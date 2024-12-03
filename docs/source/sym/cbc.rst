CBC
===


风险说明
--------

CBC存在padding oracle attack的风险，攻击者通过修改密文反复请求解密来测试padding，最终在不知道密钥的情况下成功解密。

攻击案例
--------

.. _Security Flaws Induced by CBC Padding Applications to SSL, IPSEC, WTLS...: https://www.iacr.org/cryptodb/archive/2002/EUROCRYPT/2850/2850.pdf


合规建议
--------

- 避免选用CBC模式，以GCM/CCM模式替代。
- 选用CBC模式时，结合使用常数时间的MAC函数，例如HMAC。例如，先调用CBC加密，再调用HMAC计算密文的MAC值。解密之前，先针对密文校验MAC值，校验通过，才进行解密。
- 选用CBC的padding模式时，避免使用PKCS#7、PKCS#5、ANSI X.923，尽量选用ISO10126。


参考资料
--------

.. _Timing vulnerabilities with CBC-mode symmetric decryption using padding: https://learn.microsoft.com/en-us/dotnet/standard/security/vulnerabilities-cbc-mode


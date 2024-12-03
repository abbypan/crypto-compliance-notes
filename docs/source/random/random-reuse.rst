Random Reuse
============


风险说明
--------

随机数复用可能导致ECDSA等签名算法的私钥泄漏。

攻击案例
--------

- `iPhone hacker publishes secret Sony PlayStation 3 key <https://www.bbc.com/news/technology-12116051>`_
- `Polynonce: A Tale of a Novel ECDSA Attack and Bitcoin Tears <https://research.kudelskisecurity.com/2023/03/06/polynonce-a-tale-of-a-novel-ecdsa-attack-and-bitcoin-tears/>`_


合规建议
--------

- 禁止随机数复用。
- 通信双方应各自**独立**生成安全随机数。


参考资料
--------

- `Key Discovery in ECDSA: Understanding Implementation and Security Risk <https://hacken.io/insights/ecdsa/>`_
- `ECDSA Nonce Reuse Attack <https://notsosecure.com/ecdsa-nonce-reuse-attack>`_


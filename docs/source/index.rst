密码应用合规笔记
================

.. note::

   https://github.com/abbypan/crypto-compliance-notes

目录
----

.. toctree::
   :maxdepth: 1
   :caption: 基础

   base/index
   base/base64

.. toctree::
   :maxdepth: 1
   :caption: 哈希

   hash/index
   hash/crc
   hash/md5
   hash/sha1
   hash/sha2
   hash/sha3


.. toctree::
   :maxdepth: 1
   :caption: 消息认证码

   mac/index
   mac/hmac
   mac/cmac
   mac/kmac


.. toctree::
   :maxdepth: 1
   :caption: 密钥派生函数

   kdf/index
   kdf/hkdf
   kdf/pbkdf2
   kdf/argon2


.. toctree::
   :maxdepth: 1
   :caption: 随机数

   random/index
   random/random-reuse
   random/dual_ec_drbg
   random/sha1_prng


.. toctree::
   :maxdepth: 1
   :caption: 对称密码

   sym/index
   sym/key
   sym/iv
   sym/aad


.. toctree::
   :maxdepth: 1
   :caption: 密码模式

   sym/cbc
   sym/ecb
   sym/gcm
   sym/des


.. toctree::
   :maxdepth: 1
   :caption: 非对称密码

   asym/index
   asym/private-key
   asym/public-key
   asym/rsa
   asym/ecc


.. toctree::
   :maxdepth: 1
   :caption: 公钥加密

   asym/rsa-textbook
   asym/rsaes-pkcs-v1_5
   asym/rsaes-oaep


.. toctree::
   :maxdepth: 1
   :caption: 数字信封

   asym/ecies.rst
   asym/rsaes-oaep-aes.rst


.. toctree::
   :maxdepth: 1
   :caption: 数字签名

   asym/rsassa-pkcs-v1_5
   asym/rsassa-pss
   asym/ecdsa
   asym/eddsa


.. toctree::
   :maxdepth: 1
   :caption: 密钥交换

   exchange/index
   exchange/dh
   exchange/ecdh
   exchange/noise


.. toctree::
   :maxdepth: 1
   :caption: 认证密钥交换(AKE)

   exchange/sts
   exchange/sigma


.. toctree::
   :maxdepth: 1
   :caption: 传输层安全

   tls/index
   tls/tls

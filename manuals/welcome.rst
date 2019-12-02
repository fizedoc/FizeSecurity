========
欢迎使用
========

FizeSecurity 是一个 PHP 安全库，为您的应用安全保驾护航。

FizeSecurity 是对一系列系统内置安全函数进行面向对象的再封装类库，同时添加了一些日常使用的安全类方法。 

FizeSecurity 是 Fize 项目族群的底层依赖，众多 Fize 项目依赖 FizeSecurity ，同时欢迎您使用 Fize。 

FizeSecurity 有非常完善的参考文档，其代码结构也经过精雕细琢，精炼而实用。

.. note::

   FizeSecurity 是不依赖于其他外部函数、外部类库的独立类库，同时 FizeSecurity 会根据实际情况添加、删除类库。
   使用composer的波浪线(~)版本限定方法可以让您保持绝对安全的调用环境依赖。

类库参考
========

目前 FizeSecurity 已有的类包括如下：

-  :doc:`Csrf </libraries/csrf>` : 跨站请求伪造处理
-  :doc:`Ctype </libraries/ctype>` : 字符类型检测
-  :doc:`Filter </libraries/filter>` : 过滤器
-  :doc:`Hash </libraries/hash>` : 哈希信息摘要
-  :doc:`OpenSSL </libraries/open_ssl>` : OpenSSL扩展
-  :doc:`Password </libraries/password>` : 密码散列算法
-  :doc:`Ssh2 </libraries/ssh2>` : Secure Shell2
-  :doc:`Validate </libraries/validate>` : 验证器

.. warning::

   Csrf 类暂未实现，请勿使用。
   Ssh2 类暂未实现，请勿使用。
# JavaMail解析

## 一、JavaMail简介

JavaMail，顾名思义，提供给开发者处理电子邮件相关的编程接口。它是Sun发布的用来处理email的API。它可以方便地执行一些常用的邮件传输。我们可以基于JavaMail开发出类似于Microsoft Outlook的应用程序。

JavaMail包中用于处理电子邮件的核心类是：Session，Message，Address，Authenticator，Store，Transport， Folder等。Session定义了一个基本的邮件会话，它需要从Properties中读取类似于邮件服务器，用户名和密码等信息。

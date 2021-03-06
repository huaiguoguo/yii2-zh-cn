Yii 是什么
===========

Yii 是一个基于组件的高性能 PHP 框架，目标是快速开发现代 Web 应用程序。
Yii（读作`易`）这个名称，在中文里有简单与演进两重意思，也可看作 **Yes It Is**!的缩写。


Yii 最适合干什么？
---------------------

Yii 是一个通用的 Web 编程框架，即可以用于开发各种基于 PHP 的
Web 应用。因为基于组件的框架结构和设计精巧的缓存支持，Yii 特别适合开发大型应用，如门户、论坛、内容管理系统（CMS）、电子商务项目和 RESTful Web 服务等。


Yii 相比其他框架如何？
-------------------------------------------

- Yii 实现了大多数 PHP 框架都有的 MVC（模型-视图-控制器）设计模式，并基于此模式提升了代码的组织。
- Yii 的代码简洁优雅，这是 Yii 的编程哲学。它几乎没有为实现设计模式而过度设计。
- Yii 是全栈框架，提供了大量经过验证和即时可用的功能，如查询生成器和活动记录来支持关系型数据库和 NoSQL 数据库、 RESTful API 的开发支持、多层缓存支持等。
- Yii 高度可扩展，开发者能定制或更换几乎每一段核心代码，也能利用其坚实的扩展架构优势来使用或再开发和发布 Yii 扩展。
-  Yii 高性能，这始终是 Yii 框架的首要目标。

Yii 不是独角戏，它的背后是一支[强大的核心开发团队](http://www.yiiframework.com/about/)和一个由大量专业人才组成的庞大社区，他们持续为 Yii 的开发做出贡献。Yii 开发团队紧密跟踪 Web 开发的最新趋势并从其他框架和项目挖掘最佳的实践和功能。这些功能和实践正被仔细纳入核心框架，并通过简洁优雅的接口连接。

[强大的核心开发团队]: http://www.yiiframework.com/about/

Yii 版本
------------

Yii 目前有两大主要版本可用：1.1 和 2.0。1.1 是上一代版本，目前处于维护状态。 2.0 是 Yii 采用 最新技术和协议来完全重写的版本，最新技术和协议包括 PHP 包管理器（Composer）、PHP 代码规范（PSR）、命名空间、特征（traits）等。Yii 2.0 是下一代框架，将吸收我们未来几年的主要开发成果。本指南主要介绍 2.0 版本。


要求和条件
------------------------------

Yii 2.0 需要 PHP 5.4.0 或以上版本。个别功能更详细的要求请运行发行版内的需求检查文件来查看。

使用 Yii 要求基本的面向对象编程（OOP）知识，因为 Yii 是一个纯面向对象框架。
Yii 2.0 也采用了 PHP 的很多最新功能，如[命名空间](http://www.php.net/manual/zh/language.namespaces.php)和
[特征（traits）](http://www.php.net/manual/zh/language.oop5.traits.php)。
理解这些概念有助于你更容易地掌握 Yii 2.0 。

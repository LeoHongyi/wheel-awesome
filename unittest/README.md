# 自动化单元测试

一、什么是自动化单元测试

1. 单元测试

   测试的分类
   
   A.单元测试、集成测试、系统测试

　　B.白盒测试、黑盒测试

　　C.压力测试、性能测试、安全测试

​		D.自测、交叉测试

​	单元测试（unit testing），是指对软件中的最小可测试单元进行检查和验证。对于单元测试中单元的含义，一般来说，要根据实际情况去判定其具体含义，如C语言中单元指一个函数，Java里单元指一个类，图形化的软件中可以指一个窗口或一个菜单等。总的来说，单元就是人为规定的最小的被测功能模块。单元测试是在软件开发过程中要进行的最低级别的测试活动，软件的独立单元将在与程序的其他部分相隔离的情况下进行测试。

 对开发的最小单位进行测试 通常是一个函数



2. 自动化测试

[自动化测试](https://baike.baidu.com/item/自动化测试/9815698)是敏捷开发的[基础](https://baike.baidu.com/item/基础/32794)。有效的测试策略可以更积极地提供新的功能性，加速用户反馈和提高质量。然而，对于许多开发人员而言，创建有效的自动化测试是一项独特而又陌生的挑战。



> 《xUnit测试模式》是使用当今最受欢迎的单元测试架构xUnit写自动化测试的权威指南。敏捷教练和测试自动化专家GerardMeszaros描述了68种经过证明的模式，这些模式让编写、理解和维护测试变得更容易。它还介绍了让测试更健壮、更可重复及更经济划算的方法。
>
> 作者： GerardMeszaros，是Clear-StreamConsulting（号注于敏捷开发的Calgarly咨询机构）的首席科学家和高级顾问。他具有十多年的自动化单元测试架构经验，是测试自动化模式、软件和测试重构以及易测性设计方面的知名专家。



一般是指[软件测试](https://baike.baidu.com/item/软件测试/327953)的自动化，软件测试就是在预设条件下运行系统或[应用程序](https://baike.baidu.com/item/应用程序/5985445)，评估运行结果，预先条件应包括正常条件和异常条件。



3. 自动化单元测试体系

   目前任何一种测试框架的都是对xUnit的一个实例）。它包括以下特性：

   1、用于测试期望结果的断言（Assertion）

   2、用于共享共同测试数据的测试工具

   3、用于方便的组织和运行测试的测试套件

   4、图形和文本的测试运行器






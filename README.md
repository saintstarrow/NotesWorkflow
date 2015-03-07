# NotesWorkflow
A powerful configurable workflow engine based on Notes/Domino for both clients and browsers.

# 版本历史
在2015年公开发布于网上之前，本系统已经过多年的开发和演变，但因为不是产品，并没有特别设定版本。初次发布定为3.2，之前虚构的版本历史用以记录系统经历的或虚拟的理念上的变化。今后的版本将按照Major.Feature.Maintenance的格式，即第一位数字记录主版本，逢架构改变和重大更新时变化；第二位数字为功能版本号，增加新功能时变化；第三位数字为维护版本号，记录小的修改和bug修正。

- 3.2.1	配合文档整理和优化设计。
- 3.2	进一步优化和简化流程配置。
- 3.1	重构LotusScript流程类，分离界面操作和后台操作的代码。使得可对后台流程进行单元测试，并能够批量审批流程。
- 3.0	抛弃原来采用LotusScript和表单的Web流程引擎，使用XPages和Java重新开发。与客户段工作流共用配置文档，流程界面和操作风格也一致。
- 2.3	改用类继承编写特定于具体工作流的业务逻辑。
- 2.2	采用独创的LotusScript自定义事件机制编写具体工作流的业务逻辑，使得其代码与通用流程类彻底分离。
- 2.1	重构流程配置文档，使之成为流程、节点、操作的层次体系。
- 2.0	采用LotusScript编写流程类，适用于浏览器。
- 1.0	采用LotusScript编写流程类，适用于客户端。
- 0.2	引入流程配置文档，采用公式编写通用操作。
- 0.1	采用公式逐个编写流程操作。

# 帮助文档

[我的博客](http://blog.csdn.net/starrow)上有从[89. 基于Notes/Domino的文档工作流系统（一）](http://blog.csdn.net/starrow/article/details/42521399)开始的一系列说明文档，从设计思路到代码分析。其中[94. 基于Notes/Domino的文档工作流系统（六）](http://blog.csdn.net/starrow/article/details/43484217)和[95. 基于Notes/Domino的文档工作流系统（七）](http://blog.csdn.net/starrow/article/details/44102589)介绍了如何配置和开发自定义的工作流。

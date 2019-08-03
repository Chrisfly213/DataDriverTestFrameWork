# DataDriverTestFrameWork
一.说明

    ``本实例为数据驱动测试框架搭建实践``

二.框架分析
    
    .本项目只用于学习使用， 与实际项目会有一定区别，但是思想是一样的
    .本项目未使用任何测试框架, 比如ddt数据驱动，unittest框架，pytest框架
     完全通过代码的控制及结合excel实现自动化测试的数据驱动，学习性很强
    .如果你深入理解了本项目的设计逻辑，对于以后学习ddt,PO设计模式，unittest单元测试框架有很大的帮助
    .本项目所有的元素定位表达式采用了UI对象库存储思想，当页面元素发生变化时只需修改UI对象库中的定位表达式即可完成项目的后期维护
    .所有的测试用例采用excel存储，方便管理，且可任意添加测试数据
    .项目中使用了PO设计模式，把被测项目的每个页面抽象成一个类，对每个页面的每个操作单独封装一个方法，减小代码的耦合，也方便代码的维护
    
三.如何运行此框架
    
    .克隆项目框架到本地
    .找到excel文件，可以修改里面的账号密码等数据，当然你也可以不修改
    .运行方式1：打开cmd切换到项目目录，输入命令python RunTest.py(注意：需要接此文件完整路径)
    .运行方式2：从已经配置了python解释器的ide中手动运行RunTest.py文件
    .可以根据自己的需求添加其他功能

四.本人联系方式

    .联系QQ：281754043 技术交流QQ群：878565760 个人博客地址：https://www.cnblogs.com/linuxchao/
    
五.修改记录

    .modify by linuxchao at 2019.08.03
    .修改了部分代码逻辑
    .修改了部分代码编写规范, 更加符合PEP8规范
    .添加了截图功能
    .由于126邮箱做了升级，因此修改了用例的逻辑
    .为了他人能够顺利的运行本项目，添加了环境管理文件requirements.txt文件
    .如果你clone了本项目，可以为本项目新键一个虚拟环境
     在虚拟环境中执行pip install -r requirements.txt即可为本项目安装所有的依赖库,避免使用本地环境冲突
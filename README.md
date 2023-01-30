# Harmbook

经历为期5个月的想法，还是坚持动工，开始软件工程设计，开发版本为v0.1,和[heyaspirin](https://github.com/heyaspirin)一起开发。
这个项目想的是一直做开源下去。也是为了学习golang的分布式架构，微服务。

主要思想上是利用尽可能少的技术栈实现功能。
集中在golang上。

约定同步动作标志
```bash
新文件增加：
git commit -m "ADD| [XXXX.XX]"

旧文件更新：
git commit -m "UPDATE| [XXXX.XX]"

删除动作：
git commit -m "DEL| [XXXX.XX]"

多文件更新增加：
git commit -m "BIG| [XXXX.XX]"
```


2023-01-30 
+ v0.1.0 先有页面框架
+ v0.1.1 添加服务模块
+ v0.1.2 添加分布式模块
+ v0.1.3 整体测试
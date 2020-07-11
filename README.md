## Env
- Win10
- Qt5.9.0
- QtCreator4.3.0(community)
- 开源时序数据库[pinus_db](http://www.pinusdb.cn/)

## Build
![在这里插入图片描述](./设计方案与效果/imgs/qt_build.png)
## Description
&emsp;&emsp;组态软件运行时系统原型：1. 具有模块化的图元代码设计，及基于该设计实现的组态编辑器动态生成Qt组态画面代码功能；2. 使用主从同步模式，设计及实现j集散控制系统数据区同步协议；3. 接入时序数据库完成对工业数据采集及运行时系统仿真功能。

## HighLight
- 基于缓冲区的数据管理机制解耦了分散控制系统各目标程序，减少死锁发生概率，也提高了数据访问效率从而改善实时性。
- 基于抽象数据类型的功能块代码规格减少了智慧控制系统开发维护成本。
- 基于代码复用的画面组态编译方法很好保证了监控画面的设计预期，如风格一致性，适应画面组态新发展。
- 基于时序数据库的仿真系统可以重现历史画面或模拟虚拟画面，便于开发时调试与生产时追踪。

## Detail
&emsp;&emsp;*详细设计与效果见[设计方案与效果](./设计方案与效果/README.md)*




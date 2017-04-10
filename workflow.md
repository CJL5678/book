### CI的功能

- CI，自动部署对应的分支，自动放到对应的目录里,代码检查，测试覆盖

### 开发环境到需求环境

- cz里，关闭issue

> 发现问题并没有完全修复或引发了其他问题，但是还是有关联，reopen这个问题或增加新issue关联到当前的issue

### 需求环境到master环境

- master环境不允许直接合并，全部使用pull提交（方便回滚，由于我们对于git的操作不熟练，可以通过界面处理）
- 在每周四部署时，对master代码打版本号，生成日志（手工进行）

### 流程图例

![开发流程图例](https://wlchair.gitbooks.io/fengniao/content/vender/workflow.jpg)

### 流程检查点

- CI检查通过情况
- 代码覆盖率
- changelog对应的代码版本关系是否准确
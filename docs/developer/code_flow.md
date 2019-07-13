<!--Meta
category:系统开发
title:开发流程说明
DO NOT Delete Meta Above -->


#职责说明

deb仓库人员职责
1. 向开发人员提供代码到测试仓库的机制 目前通过[pkg_debian](https://docs.deepin.io/developer/branchs/)进行处理
2. 向测试人员提供众多仓库的说明。
3. 提供测试仓库到其他仓库的包推送机制(目前由仓库人员手动维护)



开发人员维护分支和tag，根据2条原则进行
1. 符合开发团队的整体风格。　(一致性) [参考](https://docs.deepin.io/developer/git-tags/)
2. 组织上的合理性,特殊项目特殊处理。(合理性)　



#示例: 测试人员如何开始项目测试？
1. 测试事件发起人(一般是产品经理), 通知开发人员以及测试人员。
2. 开发人员通过平台将代码生成到特定的deb仓库，并告知测试人员。
3. 测试人员得知包进入仓库(开发人员告知或自行根据平台给出的通知)后进行测试
4. 测试通过后向测试事件发起人汇报结果
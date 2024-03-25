# 版本重要说明

wx版域宝，作为下一代域宝的又一个形态，目前正在逐步适配中。

得益于[ljc545w/ComWeChatRobot](https://github.com/ljc545w/ComWeChatRobot)和[JustUndertaker/ComWeChatBotClient](https://github.com/JustUndertaker/ComWeChatBotClient)项目，域宝通过onebot12协议接入wx端。虽然无法直接复用QQ版域宝的应用层，但将功能在nonebot2上重新做一遍姑且还算可以接受。

点击左侧sidebar跳转到[功能列表](/wx/manual)  

[开发日志](/wx/log)  

由于通讯层实现限制，以及避免wx风控，wx版域宝将有以下限制：
- 不会开发任何涉及生成式人工智能（文本）的功能
- 不会开发任何涉及R18的功能
- 涉及发送语音的功能将被重写为发送文本
- 涉及回复（引用）的功能将被取消回复
- 无法撤回消息
- and more...
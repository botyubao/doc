# 已支持的功能

（完善中……）

### 绑定qq
域宝的部分功能和QQ号紧耦合，所以需要使用前先关联QQ

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| bindqq | 查看当前绑定信息 | bindqq | 群聊或私聊 |
| bindqq qq号 | 根据提示，验证身份并绑定QQ | bindqq 114514 | 群聊或私聊 |

### AI绘图
<small>迁移自域宝本体</small>  
基于Stable Diffusion，后端是秋叶佬的整合包，P106-100显卡。  
默认已包含Negative Prompt。  

|指令|说明|指令示例|支持的聊天类型|
|----|----|----|----|
| AI绘图 tags | 使用给定prompts绘制一张图片。 | AI绘图 dreamy,  background, , cute, dynamic angle, hair ornament |群聊和私聊|
| SD绘图 tags | 同上 | |群聊和私聊|
| 今天我是什么少女 | 随机绘制美少女图片 | 今天我是什么少女 |仅群聊|

### 青年大学习
<small>迁移自域宝本体</small>  

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| 青年大学习 | 获取当期青年大学习信息 | 青年大学习 | 群聊和私聊 |
|无|检测到青年大学习更新时，向群内推送本期青年大学习信息|N/A|*仅帝域群聊|

### HTTP猫状态码
<small>修改自插件nonebot_plugin_HttpCat，修改以适配ob12</small>

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| httpcat \<HTTP状态码\> | 发送对应HTTP状态码的猫猫图 | httpcat 418 | 群聊和私聊 |

### 表情包制作
<small>来自插件nonebot-plugin-memes。由于wx无法图文在同一条消息内发送，所以需要携带图片参数的表情包无法制作</small>  

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| 表情包制作 | 获取所有表情包制作方案 | 表情包制作 | 群聊和私聊 |
| 表情详情 表情包关键词 | 获取表情包说明 | 表情详情 batitle | 群聊和私聊 |
| /表情关键词 文字参数 ... | 以文字参数制作指定表情包 | /batitle Granblue Fantasy | 群聊和私聊 |


### Steam Info
<small>修改自插件nonebot_plugin_steam_info，修改以适配非频道，增加解绑功能</small>  

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| steambind Steam好友代码或Steam ID | 绑定Steam账号 | steambind 114514 | 仅群聊 |
| steamunbind | 解绑steam账号 | steamunbind | 仅群聊 |
| steaminfo | 获取绑定的 Steam ID 和好友代码 | steaminfo | 仅群聊 |
| steamcheck | 看看本群谁在玩游戏 | steamcheck | 仅群聊 |

### 保存表情
<small>迁移自域宝本体</small>  
<small>话虽这么说，但其实是按照wx和ob12的逻辑彻底重写一遍...</small>  
<!--后续可能会通过其他方式实现保存gif（挖坑）-->

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| 保存表情，然后在下一条消息发送一个微信表情 | 发送这个表情包的图片或链接\(gif\)，让你可以保存到本地 | N/A | 群聊或私聊 |


### 随机咖波
<small>修改自插件nonebot-plugin-capoo，修改以适配ob12。上传功能暂未适配。</small>  

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| capoo | 获取随机咖波图 | capoo | 群聊和私聊 |

### 签到
<small>迁移自域宝本体。QQ紧耦合</small>  

|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
| 签到 | 签到 | 签到 | 仅群聊 |


### 蜜柑订阅番剧推送
<small>迁移自域宝本体</small>  
推送新番更新消息。无指令。
<!--
|指令|说明|指令示例|支持聊天类型|
|----|----|----|----|
|  |  |  |  |
-->
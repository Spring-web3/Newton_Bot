# Newton_Bot

## Newton项目介绍

Newton 是由 Magic Labs 和 Polygon Labs 联合推出的区块链统一网络，具有跨链的单一钱包和余额。Newton 旨在提高Polygon的 AggLayer 之间的互操作性，AggLayer 通过共享流动性将第 1 层和第 2 层链连接起来。该网络包括一个钱包，允许用户通过“简化的”跨链交易在各种区块链平台上存储和转移各种数字资产。

## 辅助脚本使用教程

Newton活动地址 :https://www.magicnewton.com/portal/rewards

ez-captcha打码:https://dashboard.ez-captcha.com/#/register?inviteCode=RwWnXXhDlOf

由于易语言的不可跨平台性，软件只支持windows环境运行，防火墙和杀毒软件对易语言编译的软件经常误报，可以忽略。长期使用建议挂在海外云服务器，有每日任务之类的可以长期挂机。
首次使用请将spring.exe放在C盘根目录，这是后续每个软件需要用到的nodejs后端接口服务。
请将RSCProject.dll和MagicNewtonBot.exe放置在同一目录下，MagicNewtonBot.exe有用到RSCProject.dll的支持库配置。
软件为免费提供分享，卡密key:

```javascript
2106aca2-e26d-4d60-8d61-2b51ad9bb30a
```

卡密key会不定时更新，请关注X和TG获取最新卡密信息。
软件免费分享，不开源，如果有顾虑的小伙伴请不要选择使用。信任的朋友也请使用不常用的无余额撸毛钱包和小余额钱包。
钱包安全由自己负责，本软件不承担任何责任。也欢迎任何技术大佬抓包反编译检测软件是否包含恶意程序。

![image](https://github.com/user-attachments/assets/e722c97a-9491-4a3a-b45a-4e31e55cfb83)


脚本实现了钱包全自动注册账号登录，完成一次性任务，和每天的摇骰子游戏获得积分。通过任务与获得的积分是后续空投的凭证。登录注册有谷歌人机验证，所以需要注册ez-captcha平台账号来打码验证。
注册完ez-captcha充值后，把仪表盘的客户端密钥复制粘贴在软件这里。
![image](https://github.com/user-attachments/assets/056c6e9f-75ef-4f4c-998b-7947f058733f)


然后新建一个txt文本，每行文本内容格式为 钱包----私钥
一个钱包一行，然后鼠标左键点击txt文本拖到软件上面松开鼠标左键,软件会自动导入加载文本内数据。
文本格式为:
![image](https://github.com/user-attachments/assets/cc10f8bc-caef-4068-bd4c-c032f34568c8)

都是空钱包，大家别激动，是为了大家更方面看。

首次导入钱包然后选中第一次注册，执行完成会导出一个注册成功文本，然后把注册成功文本导入软件跑做任务，做任务跑完后，重新导入注册成功文本，然后选中每日游戏，直接点设置定时开始任务，不要再关闭软件，每天会自动执行每日游戏（推荐软件挂在海外服务器），每天需要关闭电脑的话就不要用定时功能，
每天手动打开软件执行每日游戏即可。
登陆的token会失效，如果session失效，重新打开软件导入钱包私钥文本选中执行第一次注册功能即可获取到最新的登录token。令牌有效期应该在一个月左右。只有执行第一次注册功能需要打码，会花费ez-captcha余额。

![image](https://github.com/user-attachments/assets/67677b20-63ec-4f28-b28c-4d6619cdc2ba)

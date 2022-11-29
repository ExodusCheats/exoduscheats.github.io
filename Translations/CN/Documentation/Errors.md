---
title: Exodus RDR2的错误
permalink: /CN/Errors
layout: cn
---
### [首页](../index.md) / 错误
---
Exodus RDR2的错误以及如何修复它们
- [Bad Client HWID](#bad-client-hwid)
- [1337 Hacker Detected](#1337-hacker-detected)
- [Invalid Fields](#invalid-fields)
- [Failed to Find 08F1509C](#failed-to-find-08f1509c)
- [Request Error](#request-error)
- [Process Crashed (Last Script)](#process-crashed-last-script)
- [Process Crashed Server Error](#process-crashed-server-error)
- [Unauthorized (Invalid Credentials)](#unauthorized-invalid-credentials)
- [Unauthorized (Valid Credentials)](#unauthorized-valid-credentials)
- [Failed to Fetch User Data](#failed-to-fetch-user-data)
- [Bad Client Signature](#bad-client-signature)
- [Missing Required Data](#missing-required-data)
- [Local Ownership Failed](#local-ownership-failed)
- [Malformed Response](#malformed-response)
- [Failed to Select GPU](#failed-to-select-gpu)

## Bad Client HWID
1. 登录并进入你的[Exodus账户](https://exodusmenu.com/account).
2. 在设备锁下按重置您的HWID
3. 重新注入

**注意：** 按下"重置按钮"后 将有6小时的冷却时间

## 1337 Hacker Detected
*Nice try, hacker. You're one step closer to getting nowhere.*

在运行Exodus时，请关闭以下程序。
- Debuggers (ex: IDA, x64dbg, etc.)
- Cheat Engine
- Process Hacker
- MSI Afterburner
- ...

## Invalid field(s)
这个错误是由以下原因造成的:
1. 你的电子邮件是错误的
2. 你的密码是错误的

要解决这个问题，只需遵循以下路径:
1. 进入`C:\Users\YourUser\AppData\Roaming\Exodus Client`或按`win+r`并输入`AppData\Roaming\Exodus Client`
2. 用记事本或您选择的文本编辑器打开`Credentials.json`，并修改为正确信息:
```json
{
    "e": "注册Exodus时设定的邮箱例如：xxxx@email.com",
    "p": "注册Exodus时设定的密码"
}
```
3. 按`Ctrl+S`保存你刚才的改动
4. 完成，现在你所要做的就是再次注入

## Failed to Find 08F1509C
从你的RDR2游戏目录中删除`dinput8.dll`文件

## Request Error
当Exodus无法连接到Exodus服务器时就会发生请求错误

虽然目前还没有100%解决这个错误的方法，但你可以尝试使用VPN，它已经为一些人解决了这个问题

## Process Crashed (Last Script)
如果你在第其他错误提示中遇到`Process Crashed`错误提示......那么这个修复方法可能适合你
1. 进入`C:\Users\YourUser\AppData\Roaming\Exodus Client\Library\Red Dead Redemption 2\Client`或按`win+r`键，输入`AppData\Roaming\Exodus Client\Library\Red Dead Redemption 2\Client`
2. 删除`State.json`

注意：这样做会重置你Exodus RDR2设置的配置

## Process Crashed Server Error
Exodus服务器关闭了，需要耐心等待重启

## Unauthorized (Invalid Credentials)
这个错误是由以下情况引起的:
1. 你的`Credentials.json`包含不正确的信息
> [如何正确输入文件内你的邮箱及密码](#invalid-fields)
2. 你没有激活你购买的钥匙
> [如何以及在哪里激活购买的钥匙](FAQ.md#how-and-where-do-i-redeem-my-license)

## Unauthorized (Valid Credentials)
重装您的Windows系统

## Failed to Fetch User Data
重新启动RDR2并再次注入

## Bad Client Signature
这个错误发生在你使用别人的Exodus DLL时,当下载Exodus DLL时,你的账户将为该DLL创建一个独特的签名

[登录Exodus官网,下载你账户库中的Exodus DLL](https://exodusmenu.com/account/library).

## Missing Required Data
如果你使用的是VPN，请切换到不同的VPN服务器或完全切换到不同的VPN

如果你不使用VPN或上述方法不奏效，请尝试重新启动RDR2/你的系统

## Local Ownership Failed
这个错误是由以下情况引起的。
1. 你的`Credentials.json`文件包含不正确的信息
> [如何正确输入你的邮箱及密码](#invalid-fields)
2. 你的账户没有连接一个有效的激活
> [如何以及在哪里激活购买的钥匙](FAQ.md#how-and-where-do-i-redeem-my-license)

## Malformed Response
当Exodus的主机供应商出现故障或问题时就会出现这个错误。我们和你对此都无能为力

你可以随时前往我们[的不和谐服务器](https://discord.gg/YVWGTt87E8)并查看[#announcements](https://discord.com/channels/1035943230467997836/1037813684774391808)

## Failed to Select GPU
只需改变你的（游戏内）图形API

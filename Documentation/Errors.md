---
title: Exodus RDR2 Errors
permalink: /Errors
---
### [Home](/) / Errors
---
Exodus RDR2 errors and how to fix them.
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
1. Go to [your Exodus account](https://exodusmenu.com/account).
2. Press `Reset` under Device Lock.
3. Re-inject.

**Note:** There is a **1 week cooldown** after you press `Reset`.

## 1337 Hacker Detected
*Nice try, hacker. You're one step closer to getting nowhere.*

Please close the following programs while running Exodus:
- Debuggers (ex: IDA, x64dbg, etc.)
- Cheat Engine
- Process Hacker
- MSI Afterburner
- ...

## Invalid field(s)
This error is caused by the following:
1. Your Email is wrong.
2. Your Password is wrong.

To fix this, simply follow these steps:
1. Go to `C:\Users\YourUser\AppData\Roaming\Exodus Client` or press `win + r` and enter `AppData\Roaming\Exodus Client`.
2. Open `Credentials.json` with Notepad or a text editor of your choice and fill in your account information:
```json
{
    "e": "your email here",
    "p": "your password here"
}
```
Replace `your email here` with the email address you used to sign up to Exodus and `your password here` with your Exodus password.

3. Save the changes you just made by pressing `Ctrl+S`.
4. Done. All you have to do now is inject again.

## Failed to Find 08F1509C
Delete `dinput8.dll` from your RDR2 Game Directory.

## Request Error
Request Error happens when Exodus fails to Connect to the Exodus server.

Although there is currently no 100% solution to this error, you can try using a VPN that has fixed it for some people.

## Process Crashed (Last Script)
If you get the `Process Crashed` Error on Script 20, 21, 22, 23, and 24... Then this fix might be for you!
1. Go to `C:\Users\YourUser\AppData\Roaming\Exodus Client\Library\Red Dead Redemption 2\Client` or press `win + r` and type `AppData\Roaming\Exodus Client\Library\Red Dead Redemption 2\Client`.
2. Delete `State.json`.

Note: Doing this will reset your Exodus RDR2 settings.

## Process Crashed Server Error
The Exodus server is down, all you can do is wait.

## Unauthorized (Invalid Credentials)
This error is caused by the following:
1. Your `Credentials.json` contains incorrect information.
> [How to correctly input your Credentials.](#invalid-fields)
2. You didn't redeem your license.
> [How and where to redeem your license.](FAQ.md#how-and-where-do-i-redeem-my-license)

## Unauthorized (Valid Credentials)
Restart your system.

## Failed to Fetch User Data
Restart RDR2.

## Bad Client Signature
This Error happens when you are using someone else's Exodus DLL. When downloading the Exodus DLL, your account will create a unique signature for that DLL.

Download the Exodus DLL from [your library](https://exodusmenu.com/account/library).

## Missing Required Data
If you are using a VPN, switch to a different VPN server or switch to a different VPN entirely.

If you don't use a VPN or the above method didn't work, try restarting RDR2/your system.

## Local Ownership Failed
This error is caused by the following:
1. Your `Credentials.json` file contains incorrect information.
> [How to correctly input your Credentials.](#invalid-fields)
2. You don't have an active license attached to your account. 
> [How and where to redeem your License.](FAQ.md#how-and-where-do-i-redeem-my-license)

## Malformed Response
This Error occurs when the hosting provider for Exodus has outages or problems. There's nothing we or you can do about it.

You can always head to our [Discord Server](https://discord.gg/YVWGTt87E8) and check [#announcements](https://discord.com/channels/1035943230467997836/1037813684774391808).

## Failed to Select GPU
Simply change your (in-game) Graphics API.

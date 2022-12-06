---
title: Exodus RDR2 FAQ
permalink: /FAQ
---
### [Home](../index.md) / FAQ
---
Frequently asked questions and their answers.
- [How do I inject Exodus RDR2?](#how-do-i-inject-exodus-rdr2)
- [How much does Exodus RDR2 cost?](#how-much-does-exodus-rdr2-cost)
- [What account region should I choose?](#what-account-region-should-i-choose)
- [What does an Exodus license look like?](#what-does-an-exodus-license-look-like)
- [How and where do I redeem my license?](#how-and-where-do-i-redeem-my-license)

## How do I inject Exodus RDR2?
1. Make sure you have [redeemed your license](#how-and-where-do-i-redeem-my-license).
2. Disable any Anti-Virus software including Windows Defender temporarily.
3. Download [Xenos Injector](https://github.com/DarthTon/Xenos) from the [official GitHub repository](https://github.com/DarthTon/Xenos/releases/download/2.3.2/Xenos_2.3.2.7z) & this product from [your Exodus library](https://exodusmenu.com/account/library).
4. Extract Xenos from `Xenos_2.3.2.7z` using a free file archiver like [7-Zip](https://www.7-zip.org/download.html) or [WinRAR](https://www.rarlab.com/download.htm).
5. Add an exclusion for the Xenos folder/Xenos64.exe and the Exodus DLL to [Windows Security](https://support.microsoft.com/en-us/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26) or other Anti-Virus software.
6. Open the 64-bit Xenos injector (`Xenos64.exe`) and add the downloaded Exodus DLL to it.
7. Start Red Dead Redemption 2.
8. Select Freemode in the Online Main Menu.
9. After 10 seconds, select `RDR2.exe` as process in the Xenos Injector and click Inject.
10. Wait until a console window opens asking you to enter your account information in "Credentials.json".
11. The client folder should be opened automatically, if not, either go to `C:\Users\YourUser\AppData\Roaming\Exodus Client` or press `win + r` and enter `AppData\Roaming\Exodus Client`.
12. Open `Credentials.json` with Notepad or a text editor of your choice and fill in your account information:
```json
{
    "e": "youremail@email.com",
    "p": "yourpassword"
}
```
Replace `youremail@email.com` with the email address you used to sign up to Exodus and `yourpassword` with your Exodus password.

13. Save the changes you just made by pressing `Ctrl+S`.
14. Done. All you have to do now is inject again.

## How much does Exodus RDR2 cost?
```
Exodus RDR2 Lite 1 Day: 2.50$
Exodus RDR2 Lite 1 Week: 5$
Exodus RDR2 Lite 1 Month: 10$
Exodus RDR2 Lite 3 Months: 20$
Exodus RDR2 Lite Lifetime: 25$

Exodus RDR2 Full 1 Day: 5$
Exodus RDR2 Full 1 Week: 10$
Exodus RDR2 Full 1 Month: 15$
Exodus RDR2 Full 3 Months: 35$
Exodus RDR2 Full Lifetime: 75$
```

## What account region should I choose?
Please select your region of residence as the account region, as our licenses are region locked.
- Europe (Russia as well)
- Asia
- USA (North America & South America)
- Other (Africa, Australia, Middle East etc.)

## What does an Exodus license look like?
Exodus licenses are 39 characters long, consist of letters, numbers and hyphens and start with the region code.
- `EU-XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX`
- `AS-XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX`
- `US-XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX`
- `OT-XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX`

## How and where do I redeem my license?
1. Go to the [Exodus Store](https://exodusmenu.com/store).
2. Press on either [Red Dead Online Mod Menu](https://exodusmenu.com/store/red-dead-online/rdr-online-mod-menu/view) or [Red Dead Online Mod Menu Lite](https://exodusmenu.com/store/red-dead-online/rdr-online-mod-menu-lite/view).
3. Press `Use License` and redeem your license.

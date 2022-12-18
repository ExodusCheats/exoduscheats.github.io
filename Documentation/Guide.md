---
title: Getting Started with Exodus RDR2
permalink: /Guide
---
### [Home](/) / Getting Started
---
## Getting started with Exodus RDR2
1. Make sure you have [redeemed your license](FAQ.md#how-and-where-do-i-redeem-my-license).
    1. Go to the [Exodus Store](https://exodusmenu.com/store).
    2. Press on either [Red Dead Online Mod Menu](https://exodusmenu.com/store/red-dead-online/rdr-online-mod-menu/view) or [Red Dead Online Mod Menu Lite](https://exodusmenu.com/store/red-dead-online/rdr-online-mod-menu-lite/view).
    3. Press `Use License`.
    ![Exodus Store](../assets/img/Exodus_Store.png)
    4. Enter your Exodus license.
    ![Exodus Store](../assets/img/Exodus_Store_2.png)
    5. Redeem your Exodus license.
    ![Exodus Store](../assets/img/Exodus_Store_3.png)
2. Disable any Anti-Virus software including Windows Defender temporarily.
    1. Press `Start` and go to (Windows) settings.
    2. Click on `Update & Security`.
    ![Windows Settings](../assets/img/Windows_Settings.png)
    3. Click on `Windows Security`.
    ![Windows Settings](../assets/img/Windows_Settings_2.png)
    4. Click on `Open Windows Security`.
    ![Windows Settings](../assets/img/Windows_Settings_3.png)
    5. Click on `Virus & threat protection`.
    ![Windows Security](../assets/img/Windows_Security.png)
    6. Under `Virus & threat protection settings`, click on `Manage settings`.
    ![Windows Security](../assets/img/Windows_Security_2.png)
    7. Turn off `Real-time protection`.
    ![Windows Security](../assets/img/Windows_Security_3.png)![Windows Security](../assets/img/Windows_Security_4.png)
3. Download [Xenos Injector](https://github.com/DarthTon/Xenos/releases/download/2.3.2/Xenos_2.3.2.7z) from the [official GitHub repository](https://github.com/DarthTon/Xenos/releases/download/2.3.2/Xenos_2.3.2.7z).
4. Download Exodus RDR2 from [your Exodus library](https://exodusmenu.com/account/library).
![Exodus Library](../assets/img/Exodus_Library.png)
5. Extract Xenos from `Xenos_2.3.2.7z` using a free file archiver like [7-Zip](https://www.7-zip.org/download.html) or [WinRAR](https://www.rarlab.com/download.htm).
6. Add an exclusion for the Xenos folder/Xenos64.exe and the Exodus DLL to [Windows Security](https://support.microsoft.com/en-us/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26) or other Anti-Virus software.
    1. In `Windows Security`, scroll down till you see `Exclusions` and click on `Add or remove exclusions`.
    ![Windows Security](../assets/img/Windows_Security_5.png)
    2. Click on `Add an exclusion`.
    ![Windows Security](../assets/img/Windows_Security_6.png)
    3. Select either `File` or `Folder` and add an exclusion for each `Xenos64.exe` and `ExodusRDR2.dll`/`ExodusLiteRDR2.dll`.
    ![Windows Security](../assets/img/Windows_Security_7.png)
7. Open the 64-bit Xenos injector (`Xenos64.exe`) and add the downloaded Exodus DLL by either pressing `Add` or simply dragging and dropping the .DLL into Xenos64.
![Xenos64](../assets/img/Xenos64_1.png)
7. Start Red Dead Redemption 2.
8. Select Freemode in the Online Main Menu.
9. After 10 seconds, select `RDR2.exe` as process in the Xenos Injector and click Inject.
![Xenos64](../assets/img/Xenos64_2.png)![Xenos64](../assets/img/Xenos64_3.png)
10. Wait until a console window opens asking you to enter your account information in "Credentials.json".
![Exodus Console](../assets/img/RDR2.png)
11. The client folder should be opened automatically, if not, either go to `C:\Users\YourUser\AppData\Roaming\Exodus Client` or press `win + r` and enter `AppData\Roaming\Exodus Client`.
![Windows Explorer](../assets/img/explorer.png)
12. Open `Credentials.json` with Notepad or a text editor of your choice and fill in your account information:
```json
{
    "e": "your email here",
    "p": "your password here"
}
```
![Windows Notepad](../assets/img/notepad_1.png)
Replace `your email here` with the email address you used to sign up to Exodus and `your password here` with your Exodus password.
![Windows Notepad](../assets/img/notepad_2.png)
13. Save the changes you just made by pressing `Ctrl+S`.
14. Done. All you have to do now is inject again.

How To Make A Discord Dialer
============================

A Discord dialer is an isolated Virtual Machine that is used to dial a number and feed the call audio directly into Discord. This detailed guide should make the process a breeze to setup for anyone with basic knowledge of windows. The instructions in this document have been tested on [VirtualBox](https://www.virtualbox.org/wiki/Downloads) & [VM-Ware](https://www.vmware.com/), using Windows 7, 8 & 10 on the guest machine.

> The method described in these instructions does not include steps on masking your network or computer identity. Please follow our [README.md](https://github.com/ralphyjohnson/How-to-Setup-A-Stealthy-Virtual-Machine/blob/master/README.md) on [How to Setup A Stealthy Virtual Machine](https://github.com/ralphyjohnson/How-to-Setup-A-Stealthy-Virtual-Machine/) for more information on virtual machines and how to increase anonymity.

#### What You Will Need to Get Started:
- [Virtual Machine](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
- [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html)
- [Virtual Cables](https://drive.google.com/drive/folders/0BxcRDotcMjR2a0NCeEdJQVBMd1E?usp=sharing)
- [Discord App](https://discordapp.com/)

1. Setup Virtual Machine
 - Download [VM-Ware](https://www.vmware.com/) or [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
 - Get Windows OS disk image from [Microsoft](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
 - Create new virtual machine from disk image
 - Ensure you have a working internet connection before proceeding - In some cases, VM-Ware machines need to have a Network Adaptor configured. To do this, right-click the virtual machine in the left taskbar and select > Settings > Hardware > Add (Run as Admin) > Custom: Specific Virtual Network > VMnet0 (VM-Ware) > OK

2. Download Browser of your Choice
 - We reccommend google chrome because they support a [FireRTC chrome app](https://chrome.google.com/webstore/detail/firertc/iaamfpbohecgihgnbhmppgekdjkbolah?hl=en-US)
 - In some cases certain disk images come with unsupported versions of Internet Explorer & you may have to downlaod [Firefox](https://www.mozilla.org/en-US/firefox/new/), then download the desktop version of [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html) through [Firefox](https://www.mozilla.org/en-US/firefox/new/).

3. Download VB Audio Cables
 - This step may require you give IEUser full administrative rights on the virtual machine
 - [Download VB-Audio](https://drive.google.com/drive/folders/0BxcRDotcMjR2a0NCeEdJQVBMd1E?usp=sharing) packages and install
 - It will notify you to restart your system to complete the installation

4. Download Discord
 - Download and install [Discord](http://www.discordapp.com)
 - You can also use their browser version of the app, In which case you may need to grant access for the application to access your microphone through your browser. You should get an alert in the top-left corner of your broswer when you first login to the app. Select "Allow" to allow access to your microphone
 - Setup a discord dialer account and login

5. Feed FireRTC Audio into Discord
 - Open your Windows Sound Properties. You can do this by right clicking the audio speaker located in the bottom-right corner of your screen, then left clicking Playback devices
 - Right click Cable B and set to "set as Default Communication Device"
 - Right click Cable A and set to "set as Default Device"
 - Navigate to the Recording Tabbed Section
 - Right click Cable B and set to "set as Default Communication Device"
 - Right click Cable B again and set to "set as Default Device"
 - Press OK to save your changes
 - Go into the Discord application
 - Locate the cog-wheel / gear icon to enter your User Settings
 - Navigate to Voice section of the App Settigns
 - In the Input Device dropdown select "Cable A"
 - In the Output Device dropdown select "Cable B"
 - Make a test call to ensure audio is feeding into the call correctly

#### Resources:
- [VM-Ware](https://www.vmware.com/)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Free VM Microsoft Disk Images](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
- [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html)
- [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [VB-Audio Cables A & B](https://drive.google.com/drive/folders/0BxcRDotcMjR2a0NCeEdJQVBMd1E?usp=sharing)
- [Discord](http://www.discordapp.com)
- [FireRTC](http://www.firertc.com)
- [FireRTC Chrome App](https://chrome.google.com/webstore/detail/firertc/iaamfpbohecgihgnbhmppgekdjkbolah?hl=en-US)

---

> Inspired by [Malcolm Merlyn](https://www.youtube.com/channel/UC_b1bYSup-dHfwIoIXP0zPQ)
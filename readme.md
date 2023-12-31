


<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>Linux Shenanigans :: WhatsApp Desktop Applet</h1>
<h3>◦ Made for Fun and Use</h3>

<p align="center">

</p>

<img src="https://img.shields.io/github/languages/top/RudradevArya/LinuxShenanigans-WhatsApp-Desktop" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📍 But WHY?](#-But-WHY??)
- [📦 Just use Web?](#-Just-use-WhatsApp-Web!!-Right?)
- [📂 Note](#-Note)
- [🚀 Config Steps](#-Config-Steps)
- [🛣 Project TaskList](#-Project-TaskList)

---



# Linux Shenanigans :: WhatsApp Desktop Applet

## But WHY??
### Long story short I Shifted to Linux Mint and there was no desktop application for WhatsApp all other seemed a bit sus

#### Just use WhatsApp Web!! Right? 
### No!! 
#### it gets hard to navigate through multiple tabs and windows and browsers to find and as no Desktop App was available i just used a Shell Script to navigate to a browser and open that webpage in its own window basically looking like its own App hence the name Apple

> # **Note**
> ### Any web app can be make using this method (Steam, YouTube on any browser chromium based or fireforx or whatever floats your boat)




### 🔧 Config Steps

1. Type it into Terminal which'll open Text editor
```sh
sudo -H gedit /usr/share/applications/whatsapp-webapp.desktop
```
This might require password, it bascially create a `whatsapp-webapp.desktop` at the destination `/usr/share/applications/` using the gedit text editor

2. Change this path in the `whatsapp-webapp.desktop` file in the script :
```sh
/opt/google/chrome/google-chrome
```
```sh
/usr/bin/firefox
```
or any other chromium based browser u have

3. Change Icon if you wish or the link for the webpage of you choice:

4. Navigate to `/usr/share/applications/` and execute the Shell Script
```sh
sudo chmod +x whatsapp-webapp.desktop
```
and Press enter, there should be no error and no comments
This comment using the Superuser access changes the mode of the file to [e]xecute the Shell Script

# Enjoy


## 🛣  Project TaskList

> - [X] `ℹ️  Find files of browsers `
> - [X] `ℹ️  Shell scripting basics`
> - [X] `ℹ️  Basic Script`
> - [X] `ℹ️  Testing`
> - [X] `ℹ️  Icons?`
> - [X] `ℹ️  Used CoPilot image generator for making india+space+WA icon`
> - [X] `ℹ️  Remove background from the icon`
> - [ ] `ℹ️  Enjoy`

---
# Android

## Table of Contents

#### [1. Custom ROMs](/AndroidStuff.md#1-custom-roms-for-phone-brandmodel)

#### [2. Open Source Alternatives](/AndroidStuff.md#2-open-source-alternatives-to-applications)

#### [3. Modded Applications](/AndroidStuff.md#3-modded-applications)

#### [4. Miscellaneous Applications](/AndroidStuff.md#4-miscellaneous-applications-1)

#### [5. DITO SIM No Data Fix](/AndroidStuff.md#5-dito-sim-setup)

#### [6. BPI SIM Verification Error](/AndroidStuff.md#6-bpi-app-not-verifying-sim)


## 1. Custom ROMs for Phone Brand/Model

Searching ```Custom ROM for x phone/brand/model``` barely helps you and may sometimes suggest ROMs that are actually not compatible with your device. Beware!

#### Resources to find suitable ROMs for your Smartphone
1. XDA Forums
> Just search for ```{device} custom ROMs xda forums/developers```

2. Reddit
> There are various subreddits that provide guides to ROMs you can find, although a more specific subreddit that caters towards your device is hard to find or none at all

3. Telegram
> Searching for groups like ```{device} ROMs``` can lead you to one or more for your specific device

4. YouTube
> Just like Reddit, there are various videos floating around that gives guides to custom ROM for speficic devices

#### Required Tools to Custom ROM-ing
Assuming your bootloader has already been unlocked

1. platform tools by Android
> Required for installing custom recoveries like Orange Fox, TWRP, and such
2. Recovery Software(?)
> Image and ZIP file of device-specific custom recovery. It almost always bundled with posts about custom ROMs in Telegram
3. Custom ROM
> Of course, you need to download the ZIP file of the custom ROM you want or have it inside your device's internal storage


### 1.1 Realme-specific Guide for Custom ROMs

Here is the Telegram Group for Realme 6 Pro: [Realme 6 Pro | Updates [Official]](https://web.telegram.org/a/#-1001493467397)

There, you can find the latest Orange Fox Recovery and various other custom ROMs *(personally, I recommend SuperiorOS)*

If you don't have a custom recovery installed yet, follow the steps to install Orange Fox:

***This method requires a computer!***

1. Download the image file of OFRP to your PC
2. Download platform-tools from Android
3. Extract the platform-tools and open the command prompt inside the directory
4. Download the OFRP ZIP file to your device
5. Reboot your device to fastboot mode
6. Flash the image file by using the command
    > fastboot flash recovery {ofrp-image-filename}.img
7. Reboot your device to recovery using the command
    > fastboot reboot recovery
8. Wipe your device by:
    - Clicking the `Trash` Icon
    - Enabling the following if available: `metadata`, `system`, `vendor`, `cache`, `dalvik cache`, and `data`
    - Swipe to Wipe
9. Flash the OFRP Zip File by clicking the `Files` Icon and looking for the ZIP file and Swipe to Install
10. Format your device by going to the `Trash` Icon and directing to Format Data and typing `yes`
11. Reboot device and enjoy the ROM



## 2. Open-Source Alternatives to Applications

1. FlorisBoard
    - A keyboard alternative to GBoard
    - Dictionary feature
    - Allow customizing theme (not with image background ones)
    - Gesture feature
    - Clipboard history feature
    - Private mode feature

2. Aves Gallery
    - Available in Play Store
    - Clean UI

3. Fossify Gallery
    - Has editing features
    - Material design
    - Good UX

4. Material Files
    - Material design
    - Similar to Google Files
    - No Recycle Folder (con)

5. Firefox
    - lmao
    - best browser
    - fuck chrome

6. Nekogram
    - Alternative to Telegram
    - Simple yet versatile
    - Allows simple customization

## 3. Modded Applications

Applications that are either modded or straight up cracked, lol

### 3.1 ReVanced Manager
An application that modify android applications and also a continuation of the legacy of Vanced

#### 3.1.1 Recommended ReVanced Applications
1. YouTube
> Has over 60 patches available (block ads, remove sponsors, enhance privacy, and allow customization and bringing back old youtube contexts)

### 3.2 A certain Spotify Patcher 
(xManager)
An application that patches Spotify and Wave

## 4. Miscellaneous Applications

Applications that are not for day-to-day use, applications that are posibly for entertainment, utility, and broad stuff

### 4.1 Tachiyomi and Forks

A manga reader application that supports that uses "Extensions" to integrate various websites in-app to read and discover

#### 4.1.1 Neko
A fork of Tachiyomi that specializes on MangaDex

#### 4.1.2 TachiyomiJ2K
A fork of Tachiyomi that has better UI

#### 4.1.3 TachiyomiSY
A fork of Tachiyomi that specializes on adult content (Manhwa, doujinshi, etc.)


### 4.2 YTDLnis
A yt-dl based application for downloading content for various sites. Look up yt-dlp supported sites to see the supported sites.

### Droid-ify
An F-Droid alternative/client that manages open-source applications where you can download and update, basically a Play Store for FOSS

## 5. DITO SIM Setup

This is a setup for DITO Sim if the Mobile Data function does not work. Follow the steps below.

1. Open DITO SIM 
> Network & Internet > SIMs

2. Go to Access Point Names
3. Create one by clicking the `+` Icon
4. Set the name to whatever you want (preferrably DITO Internet)
5. Set APN to internet.dito.ph
6. Set MCC to 515
7. Set MNC to 66
8. Set APN type to default
9. Set APN protocol to IPv4/IPv6
10. Set APN Roaming protocol to IPv4
11. Enable APN
12. Save

## 6. BPI app Not Verifying SIM

If you cant verify your BPI account through SMS, follow the steps below.

### 6.1 Reinstall BPI app

### 6.2 Disable Unused SIM
If you are on dual-SIM, disable the unused SIM or physically remove it from the port and try again

### 6.3 Send Encrypted Content to Another Number
Your number is automatically sending a verification message to DEVreg, but sometimes fail. To bypass it, you can send the verification message to other numbers within one minute.

1. Send the Verification Message in Usual Way
2. Go to Messages app and copy the message you sent to DEVreg
3. Send the copied message to the following numbers: `09178910000`, `09188910000`, or `225657764`

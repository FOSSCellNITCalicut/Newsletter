---
title: "Syncing Notes and Files via Syncthing and Joplin"
subtitle: A Comprehensive Guide
date: 2023-08-21T00:36:10+05:30
tags: ["FOSS", "Syncthing", "Joplin"]
bigimg: [{src: "/syncthingJoplin/logos.jpg", desc: "Syncthing and Joplin"},]
---

# Syncthing and Joplin: The FOSS Way to Sync Notes

In the world of Free and Open Source Software (FOSS), maintaining privacy and data ownership is crucial. Traditional note-taking apps often require compromising these principles to achieve synchronization across devices. However, with the combination of Syncthing and Joplin, FOSS enthusiasts can synchronize their notes seamlessly without relying on external cloud services. Let's explore how this powerful duo empowers users to keep their notes in sync while respecting their privacy.

Syncthing and Joplin provide a reliable and privacy-focused solution that utilizes peer-to-peer sharing. This means that your notes are synchronized directly between your devices without any intermediary cloud services. Your data remains private, residing solely on your devices.

## How Syncthing Works

Syncthing is a continuous file synchronization tool that ensures your data is safe, secure, and easily accessible. It can sync files between devices on a local network or between remote devices over the Internet. Data security and data safety are built into its design, as the files are shared through a local or remote network only. It's easy to set up and use, and it syncs whenever there are changes in the corresponding folder.


## Setting Up Syncthing

The latest versions of the software for almost all operating systems, including GNU/Linux, Windows, MacOS, and Android, are available [here](https://syncthing.net/downloads/). Most GNU/Linux distros have syncing in their default repositories, so you can always install it directly from your terminal using apt, dnf, or Pacman. It is also available on [F-droid](https://f-droid.org/packages/com.nutomic.syncthingandroid/) and [play store](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid) for Android. There is no official app for iOS, but you can use [Möbius Sync](https://www.mobiussync.com/), an open-source Syncthing client available in the iOS app store.

![Syncthing Screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Syncthing_1.7.1_web_interface.png/640px-Syncthing_1.7.1_web_interface.png)

To begin, install Syncthing on two devices connected to the same network. Initiate the Syncthing service on both devices. For Android and iOS, this action is performed when the app starts and runs in the background. On Linux distributions and macOS, launch Syncthing via the applications menu, while for Windows, execute the `syncthing.exe` file. The admin GUI launches automatically and remains accessible at `http://localhost:8384/` for PCs, while the app itself serves as the admin GUI for Android and iOS. Next, navigate to Settings and select "Show ID" on one device, copying or scanning the ID from the other device. Upon sending a connection request to the first device, accept it to complete the device setup. Create a new folder on one device, adding it to the Syncthing GUI. Ensure you share this folder with the previously connected device and accept the share request on the latter. This concludes the setup and the files within the designated folders will synchronize across both devices.

## Joplin for Note-Taking

Joplin emerges as a versatile, open-source note-taking and to-do application. Noteworthy features include storing notes in Markdown format and facilitating easy formatting and editing. Available across desktop, mobile, and terminal applications, Joplin ensures seamless access on various devices. Notes are organized into notebooks, while the provision to assign tags to notes and notebooks enhances accessibility.

![Joplin Screenshot](https://joplinapp.org/images/home-top-img-2x.webp)

## Synchronizing with Joplin

After establishing a Syncthing folder, configuring Joplin synchronization is pretty straightforward. Install [Joplin](https://joplinapp.org/download/) on both devices and navigate to configurations or options, depending on the operating system. Select "Synchronization" and designate the filesystem as the synchronization target. Specify the directory for synchronization (absolute path) as the folder earlier added to Syncthing, and disable the failsafe option below, and Voila! Any changes made within Joplin on one device will automatically synchronize with other connected devices once the Synchronise button is pressed.


 The combination of Syncthing and Joplin seamlessly integrates FOSS principles with the convenience of cross-device note synchronization. This will relieve FOSS enthusiasts of the need to depend on services like Google Keep Notes or Notion, thus being able to maintain an all-FOSS environment on their devices.

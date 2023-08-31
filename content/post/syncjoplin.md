---
title: "Syncing Notes and Files via Syncthing and Joplin"
subtitle: A Comprehensive Guide
date: 2023-08-21T00:36:10+05:30
tags: ["FOSS", "Syncthing", "Joplin"]
bigimg: [{src: "/syncthingJoplin/logos.jpg", desc: "Syncthing and Joplin"},]
---

# Syncthing and Joplin: The FOSS Way to Sync Notes

In the world of Free and Open Source Software (FOSS), maintaining privacy and data ownership is crucial. Traditional note-taking apps often require compromising these principles to achieve synchronization across devices. However, with the combination of Syncthing and Joplin, FOSS enthusiasts can synchronize their notes seamlessly without relying on external cloud services. Let's explore how this powerful duo empowers users to keep their notes in sync while respecting their privacy.
The Power of Peer-to-Peer Note Syncing

Syncthing and Joplin provide a reliable and privacy-focused solution that utilizes peer-to-peer sharing. This means that your notes are synchronized directly between your devices, without any intermediary cloud services. Your data remains private, residing solely on your devices.

## How Syncthing Works

Syncthing is a continuous file synchronization tool that ensures your data is safe, secure, and easily accessible. It can sync files between devices on a local network, or between remote devices over the Internet. Data security and data safety are built into its design, as the files are shared through a local or remote network only. It's easy to setup and use, and it syncs whenever there are changes in the corresponding folder.

    
## Setting up syncthing

The latest versions of the software for almost all operating systems, inlcuding GNU/Linux, Windows, MacOS and Android are available [here](https://syncthing.net/downloads/). Most GNU/Linux distros have syncthing in their default repositories, so you can always install it directly from your terminal using apt, dnf or pacman. It is also available on [F-droid](https://f-droid.org/packages/com.nutomic.syncthingandroid/) and [play store](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid) for Android. There is no official app for iOS, but you can use [Möbius Sync](https://www.mobiussync.com/), an open source Syncthing client available in the iOS appstore.

![syncthing screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Syncthing_1.7.1_web_interface.png/640px-Syncthing_1.7.1_web_interface.png)
To get started, install Syncthing in any two devices, and make sure they are on the same network. Start the syncthing service on both your devices. On Android an iOS, this will be done whenever the app is started and running in the background. For Linux distros and MacOS, just click on start Syncthing in the applications menu, and for Windows, execute the syncthing.exe file. The admin GUI starts automatically and remains available on http://localhost:8384/ for PCs. The app itself will be the admin GUI for Android and iOS devices. Then click on Settings>Show ID on one device, and copy/scan the ID from the other device. A connection request will be sent to our first device, accept it and voila, the devices are setup for syncing. Make a new folder one of your devices, and add the folder in the syncthing GUI. Make sure you share the folder with the device that has been connected earlier. Accept the share request on the other device and you're set to go. The files in those folders will be synced in both the devices.

 
## Utilizing Joplin for Note-Taking

Joplin is a versatile, open-source note-taking and to-do application. It stores notes in Markdown format, enabling easy formatting and editing. It's available in desktop, mobile and even terminal applications, ensuring access across various devices. The notes are organized into notebooks, which are available in the overview. We can also assign tags to notes and notebooks, thus making it easier to access.
![Joplin-SS](https://joplinapp.org/images/home-top-img-2x.webp)

	


Once you have setup the syncthing folder, it's pretty easy to setup Joplin sync. Install [Joplin](https://joplinapp.org/download/) on both devices, and go to configurations/ options depending on you OS. Then select synchronisation, and set filesystem as synchronisation target. Set the directory to synchronise with (absolute path) to the folder you added earlier into syncthing and disable the failsafe option below. And voila, the changes in joplin in one device will be synchronised to the other devices too.



# Syncthing and Joplin: The FOSS Way to Sync Notes

In the world of Free and Open Source Software (FOSS), maintaining privacy and data ownership is crucial. Traditional note-taking apps often require compromising these principles to achieve synchronization across devices. However, with the combination of Syncthing and Joplin, FOSS enthusiasts can synchronize their notes seamlessly without relying on external cloud services. Let's explore how this powerful duo empowers users to keep their notes in sync while respecting their privacy.

Syncthing and Joplin provide a reliable and privacy-focused solution that utilizes peer-to-peer sharing. This means that your notes are synchronized directly between your devices, without any intermediary cloud services. Your data remains private, residing solely on your devices.

## How Syncthing Works

Syncthing is a continuous file synchronization tool that ensures your data is safe, secure, and easily accessible. It can sync files between devices on a local network, or between remote devices over the Internet. Data security and data safety are built into its design, as the files are shared through a local or remote network only. It's easy to setup and use, and it syncs whenever there are changes in the corresponding folder.


## Setting Up Syncthing

The latest versions of the software for almost all operating systems, inlcuding GNU/Linux, Windows, MacOS and Android are available [here](https://syncthing.net/downloads/). Most GNU/Linux distros have syncthing in their default repositories, so you can always install it directly from your terminal using apt, dnf or pacman. It is also available on [F-droid](https://f-droid.org/packages/com.nutomic.syncthingandroid/) and [play store](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid) for Android. There is no official app for iOS, but you can use [Möbius Sync](https://www.mobiussync.com/), an open source Syncthing client available in the iOS appstore.

![Syncthing Screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Syncthing_1.7.1_web_interface.png/640px-Syncthing_1.7.1_web_interface.png)

To begin, install Syncthing on two devices connected to the same network. Initiate the Syncthing service on both devices. For Android and iOS, this action is performed when the app starts and runs in the background. On Linux distributions and macOS, launch Syncthing via the applications menu, while for Windows, execute the `syncthing.exe` file. The admin GUI launches automatically and remains accessible at `http://localhost:8384/` for PCs, while the app itself serves as the admin GUI for Android and iOS. Next, navigate to Settings and select "Show ID" on one device, copying or scanning the ID from the other device. Upon sending a connection request to the first device, accept it to complete the device setup. Create a new folder on one device, adding it to the Syncthing GUI. Ensure you share this folder with the previously connected device and accept the share request on the latter. This concludes the setup, and the files within the designated folders will synchronize across both devices.

## Joplin for Note-Taking

Joplin emerges as a versatile, open-source note-taking and to-do application. Noteworthy features include storing notes in Markdown format, facilitating easy formatting and editing. Available across desktop, mobile, and terminal applications, Joplin ensures seamless access on various devices. Notes are organized into notebooks, while the provision to assign tags to notes and notebooks enhances accessibility.

![Joplin Screenshot](https://joplinapp.org/images/home-top-img-2x.webp)

## Synchronizing with Joplin

After establishing a Syncthing folder, configuring Joplin synchronization is pretty straightforward. Install [Joplin](https://joplinapp.org/download/) on both devices and navigate to configurations or options, depending on the operating system. Select "Synchronization" and designate the filesystem as the synchronization target. Specify the directory for synchronization (absolute path) as the folder earlier added to Syncthing, and disable the failsafe option below and Voila!. Any changes made within Joplin on one device will automatically synchronize with other connected devices once the the Synchronise button is pressed.


-------------------
 The combination of Syncthing and Joplin seamlessly integrates FOSS principles with the convenience of cross-device note synchronization. This will relieve FOSS enthusiasts the need to depend on services like Google keep notes or Notion, thus being able to maintain an all FOSS environment in their devices.

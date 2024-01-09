---
title: Linux Gaming
subtitle: Want to try linux, but worried about your games? Here's a guide to help you get started with gaming on linux.
date: 2023-12-31T04:05:14+05:30
tags: ["Gaming", "Flatpak", "Lutris"]
author: "AfthabEK"
bigimg: [{src: "/linuxgaming/steamdeck.jpg", desc: "Steam Deck", link: "https://www.steamdeck.com/en/"}, {src: "/linuxgaming/lutrisscreenshot.jpg", desc: "Lutris", link: "https://lutris.net/"}, {src: "/linuxgaming/protondb.jpg", desc: "ProtonDB", link: "https://www.protondb.com/"}, {src: "/linuxgaming/flathub.png", desc: "Flatpak", link: "https://flathub.org/home"}, {src: "/linuxgaming/genshinhome.jpg", desc: "Genshin Impact", link: "https://genshin.mihoyo.com/en/home"}, {src: "/linuxgaming/lutris.png", desc: "Lutris", link: "https://lutris.net/"}]
og_image: "/linuxgaming/protondb.jpg" 
---

The unavailability of gaming options on Linux has long been a significant deterrent for Windows users considering the switch. For years, this has remained a prevalent issue. A few months ago, even I considered committing blasphemy and reverting to Windows, as I was unable to play my favorite games. However, recent developments such as the introduction of the Steam Deck—Valve's latest gaming console based on Linux—and the emergence of Proton, a gaming environment, alongside major improvements in Wine, have effectively addressed this long-standing concern. After testing Genshin Impact, a popular AAA title, on my PC, I can confidently attest that my gaming experience on Linux has been on par, if not superior to my previous Windows gaming experience.

## The Steam Deck - Our Savior
![Steam Deck](/linuxgaming/steamdeck.jpg)

The Steam Deck, designed by Valve, is a pivotal milestone in Linux gaming. Its integration with Linux-based SteamOS and optimized gaming capabilities has significantly contributed to showcasing the potential of gaming on this platform. With Valve's backing and support, Linux gaming has gained substantial traction, prompting further developments and support from game developers. Proton, a compatibility layer developed by Valve, enables the use of Windows games on Linux. It's based on Wine, a compatibility layer that allows Windows applications to run on Linux. Proton's integration with Steam has made it incredibly easy to install and play Windows games on Linux. While Proton is still in its early stages, it has already proven to be a viable solution for gaming on Linux.

## Flatpak - A way out of dependency hell
![Flatpak](/linuxgaming/flathub.png)

Previously, configuring exact system requirements, drivers, and dependency versions for Wine and Proton posed a significant challenge. However, the advent of Flatpaks has simplified this process considerably.
Flatpaks offer a solution by enabling the use of official app versions directly from developers, utilizing the intended dependencies on any Linux distribution. Setting up Flatpak across various distributions like Debian, Arch, Fedora, Ubuntu, and Manjaro has become relatively straightforward, ensuring a consistent experience across different Linux platforms.

The alternative to Flatpak is Snap, which is a similar package manager. However, Snap is not as widely supported as Flatpak, and it's not officially supported on Debian-based distributions. As a result, I recommend using Flatpak for the best experience.

## ProtonDB - A database for compatibility
![protondb](/linuxgaming/protondb.jpg)

Due to the advent of steam deck, a lot of games are now being ported to Linux. You can check for the games directly supported on the GNU/Linux platform by searching on ProtonDB. ProtonDB is a community-driven database that provides information on the compatibility of Windows games with Linux. It also provides a rating for each game based on the user's experience. This information is incredibly useful for determining whether a game is compatible with Linux and the potential performance issues that may arise.

## Lutris
![Lutris](/linuxgaming/lutris.png)

While it's plausible to manually install all necessary software dependencies, using a gaming platform like Lutris significantly streamlines the process and minimizes hassle. To avoid potential dependency issues, I recommend installing Lutris via Flatpak.

![Lutris Screenshot](/linuxgaming/lutrisscreenshot.jpg)

After installing Lutris, accessing and installing games becomes very straightforward. Simply navigate to lutris.net, search for your desired game, choose an install script, and follow the provided instructions for installation.

I'll be using Genshin Impact as an example. Genshin Impact is a popular free-to-play action role-playing game developed by Hoyoverse. I know some of you might judge me for playing this game, but we can debate on that later. It's available on Windows, PlayStation, Android, and iOS. While it's not officially supported on Linux, it can be installed and played using Lutris as a flatpak.

To install Genshin Impact, Search Genshin impact on lutris.net, and select the latest install script. Then, click on the install button to install the game. After the installation is complete, you can launch the game from the Lutris library.


![Genshin Impact](/linuxgaming/genshinhome.jpg)

After playing Genshin Impact for a month without experiencing a single frame drop, I can confidently say that my gaming experience on Linux has been on par, if not superior to my previous Windows gaming experience. While I can't pinpoint the exact reason, it seems that WINE's emulation of Windows might actually outperform Windows itself!

You can also use other applications like Heroic Games Launcher, which is a native Linux client for the Epic Games Store. It's still in its early stages, but it's a promising alternative to Lutris. 

If you're a fan of retro games, you can also use RetroArch, which is a frontend for emulators, game engines, and media players. It's available on Flatpak.

I've also tried out playing witcher 3 on my setup, although not for that long, and I'm getting 60 FPS at ultra settings, without any frame drops. This is the same performance I was getting on Windows 11, so I'm pretty happy with that.

## Conclusion

With the exception of games that use Kernel-level anti-cheat software(Valorant smh), it's possible to run almost any game on Linux, without any notable performance issues. All in all, Linux gaming has undergone a remarkable transformation, thanks to advancements in compatibility layers, dedicated gaming platforms, and the active support of the community. With these recent advancements, GNU/Linux can now be seens as a viable and compelling choice for gamers seeking a reliable and efficient gaming experience.




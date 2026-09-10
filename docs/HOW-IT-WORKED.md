# How Methodus Worked

This document explains Methodus at a historical/architectural level based on original Methodus2000 pages and preserved version notes. It intentionally avoids operational instructions for abuse-oriented features.

## Overall design

Methodus Toolz and Methodus 3 were not single-purpose AOL add-ons. They were **multi-tool Windows applications** that grouped many separate utilities under one interface and menu system.

The original site states that Methodus was developed in **Visual Basic**, and later Methodus/Crapster material specifically identifies **Visual Basic 6**.

Methodus 3 organized functionality into menu families such as:

- Main
- Toolz
- Chat
- IMz
- Games
- Other
- AOL-specific submenus

The program could switch between AOL and AIM-oriented modes, and the Build 7 changelog confirms that mode switching was implemented directly in the application.

## Interface and skin system

Methodus had an unusually customizable UI for an AOL-era prog.

Original pages say users could modify:

- Window backgrounds
- Text colors
- Button colors
- Menu colors
- Startup/loading screens
- Window frames and appearance
- Skins across multiple tool windows

The skin system was important enough that the site distributed both **Easy Skin Maker** and **Advanced Skin Maker** utilities.

The Methodus 3 skins page also says Methodus Toolz 2 skins could work with Methodus 3, suggesting at least partial backwards compatibility in the skin format.

## AOL and AIM integration

Many Methodus utilities interacted with AOL or AIM windows rather than functioning as completely separate clients.

Historical examples include:

- IM faders
- Chat faders
- Mail faders
- IM Manager
- IM Answering Machine
- Chat Picture Scroller
- Room Buster
- Bots
- AOL wallpaper customization

The options system explicitly supported AOL 5, 6, and 7 and contemporary AIM versions.

## Crapster file sharing

Crapster was one of Methodus 3's largest components.

The original Methodus site describes it as a **decentralized file-sharing network**, conceptually similar to Napster but without a central server. It could search for arbitrary file types rather than only MP3s.

Documented capabilities included:

- Multiple simultaneous downloads
- Resume after disconnection
- System-tray operation
- User chat
- Network statistics
- Indirect connection counts
- Shared-file counts
- Upload/download handling

The official build history shows that Crapster was actively developed across multiple Methodus 3 builds:

- Build 2: upload optimizations
- Build 4: fixed shared-socket download bug
- Build 6: fixed false 100% completion reporting
- Build 7: fixed incoming-connection crash/blue-screen behavior and added chat filtering
- Build 8: default TTL changed to 6 and chat friend-marker behavior added

A surviving Methodus research page states that Crapster was created in **Visual Basic 6** and that its source code existed as part of a Gnutella research package.

## FTP tools

Methodus 3 included both FTP client and FTP server functionality.

The FTP Client was positioned as a simplified alternative to standalone FTP applications. Build 6 added progress bars for uploads and downloads, showing that transfer state was tracked directly in the UI.

## Web server

The original feature list says Methodus 3 could host a webpage from the user's computer.

Documented server capabilities included:

- Serving webpages
- Serving images
- Serving downloadable files
- Automatically monitoring visitors

This placed Methodus beyond a traditional AOL prog and into general networking/server utilities.

## Multimedia tools

Methodus 3 integrated several multimedia functions:

- CD Burner
- CD Ripper
- WAV-to-MP3 conversion / MP3 encoder
- Downloaded-media workflow tied conceptually to Crapster

The original site specifically described ripping CD audio to MP3 and burning downloaded music back to CDs.

## Macro and text tools

Methodus included a collection of AOL-scene text/ASCII utilities:

- Macro Editor
- Font-to-Macro Converter
- Chat Picture Scroller
- Color Faders for IM, Chat, Mail, and HTML

These tools supported the visual/text culture of AOL chat rooms, where ASCII art, colored text, macros, and scrolling text/images were common.

## IM management

The IM Manager grouped multiple IM conversations into a tab-like interface to reduce desktop clutter.

Methodus also had an IM Answering Machine that could automatically respond and record incoming messages.

## Hotkeys and launcher behavior

Methodus 3 could bind keyboard combinations to launch programs. The original feature page uses a combination like Shift+F4 as an example.

This made Methodus partly function as a desktop utility launcher in addition to its AOL/AIM functions.

## Games and ActiveX dependencies

Methodus contained multiple built-in games.

The official update history documents recurring ActiveX/component compatibility issues, including `ccrptmr` and the well-known Visual Basic-era "Active X Component Cannot Create" error. Build 8 says the game-related component creation issue was finally fixed.

This is useful technical evidence that Methodus relied on external COM/ActiveX components typical of VB6 software from the era.

## Browser utility

Methodus included a No-Pop-Ups Browser intended to suppress popup windows while browsing.

This was a separate utility inside the suite rather than a full independent browser product.

## Networking and developer utilities

Original material references:

- Port Scanner
- API Spy
- FTP Client
- FTP Server
- Web Server
- Crapster/Gnutella networking
- Screen Name Collector

The Build 2 changelog specifically documents a Port Scanner interval bug, confirming that this functionality was present in public Methodus 3 builds.

## Security-sensitive historical features

Methodus also included tools described by its original site as supporting behaviors such as spoofing, credential collection, keylogging, remote control, or disruptive AOL activity.

These are preserved in this archive as historical evidence only. This repository should document names, screenshots, menus, version history, and provenance, but should not provide step-by-step instructions for using such capabilities against other systems or users.

## Why Methodus was technically notable

Methodus combined several categories that were usually separate programs:

1. AOL/AIM automation
2. Chat customization
3. File sharing
4. FTP tools
5. Web serving
6. Multimedia conversion
7. Desktop launch/hotkey utilities
8. UI skinning
9. Games
10. Developer/network utilities

That broad scope explains the site's repeated description of Methodus as an "all-in-one" utility suite rather than merely an AOL prog.

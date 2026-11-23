# terminator-war-of-the-machines-terminator-future-shock
## Terminator War of the Machines - Terminator: Future Shock Remake
A total conversion mod for Terminator: War of the Machines that rebuilds the free-roam post-Judgment Day wasteland of Terminator: Future Shock (1995) with its SKYNET-infested open-world Los Angeles, drivable vehicles, and unscripted Terminator combat.

## Github Treeview
[https://treegit.macosxjs.com/?url=igiteam/terminator-war-of-the-machines-terminator-future-shock](https://treegit.macosxjs.com/?url=igiteam/terminator-war-of-the-machines-terminator-future-shock)

## Github Tree Api Direct JSON
[https://api.github.com/repos/igiteam/terminator-war-of-the-machines-terminator-future-shock/git/trees/main?recursive=1](https://api.github.com/repos/igiteam/terminator-war-of-the-machines-terminator-future-shock/git/trees/main?recursive=1)

## Base gameplay
[![Terminator - Future Shock: How it runs on a 1994 PC — Pentium 90 MHz / Mach64 / AWE32 / Roland SC-88](https://img.youtube.com/vi/9Pyu9pDM3g0/maxresdefault.jpg)](https://ytembed.macosxjs.com/?OVB5dTlwRE0zZzA)

[![Terminator 3: War of the Machines (2003) - PC Gameplay 4k 2160p / Win 10](https://img.youtube.com/vi/ifReXyQERTc/maxresdefault.jpg)](https://ytembed.macosxjs.com/?aWZSZVh5UUVSVGM)


## WS11WineCX20.0.4 (MacOSX Big Sur 32bit)
[WS11WineCX20.0.4.tar.7z](https://github.com/vitor251093/porting-kit-engines/releases/download/wineskin/WS11WineCX20.0.4.tar.7z)

[![wine windows games on macosx](https://raw.githubusercontent.com/igiteam/igi1-macbook-3d-workstation/refs/heads/main/wine-engine-config.png)](https://github.com/igiteam/wine_engines)

## Reference links
[https://archive.org/details/terminator-3-war-of-the-machines](https://archive.org/details/terminator-3-war-of-the-machines)

[https://archive.org/details/the-terminator-future-shock-mr-abandonware](https://archive.org/details/the-terminator-future-shock-mr-abandonware)

---

<p align="center">
  <img
    src="https://github.com/JacoboGutierrez/JacoboGutierrez/blob/main/t3-thumbnail-05.png?raw=true"
    alt="T3 Mod Tools Banner"
  />
</p>

# T3-ModTools

**Version 0.6.12**  
Experimental asset extraction, conversion, and mod management tool for **Terminator 3: War of the Machines (PC)**.
<br>
$\color{yellow}\textsf{Note: The first time you launch the game after patching the executable, it will crash and automatically restart.}$
$\color{yellow}\textsf{This is expected behavior and will only happen once, unless you install or modify a mod that patches the game's engine.}$

<br>
[Español](#español)

## What is T3-ModTools?

T3-ModTools is a Windows application designed to make the game's files easier to inspect and to provide a safer, organized way to install and combine mods.

The application has two main modes:

- **Asset Extraction** reads the game's ZIP-compatible COD archives and extracts selected content such as characters, vehicles, weapons, maps, menu models, effects, audio, and animations. It can also create working conversions of supported models, including OBJ/MTL files for static geometry and glTF 2.0 files for compatible rigged models.
- **Modding** manages independent mod projects, their enabled state, and their load order. It combines the files from enabled projects into `mods/Mods.Cod` and creates a separate `T3_Modded.exe` that loads the compiled package before the original game archives.

The original `T3.exe` is not modified. Each build recreates `T3_Modded.exe` from the original executable, allowing the unmodified game to remain available.

## Main capabilities

- Reads `Game.cod`, patch COD archives, installed game folders, and compatible backup archives.
- Extracts raw game assets by category.
- Converts supported SCA, LOD, and DET geometry to OBJ and MTL.
- Exports compatible rigged character, weapon, and vehicle models to glTF 2.0.
- Extracts native ANM animation files and produces animation metadata.
- Includes experimental Blender import and export plug-ins for supported T3 model and animation workflows.
- Creates and manages separate mod projects.
- Enables, disables, and reorders mods through a load-order system.
- Resolves duplicate asset paths according to load order when building the combined package.
- Compiles enabled project files into `mods/Mods.Cod`.
- Builds `T3_Modded.exe` without overwriting the original executable.
- Supports optional, conservative executable patch manifests and stops the build when incompatible patch writes conflict.

## Purpose and scope

T3-ModTools is intended for personal modding, preservation, and interoperability research using a legally owned copy of the game. It does not bypass DRM, encryption, online authentication, or anti-cheat systems.

This project is experimental. Some assets or workflows may require target-specific testing, and adding entirely new game content can require configuration or engine research beyond ordinary file replacement.

This README describes the role of the application only. For installation instructions and modding tutorials, see the included [T3 Modding Guide](https://github.com/JacoboGutierrez/T3-ModTools/blob/main/T3-ModTools/Documentation/T3-Modding-Guide.pdf).

The source code is distributed under the MIT License. This license applies to T3-ModTools itself, not to extracted game assets. Game assets remain the property of their respective rights holders.

---


## Dev Environment

**Official White Wii Remote With Nunchuk — Tested And Working — £14.99**
[https://www.ebay.co.uk/itm/800847189353](https://www.ebay.co.uk/itm/800847189353)

**Infrared Sensor Bar USB for Wii Emulator Remote Motion Detection Setup — £6.69**
[https://www.ebay.co.uk/itm/227423830875](https://www.ebay.co.uk/itm/227423830875)

**Apple MacBook Pro Retina 15in (2014) i7 2.8GHz 16GB 1TB SSD GT 750M — £120.30**
[https://www.ebay.co.uk/itm/800844561513](https://www.ebay.co.uk/itm/800844561513)

**WS11WineCX20.0.4 (Wine engine)**
[https://igiteam.github.io/wine_engines/](https://igiteam.github.io/wine_engines/)

**Official Genuine Sony PS3 PlayStation 3 DualShock 3 Wireless Controller Black — £19.99**
[https://www.ebay.co.uk/itm/840031043465](https://www.ebay.co.uk/itm/840031043465)

**Amazon Basics 4K HDMI Cable 3m — 18Gbps High Speed with Ethernet, 4K@60Hz, 2160p — £8.44**
[https://www.ebay.co.uk/itm/327352257557](https://www.ebay.co.uk/itm/327352257557)

**wiimote_nunchuk_macosx**
[https://github.com/igiteam/wiimote-nunchuk](https://github.com/igiteam/wiimote-nunchuk)

**xbox360_input_gui_py**
[https://github.com/igiteam/xbox360_input_gui_py](https://github.com/igiteam/xbox360_input_gui_py)

**logitec_mx_mouse_3_macos**
[https://github.com/igiteam/logitec_mx_mouse_3_macos](https://github.com/igiteam/logitec_mx_mouse_3_macos)

**igi1-macbook-3d-workstation**
[https://github.com/igiteam/igi1-macbook-3d-workstation](https://github.com/igiteam/igi1-macbook-3d-workstation)

---


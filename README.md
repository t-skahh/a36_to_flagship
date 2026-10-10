# A36 to Flagship

A module that ports Galaxy S25 (S931B) features to the Galaxy A36, hence the module name itself.

The files were grabbed from the S25's S931BXXSCCZH1 firmware.

> [!CAUTION]
> INSTALL THIS MODULE AT YOUR OWN RISK.
> 
> I am not responsible of your device getting bricked, it is you who installed it. I made the module and you make the decision of installing it.

## 📌 Features

<table>
  <tr>
    <th>Galaxy AI</th>
    <td>Call assist, Writing assist, Interpreter, Note assist, Transcript assist, Browsing assist, Photo assist, Creative studio, Weather wallpaper, Now brief, Health assist.</td>
  </tr>
  <tr>
    <th>Additional Features</th>
    <td>Live blur working, HighEnd Animations.</td>
  </tr>
</table>

## 🐞 Bugs

+ Photo assist ``Create`` makes the photo black or crashes Photo Editor, other features work fine.

## 📦 Installation

### Prerequisites
> [!WARNING]
> Before installing anything, you **must** disable "Umount modules by default" (``KernelSU`` > ``Settings`` > Disable `Umount modules by default`); otherwise the features **will not work**.

+ Device rooted with KernelSU.
+ [OverlayFS MetaModule](https://gr.dergoogler.com/gmr/modules/meta-overlayfs/1.3.1_13100.zip) or [Hybrid Mount](https://github.com/Hybrid-Mount/meta-hybrid_mount/releases/latest/download/) installed.

### Method 1: New Installation

1. Install the latest module from the [releases](https://github.com/rqpl/a36_to_flagship/releases).
2. Soft reboot.

### Method 2: Existing Installation

1. Uninstall existing module.
2. Hard reboot.
3. Root your device with whatever you're using.
4. Soft reboot.
5. Install the latest module from the [releases](https://github.com/rqpl/a36_to_flagship/releases).
6. Soft reboot again.

## 📑 Credits
Module made by Denver (@t-skahh).

Original [a56-to-flagship](https://github.com/ducthoe/A56-To-Flagship) by @ducthoe.

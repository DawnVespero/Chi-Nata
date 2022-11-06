# Chi-Nata
**A MacOS 9-styled icon set**

![Chi-Nata Logo](Chi-Nata%20Logo.png)
---

![CC BY-SA Banner](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

---



**Chi-Nata** ("[Chicago](https://en.wikipedia.org/wiki/Chicago_(typeface)) [Sonata](https://en.wikipedia.org/wiki/Mac_OS_9#Version_history)") is an icon set that tries to recreate the look of MacOS 9's desktop icons. The intention behind this is to enable users of modern systems to emulate the aesthetic of the Classic MacOS more completely by providing icons for newer programs that fit with this style.

While these may use some of the original MacOS ico's as a base (such as the file icon), **all icons in this repo must be original**. Please don't just recolor the base MacOS icons and push them here. With that being said, do feel free to look at the original icons for inspiration.

## Standards

### Design

To keep the look of the icons consistent, please make sure your additions meet these standards:

* .ico file type
* Create the icons in 32x32 pixel image size, but export them in 256x256
* Paletted to the [Standard VGA Palette](https://en.wikipedia.org/wiki/Video_Graphics_Array#/media/File:VGA_palette_with_black_borders.svg)

### Naming

To ensure that any icon can be easily searched for, use this naming scheme:

`[Author] . [Program Name] - [Variant]`

for example, for Steam, use

`Valve.Steam.ico`

if a base icon for a program already exists and you want to add a variant, suffix a variant name to its name with a dash. So for our example, you might use

`Valve.Steam-Dark.ico`

If you're in doubt about the author of a program, not sure which to use, or just want to quickly look it up, I would recommend using the IDs off the [winget-pkgs](https://github.com/microsoft/winget-pkgs) repo, after which this scheme is modeled.

## Instructions

### MacOS

The method listed below is the vanilla method provided by the OS. If you want to apply these custom icons to system apps, I would recommend [IconChamp](https://www.macenhance.com/iconchamp.html) or a similar application of your choice. For IconChamp users, an .ict file is provided in the root folder which will install the theme automatically when opened.

1. Open you application folder (Macintosh HD -> Applications)
2. Select the application whose icon you want to change and open its info panel (⌘I)
3. Open the .ico file you want to apply to the app in Preview
4. Select the desired icon size and copy it (⌘C)
5. In the app's info window, select the application icon in the upper left corner and paste the icon (⌘V)

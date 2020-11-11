> # 🎉 PANBTG
> Pixel Art NBT Generator.

---

<p align="left"> 
    <a href="https://github.com/TheArmagan/panbtg-releases/releases">
        <img alt="Download Link" src="https://img.shields.io/github/downloads/TheArmagan/panbtg-releases/total?color=%231ED760&label=CLICK%20TO%20DOWNLOAD&logo=github&logoColor=%23ffffff&style=for-the-badge">
    </a>
    <a href="https://discord.gg/fCqAh4kh77">
        <img alt="Join To Discord" src="https://img.shields.io/discord/775348842894983171?color=%237289DA&label=JOIN%20TO%20DISCORD&logo=discord&logoColor=%23ffffff&style=for-the-badge">
    </a>
</p>

---

```
|   ██████╗  █████╗ ███╗   ██╗██████╗ ████████╗ ██████╗
|   ██╔══██╗██╔══██╗████╗  ██║██╔══██╗╚══██╔══╝██╔════╝
|   ██████╔╝███████║██╔██╗ ██║██████╔╝   ██║   ██║  ███╗
|   ██╔═══╝ ██╔══██║██║╚██╗██║██╔══██╗   ██║   ██║   ██║
|   ██║     ██║  ██║██║ ╚████║██████╔╝   ██║   ╚██████╔╝
|   ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═══╝╚═════╝    ╚═╝    ╚═════╝

|   Pixel Art NBT Generator. v1.1.1 By Kıraç Armağan Önal (Armagan#2496)

Example Usages:
    / Normal conversion without dithering. (Generally looks bad except pixel arts!)
    $ PANBTG.exe -i myImage.jpg

    / Draw half sized image
    $ PANBTG.exe -i myImage.jpg -s 0.5

    / Conversion with dithering amount 5.
    $ PANBTG.exe -i myImage.jpg -d 5

    / Normal conversion but vertical image result.
    $ PANBTG.exe -i myImage.jpg --vertical

    / Dithering and vertical at same time.
    $ PANBTG.exe -i myImage.jpg --vertical -d 5

Argument List:
    -V, --version:
    \> output the version number

    -d, --dither <1-10>: (Default: 0)
    \> Set the dithering factor. (Original: 5)

    -sb, --scaffold-block <block-name>: (Default: "stone")
    \> Scaffold block type for the powder type blocks.. (Use '-' for spaces.)

    -ff, --full-scaffold: (Default: false)
    \> Enables scaffold for every block.

    -i, --input <path>:
    \> Input image file. (jpg)

    --vertical: (Default: false)
    \> Draw the art vertically. (kinda-buggy)

    -s, --scale <factor>: (Default: 1)
    \> Rescale the image based on factor. (Original: 1)

    -e, --effects <effects>:
    \> Add effects to source image. (Separated using comma ",") (Available Effects: grayscale,deepfry)

    --help:
    \> Show the help panel.

Download:
    https://github.com/TheArmagan/panbtg-releases
```


---

> Created by Kıraç Armağan Önal


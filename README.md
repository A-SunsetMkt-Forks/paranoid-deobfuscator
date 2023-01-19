# [Paranoid] deobfuscator

A script to deobfuscate apps obfuscated with [Paranoid]
to help you with static analysis.

Before | After
:-:|:-:
![Before](.assets/before.png) | ![After](.assets/after.png)

## Requirements
* [Apktool]
* Python 3
  * `numpy` package (install it via `pip install numpy` or `pip install -r requirements.txt`)

## Usage
1. Decode app with [Apktool]: `apktool d app.apk`
2. Run deobfuscator: `python deobfuscator.py app` or `./deobfuscator.py app`
3. Build app with [Apktool]: `apktool b app`
4. Enjoy your deobfuscated apk!

[paranoid]: https://github.com/MichaelRocks/paranoid
[apktool]: https://github.com/iBotPeaches/Apktool
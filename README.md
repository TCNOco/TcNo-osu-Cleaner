
<p align="center">
  <a href="https://tcno.co/">
    <img src="/img/banner.png"></a>
</p>
<p align="center">
  <img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/TcNobo/osu-cleaner/total?logo=GitHub&style=flat-square">
  <a href="https://tcno.co/">
    <img alt="Website" src="/img/web.svg" height=20"></a>
  <a href="https://s.tcno.co/AccSwitcherDiscord">
    <img alt="Discord server" src="https://img.shields.io/discord/217649733915770880?label=Discord&logo=discord&style=flat-square"></a>
  <a href="https://twitter.com/TcNobo">
    <img alt="Twitter" src="https://img.shields.io/twitter/follow/TcNobo?label=Follow%20%40TcNobo&logo=Twitter&style=flat-square"></a>
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/TcNobo/osu-cleaner?logo=GitHub&style=flat-square">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/TcNobo/osu-cleaner?logo=GitHub&style=flat-square">
</p>
                                                                                                                                  
<p align="center"><a target="_blank" href="https://github.com/TcNobo/osu-cleaner/releases/latest">
  <img alt="Download button" src="/img/btnDownload.png" height=70"></a></p>


Small tool, written in C#, to clean unused elements from beatmaps.
Originally created by [henntix](https://github.com/henntix/osu-cleaner), but completely reskinned, revamped, branded and updated by [TechNobo](https://tcno.co)

Lots of changes and improvements since the original 1.0 henntix release. Enjoy the revamped software!

If you are using a SSD, you will be happy! Deleting those elements will save your disk space even by few gigabytes. You can choose what to delete: videos, storyboards, beatmap skins, backgrounds and hitsounds. You can also choose to move those files instead of permanent purge.

### How does it work?
After either guessing or being told your osu! directory, it will take the options you give it and search for relative files. This lets you pull unused images and sounds out of song packs, as well as other "pointless" files, that you may choose not to use or already ignore because you have a custom skin/sounds active. You'd be surprised how much junk is just lying around in your folder!

## Required runtimes (Download and install):
**- Requires Microsoft .NET Framework 4.5.2 Runtime:** [Web Installer](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net452-web-installer), [Offline Installer](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net452-offline-installer), [Other languages](https://dotnet.microsoft.com/download/dotnet-framework/net452)

**Running the program:**
After downloading your .zip from the [GitHub Releases](https://github.com/TcNobo/TcNo-osu-Cleaner/releases) page, extract everything to a folder of your choice and run `TcNo-osu-Cleaner.exe`

### Screenshots:
<p>
  <img alt="Main window - Mid-scan" src="/img/screenshot1.png">
  <img alt="main window - Selected files to purge" src="/img/screenshot2.png">
</p>

## License: The MIT License (MIT)
Copyright for portions of [TcNo-osu-Cleaner](https://github.com/TcNobo/TcNo-osu-Cleaner) are held by [henntix](https://github.com/henntix/), 2016 as part of [osu-cleaner](https://github.com/henntix/osu-cleaner). All other copyright for [TcNo-osu-Cleaner](https://github.com/TcNobo/TcNo-osu-Cleaner) are held by [Wesley Pyburn (TechNobo)](https://github.com/TcNobo/)

> Contributors are appreciated. If you want to contribute and add something, fork it and send me a pull request.

> If you find issues or bugs, report them via Issues page. Please also report if something has been not deleted but it should be.

## Changelog
* v2.0 (26.01.2021) Completely reskinned, updated & improved by [TechNobo](https://tcno.co).
* v1.0 (06.11.2018) Initial release, written in 2016

---

## Known Issues
* (Since 1.0) Some storyboard elements are not deleted due to not being used on actual storyboard. This cannot be easily fixed due to storyboard elements finding approach. This issue could be fixed by implementing *"unused elements cleaner"* which will delete all files except \*osu, audio files and whitelisted elements mentioned above, selected by user
* (Since 1.0) \*.osb files are not deleted. 

#### Disclaimer
All trademarks and materials are property of their respective owners and their licensors.<br>
This project is not affiliated with "osu!" or "ppy" or "Peppy".<br>
I am not responsible for the contents of external links.<br>
USE THIS SOFTWARE AT YOUR OWN RISK. I AM NOT RESPONSIBLE FOR ANY DAMAGES IF YOU CHOOSE TO USE THIS SOFTWARE. COMPONENTS ARE PROVIDED ON AN "AS IS" AND "AS AVAILABLE" BASIS, WITHOUT ANY WARRANTIES OF ANY KIND TO THE FULLEST EXTENT PERMITTED BY LAW, AND I EXPRESSLY DISCLAIM ANY AND ALL WARRANTIES, WHETHER EXPRESS OR IMPLIED.
<p align="center"><img src="src/gui/resources/images/readme-icon.png" alt="" /></p>

<h1 align="center">Grabber</h1>

[![Discord chat](https://img.shields.io/discord/780466420877361156?logo=discord&logoColor=white)](https://discord.gg/pWnY5eW3rz)
[![GitHub release](https://img.shields.io/github/release/Bionus/imgbrd-grabber.svg)](https://github.com/Bionus/imgbrd-grabber/releases/latest)
[![GitHub downloads](https://img.shields.io/github/downloads/Bionus/imgbrd-grabber/latest/total.svg)](https://github.com/Bionus/imgbrd-grabber/releases/latest)
[![GitHub downloads](https://img.shields.io/github/downloads/Bionus/imgbrd-grabber/total.svg)](https://github.com/Bionus/imgbrd-grabber/releases)
[![GitHub issues](https://img.shields.io/github/issues/Bionus/imgbrd-grabber.svg)](https://github.com/Bionus/imgbrd-grabber/issues)
[![Donate with PayPal](https://img.shields.io/badge/paypal-donate-orange.svg)](https://www.paypal.me/jvasti)
[![Donate with Patreon](https://img.shields.io/badge/patreon-donate-orange.svg)](https://www.patreon.com/bionus)
[![Build Status](https://img.shields.io/github/actions/workflow/status/Bionus/imgbrd-grabber/build.yml)](https://github.com/Bionus/imgbrd-grabber/actions)
[![Code Coverage](https://img.shields.io/codecov/c/github/Bionus/imgbrd-grabber.svg)](https://codecov.io/gh/Bionus/imgbrd-grabber)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/3ab9cd9af181458fad287a2663129d98)](https://app.codacy.com/gh/Bionus/imgbrd-grabber/dashboard)
[![Project license](https://img.shields.io/github/license/bionus/imgbrd-grabber.svg)](https://raw.githubusercontent.com/Bionus/imgbrd-grabber/develop/LICENSE)

Imageboard/booru downloader which can download thousands of images from multiple boorus very easily.

Thanks to its powerful naming features, you just have to set your filename and save directory using all the tokens available, and the program will generate a filename using the image's information. With this, you can store and manage your pictures in advanced directory structures, and save image with custom filenames!

Grabber works on Windows, Mac, and Linux. It is available in English, French, Russian, simplified Chinese, and Spanish.

## Download
You can download the latest release [here](https://github.com/Bionus/imgbrd-grabber/releases/latest), or find all previous releases [here](https://github.com/Bionus/imgbrd-grabber/releases).

For users interested, a nightly version is built automatically on every commit on the `develop` branch, and can be downloaded [here](https://github.com/Bionus/imgbrd-grabber/releases/nightly). Note that it might be less stable than official releases, so use at your own risk.

* [Install steps for Windows](https://www.bionus.org/imgbrd-grabber/docs/install/windows.html)
* [Install steps for Linux](https://www.bionus.org/imgbrd-grabber/docs/install/linux.html)
* [Install steps for macOS](https://www.bionus.org/imgbrd-grabber/docs/install/macos.html)
* [Install steps for Android](https://www.bionus.org/imgbrd-grabber/docs/install/android.html)

## Features

### Browse

[<img src="https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/search-basic-thumb.png" align="right" />](https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/search-basic.png)

* Tabs to make multiple searches at the same time
* Able to show results from multiple imageboards at the same time in a single tab
* Remove duplicate results from multiple-imageboard searches
* Auto-completion of tags in the search field
* Blacklisting of tags to mark or hide images you don't want to see
* Proxy support
* Post-filtering (when the imageboard search is limited)
* Auto-download images as you search according to a whitelist

### Download

[<img src="https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/download-thumb.png" align="right" />](https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/download.png)

* Download thousands of images at once
* Download single images using their MD5 or ID
* Command line interface to download images

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

### Customize

[<img src="https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/sources-thumb.png" align="right" />](https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/sources.png)

* Add your own imageboards very easily
* Authentication for sources behind a login wall
* Theme support using CSS. See [Themes](https://www.bionus.org/imgbrd-grabber/docs/plugins/theme.html) for details.
* Lots of options to customize the program's behaviour

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

### Organize

[<img src="https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/filename-thumb.png" align="right" />](https://www.bionus.org/imgbrd-grabber/assets/img/screenshots/filename.png)

* Save images using a custom format, for example `%artist%/%copyright%/%character%/%md5%.%ext%`, or using JavaScript code. See [Filename](https://www.bionus.org/imgbrd-grabber/docs/filename.html) for details.
* Favorite tags to keep track of new images
* "View it later" tags to save a search for later
* Support saving images directly to a local booru, such as [Szurubooru](https://www.bionus.org/imgbrd-grabber/docs/commands/szurubooru.html), [MyImouto](https://www.bionus.org/imgbrd-grabber/docs/commands/my-imouto.html), [Gelbooru](https://www.bionus.org/imgbrd-grabber/docs/commands/gelbooru.html), or [Shimmie](https://www.bionus.org/imgbrd-grabber/docs/commands/shimmie.html).
* Can add entries to a database for each image or tag while downloading. See [Commands](https://www.bionus.org/imgbrd-grabber/docs/commands/) for details.
* Conditional filenames triggered by a tag
* Rename already downloaded images

## Default sources
You can add additional sources very easily, but here's a short list of some sources that are included and supported by default:
* Danbooru
* Gelbooru
* E-Hentai
* Pixiv
* yande.re
* Shimmie
* e621
* Konachan
* rule34
* safebooru
* Anime-Pictures
* behoimi
* Zerochan
* Twitter

## Compilation
See the [Compilation](https://bionus.github.io/imgbrd-grabber/docs/compilation.html) documentation to know how to build Grabber.

* Linux: run `./build.sh` at the root of the repository
* macOS: run `./build-mac.sh` at the root of the repository

## Contributors
<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Bionus"><img src="https://avatars2.githubusercontent.com/u/882719?s=122?s=122" width="122px;" alt="Jack Vasti"/><br /><sub><b>Jack Vasti</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/commits?author=Bionus" title="Code">💻</a> <a href="https://github.com/Bionus/imgbrd-grabber/commits?author=Bionus" title="Documentation">📖</a> <a href="https://github.com/Bionus/imgbrd-grabber/commits?author=Bionus" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Zzzyyzzyxx"><img src="https://avatars0.githubusercontent.com/u/16903308?s=122?s=122" width="122px;" alt="YMI"/><br /><sub><b>YMI</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3AYMI" title="Bug reports">🐛</a> <a href="#ideas-YMI" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/SultrySamthepennanceman"><img src="https://avatars2.githubusercontent.com/u/12085184?s=122?s=122" width="122px;" alt="SultrySamthepenna&hellip;"/><br /><sub><b>SultrySamthepenna&hellip;</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3ASultrySamthepennanceman" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/BarryMode"><img src="https://avatars1.githubusercontent.com/u/5648875?s=122?s=122" width="122px;" alt="BarryMode"/><br /><sub><b>BarryMode</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/commits?author=BarryMode" title="Code">💻</a> <a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3ABarryMode" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Flat"><img src="https://avatars3.githubusercontent.com/u/2048861?s=122?s=122" width="122px;" alt="Ken Swenson"/><br /><sub><b>Ken Swenson</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/commits?author=Flat" title="Code">💻</a> <a href="#platform-Flat" title="Packaging/porting to new platform">📦</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/larry-he"><img src="https://avatars0.githubusercontent.com/u/18506295?s=122?s=122" width="122px;" alt="Larry He"/><br /><sub><b>Larry He</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/commits?author=larry-he" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/brodycas3"><img src="https://avatars3.githubusercontent.com/u/19770864?s=122?s=122" width="122px;" alt="brodycas3"/><br /><sub><b>brodycas3</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3Abrodycas3" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/sanddudu"><img src="https://avatars1.githubusercontent.com/u/1650692?s=122?s=122" width="122px;" alt="Klion Xu"/><br /><sub><b>Klion Xu</b></sub></a><br /><a href="#translation-sanddudu" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/MasterPetrik"><img src="https://avatars2.githubusercontent.com/u/22294259?s=122?s=122" width="122px;" alt="MasterPetrik"/><br /><sub><b>MasterPetrik</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3AMasterPetrik" title="Bug reports">🐛</a> <a href="#translation-MasterPetrik" title="Translation">🌍</a> <a href="#ideas-MasterPetrik" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/dyskette"><img src="https://avatars3.githubusercontent.com/u/6687927?s=122?s=122" width="122px;" alt="Eddy Castillo"/><br /><sub><b>Eddy Castillo</b></sub></a><br /><a href="#translation-dyskette" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/MrAndre96"><img src="https://avatars0.githubusercontent.com/u/6564956?s=122?s=122" width="122px;" alt="MrAndre96"/><br /><sub><b>MrAndre96</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3AMrAndre96" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/brazenvoid"><img src="https://avatars1.githubusercontent.com/u/8722533?s=122?s=122" width="122px;" alt="Umair Ahmed"/><br /><sub><b>Umair Ahmed</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3Abrazenvoid" title="Bug reports">🐛</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/ccppoo"><img src="https://avatars0.githubusercontent.com/u/46418312?s=122?s=122" width="122px;" alt="ccppoo"/><br /><sub><b>ccppoo</b></sub></a><br /><a href="#translation-ccppoo" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/yami-no-tusbas"><img src="https://avatars2.githubusercontent.com/u/3921598?v=4?s=122" width="122px;" alt="YamiNoSho"/><br /><sub><b>YamiNoSho</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3Ayami-no-tusbas" title="Bug reports">🐛</a> <a href="#question-yami-no-tusbas" title="Answering Questions">💬</a> <a href="#ideas-yami-no-tusbas" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/waitingmoon"><img src="https://avatars.githubusercontent.com/u/16256443?v=4?s=122" width="122px;" alt="waitingmoon"/><br /><sub><b>waitingmoon</b></sub></a><br /><a href="#translation-waitingmoon" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Penguin-Guru"><img src="https://avatars.githubusercontent.com/u/22182988?v=4?s=122" width="122px;" alt="Penguin-Guru"/><br /><sub><b>Penguin-Guru</b></sub></a><br /><a href="https://github.com/Bionus/imgbrd-grabber/commits?author=Penguin-Guru" title="Code">💻</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/lucas-04"><img src="https://avatars.githubusercontent.com/u/95548091?v=4?s=122" width="122px;" alt="lucas"/><br /><sub><b>lucas</b></sub></a><br /><a href="#translation-lucas-04" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/adem4ik"><img src="https://avatars.githubusercontent.com/u/4707112?v=4?s=122" width="122px;" alt="Andrei Stepanov"/><br /><sub><b>Andrei Stepanov</b></sub></a><br /><a href="#translation-adem4ik" title="Translation">🌍</a> <a href="https://github.com/Bionus/imgbrd-grabber/issues?q=author%3Aadem4ik" title="Bug reports">🐛</a> <a href="#ideas-adem4ik" title="Ideas, Planning, & Feedback">🤔</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="16.66%"><a href="https://crowdin.com/profile/noptiwhite"><img src="https://crowdin-static.downloads.crowdin.com/avatar/15784087/large/fb71788d44585300e7a35e5172bf23e6.jpg?s=122" width="122px;" alt="Noptiwhite"/><br /><sub><b>Noptiwhite</b></sub></a><br /><a href="#translation-Noptiwhite" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Tunguso4ka"><img src="https://avatars.githubusercontent.com/u/71643624?v=4?s=122" width="122px;" alt="Tunguso4ka"/><br /><sub><b>Tunguso4ka</b></sub></a><br /><a href="#translation-Tunguso4ka" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://crowdin.com/profile/gorgusm"><img src="https://crowdin-static.downloads.crowdin.com/avatar/13720583/large/8099e5675724971e1519f4ea6f305d41_default.png?s=122" width="122px;" alt="Gorgusm"/><br /><sub><b>Gorgusm</b></sub></a><br /><a href="#translation-Gorgusm" title="Translation">🌍</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification.
Contributions of any kind are welcome!

<div align="left">

[简体中文](https://github.com/koodo-reader/koodo-reader/blob/master/README_cn.md) | [Português](https://github.com/koodo-reader/koodo-reader/blob/master/README_pt.md) | English

</div>

<div align="center" >
  <img src="https://i.loli.net/2021/07/30/ZKNMmz54Q3uqlrW.png" width="96px" height="96px"/>
</div>

<h1 align="center">
  Koodo Reader
</h1>

<h3 align="center">
  A cross-platform ebook reader
</h3>
<div align="center">

[Download](https://koodo.960960.xyz/en) | [Preview](https://reader.960960.xyz) | [Roadmap](https://troyeguo.notion.site/d1c19a132932465bae1d89dd963c92ea?v=ca8aa69cf25849c18c92b92ba868663b) | [Document](https://troyeguo.notion.site/Koodo-Reader-Document-9c767af3d66c459db996bdd08a34c34b)

</div>

## Preview

<div align="center">
  <img src="https://i.loli.net/2021/08/08/I37WPYFJcC1jltn.png" >
  <img src="https://i.loli.net/2021/08/08/G7WvUQFTrEpSCKg.png" >
</div>

## Feature

- Format support:
  - EPUB (**.epub**)
  - Scanned document (**.pdf**, **.djvu**)
  - DRM-free Mobipocket (**.mobi**) and Kindle (**.azw3**, **.azw**)
  - Plain text (**.txt**)
  - FictionBook (**.fb2**)
  - Comic book archive (**.cbr**, **.cbz**, **.cbt**, **.cb7**)
  - Rich text (**.md**, **.docx**)
  - Hyper Text (**.html**, **.xml**, **.xhtml**, **.mhtml**, **.htm**, **.htm**)
- Platform support: **Windows**, **macOS**, **Linux** and **Web**
- Save your data to **OneDrive**, **Google Drive**, **Dropbox**, **FTP**, **SFTP**, **WebDAV**
- Customize the source folder and synchronize among multiple devices using OneDrive, iCloud, Dropbox, etc.
- Single-column, two-column, or continuous scrolling layouts
- Text-to-speech, translation, dictionary, touch screen support, batch import
- Add bookmarks, notes, highlights to your books
- Adjust font size, font family, line-spacing, paragraph spacing, background color, text color, margins, and brightness
- Night mode and theme color
- Text highlight, underline, boldness, italics and shadow

## Installation

- Desktop Version:
  - Stable Version (Recommended): [Download](https://koodo.960960.xyz/en)
  - Developer Version: [Download](https://github.com/koodo-reader/koodo-reader/releases/latest) ( With new feature and bug fix, but may induce some unknown bugs)
- Web Version：[Preview](https://reader.960960.xyz)
- Install with Scoop:

```shell
scoop bucket add extras
scoop install extras/koodo-reader
```

- Install with Winget:

```shell
winget install -e AppbyTroye.KoodoReader
```

- Install with Homebrew:

```shell
brew install --cask koodo-reader
```

- Install with Docker:

```bash
docker-compose up -d
```

- Install with Flathub:

```shell
flatpak install flathub io.github.troyeguo.koodo-reader
flatpak run io.github.troyeguo.koodo-reader
```

<a href="https://flathub.org/apps/details/io.github.troyeguo.koodo-reader"><img height="50" alt="Download on Flathub" src="https://flathub.org/assets/badges/flathub-badge-en.png"/></a>

## Screenshot

<div align="center">
  <b>List mode</b>
  <img src="https://i.loli.net/2021/08/08/JyNHfThMs184Um2.png" >
  <b>Cover mode</b>
  <img src="https://i.loli.net/2021/08/08/76zkDEAobd4qsmR.png" >
  <b>Reader menu</b>
  <img src="https://i.loli.net/2021/08/08/LeEN9gnOvFmfVWA.png" >
  <b>Backup and restore</b>
  <img src="https://i.loli.net/2021/08/08/aRIAiYT2dGJQhC1.png" >
  <b>Dark mode and theme color</b>
  <img src="https://i.loli.net/2021/08/08/ynqUNpX93xZefdw.png" >
  <b>Note management</b>
  <img src="https://i.loli.net/2021/08/09/sARQBoefvGklHwC.png" >

</div>

</div>

## Develop

Make sure that you have installed yarn and git

1. Download the repo

   ```
   git clone https://github.com/koodo-reader/koodo-reader.git
   ```

2. Enter desktop mode

   ```
   yarn
   yarn dev
   ```

3. Enter web mode

   ```
   yarn
   yarn start
   ```

## Translation

You can submit pull requests to edit current translation or add new language

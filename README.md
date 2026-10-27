<p align="center">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-logo.svg" width="88" height="88" alt="">
</p>

<h1 align="center">Pomelo</h1>

<p align="center">Convert, compress and edit files mid-drag in File Explorer.</p>

<p align="center">
  <a href="https://apps.microsoft.com/detail/9P81WJ5W014Q?referrer=appbadge&mode=full">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-preview.pomelo-app.pages.dev/store/get-it-from-microsoft-light.svg">
      <img src="https://github-preview.pomelo-app.pages.dev/store/get-it-from-microsoft-dark.svg" width="161" height="44" alt="Get it from Microsoft">
    </picture>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/language-C%23-239120" alt="language: C#">
  <img src="https://img.shields.io/badge/.NET-10-512BD4" alt=".NET: 10">
  <img src="https://img.shields.io/badge/UI-WinUI%203-0078D4" alt="UI: WinUI 3">
  <img src="https://img.shields.io/badge/media-Media%20Foundation-005A9E" alt="media: Media Foundation">
  <img src="https://img.shields.io/badge/platform-Windows%2011%20x64-00A4EF" alt="platform: Windows 11 x64">
  <a href="CHANGELOG.md"><img src="https://img.shields.io/badge/version-1.2.0-44C800" alt="version: 1.2.0"></a>
  <a href="#what-it-does"><img src="https://img.shields.io/badge/conversions-220-F39C12" alt="conversions: 220"></a>
  <a href="#what-it-does"><img src="https://img.shields.io/badge/tools-31-E74C3C" alt="tools: 31"></a>
  <a href="#what-it-does"><img src="https://img.shields.io/badge/formats-36-16A085" alt="formats: 36"></a>
  <a href="#what-it-does"><img src="https://img.shields.io/badge/file%20actions-8-8E44AD" alt="file actions: 8"></a>

  <a href="https://pomeloapp.net/privacy/"><img src="https://img.shields.io/badge/tracking-none-2C3E50" alt="tracking: none"></a>
  <img src="https://img.shields.io/badge/license-proprietary-555555" alt="license: proprietary">
</p>

<p align="center">
  <a href="https://pomeloapp.net/">Website</a> ·
  <a href="https://pomeloapp.net/features/">Every window</a> ·
  <a href="https://pomeloapp.net/help/">Help</a> ·
  <a href="https://pomeloapp.net/feedback/">Report a problem</a> ·
  <a href="https://pomeloapp.net/press/">Press kit</a>
</p>

<p align="center">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-trailer.webp" width="800" alt="The Pomelo trailer: drag, tap a key, drop, then the windows of the tools for images, video, audio and PDF">
</p>

<p align="center"><a href="https://pomeloapp.net/press/pomelo-trailer.mp4">Watch the trailer with sound</a> (40 seconds, MP4)</p>

Pomelo adds a wheel of file operations to the drag you already make in File Explorer. Hold the mouse button on some files, tap Shift, Ctrl or Alt, and the wheel opens under the pointer. Drop the files on a wedge. The results are saved as new files next to the originals, and nothing leaves your PC.

The wheel knows 220 conversions between 36 formats, 31 tools and 8 file actions, for images, PDFs, audio, video, documents, slides and spreadsheets.

## Built like a part of Windows

Pomelo is made with the same parts as the apps that come with Windows 11, so it looks and behaves like one of them.

- The interface is WinUI 3, the framework of the Windows 11 apps: Mica windows, Segoe Fluent Icons, the system font, and your light, dark or high contrast theme.
- Audio and video go through Media Foundation, the media engine of Windows, with the codecs of Windows and, where your PC has one, the hardware encoder of its graphics chip.
- HEIC photos are read and written by the Windows Imaging Component, with Microsoft's HEIF and HEVC extensions.
- PDF pages become pictures through the PDF renderer built into Windows, and Copy text reads images with the text recognition built into Windows.
- Share opens the Windows share sheet. Copy to and Move to hand the files to Windows, which copies them with its own progress and undo.

Where Windows has no engine of its own, Pomelo ships open-source ones: libvips for the other image formats, qpdf and PDFsharp for PDFs, the Xiph libraries and libvpx for OGG, Opus and WebM, and TagLib# for audio tags. Word, PowerPoint and Excel files are read with Syncfusion's libraries, so Office is not needed.

Pomelo is an independent app by Andrea Loroni. It is not made, sponsored or endorsed by Microsoft.

## How it works

1. Start dragging files in File Explorer or on the desktop, up to 200 at a time.
2. While you hold the button, tap a key. Shift opens Convert, Ctrl opens Tools and Alt opens Actions.
3. Drop the files on a wedge. A small card says when the job is done.

A wedge whose name ends in an ellipsis, like Crop…, opens a small window first, so you choose before anything is saved. Pomelo never overwrites a file: when the original folder can't be written to, the results go to a fallback folder.

## Screenshots

<p align="center">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-screenshot-01.jpg" width="49%" alt="Convert files mid-drag: tap Shift while you drag and drop on a wedge">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-screenshot-02.jpg" width="49%" alt="Compress, crop, edit: Ctrl opens Tools">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-screenshot-03.jpg" width="49%" alt="Actions are always free: Alt opens Actions">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-screenshot-04.jpg" width="49%" alt="Results land next to the originals">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-screenshot-05.jpg" width="49%" alt="Light or dark, like Windows">
  <img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-screenshot-06.jpg" width="49%" alt="Your keys, your way: Settings">
</p>

## The tool windows

Some wedges open a window before they save. Each one keeps the original and saves a copy next to it. [See all of them on the website](https://pomeloapp.net/features/).

<table>
  <tr>
    <td width="50%"><img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-window-image-crop.png" alt="The Crop window"><br>Crop… a photo to a ratio or to the pixel.</td>
    <td width="50%"><img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-window-image-edit.png" alt="The Edit window"><br>Edit… light and colour with eight sliders and a live preview.</td>
  </tr>
  <tr>
    <td><img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-window-image-annotate.png" alt="The Annotate window"><br>Annotate… with arrows, boxes, circles, pen and text.</td>
    <td><img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-window-video-trim.png" alt="The Trim window for a video"><br>Trim… a video to a hundredth of a second.</td>
  </tr>
  <tr>
    <td><img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-window-audio-normalize.png" alt="The Normalize window"><br>Normalize… the loudness of a recording to a target in LUFS.</td>
    <td><img src="https://github-preview.pomelo-app.pages.dev/press/pomelo-window-pdf-organize.png" alt="The Organize window for a PDF"><br>Organize… the pages of a PDF: reorder, rotate, duplicate or delete.</td>
  </tr>
</table>

## What it does

| Files | Reads | Converts to | Tools |
|---|---|---|---|
| Images | JPG, PNG, WEBP, HEIC, AVIF, TIFF, BMP, GIF | JPG, PNG, WEBP, AVIF, HEIC, TIFF, BMP, PDF | 10 |
| PDF | PDF | PNG, JPG | 6 |
| Audio | MP3, M4A, AAC, WAV, FLAC, WMA, OGG, OPUS, AIFF | MP3, M4A, WAV, FLAC, OGG, OPUS, AIFF, WMA | 7 |
| Video | MP4, M4V, MOV, WMV, AVI, MKV, WEBM | MP4, WEBM, GIF, MP3, M4A | 8 |
| Documents | DOCX, DOC, RTF, TXT, MD, HTML | PDF, DOCX, TXT, MD, HTML, EPUB, PNG, JPG | none |
| Slides | PPTX | PDF, PNG, JPG | none |
| Spreadsheets | XLSX, XLS, CSV, TSV | PDF, XLSX, CSV, TSV, ODS | none |

### Images

| Tab | Wedge | What it does |
|---|---|---|
| Convert | JPG | For photos you send or post. Transparent areas turn white. |
| Convert | PNG | Lossless, keeps transparency. |
| Convert | WEBP | Smaller than JPG at the same look. |
| Convert | AVIF | Smaller still, for the web. |
| Convert | HEIC | The iPhone photo format. Needs the HEIF and HEVC extensions from the Microsoft Store. |
| Convert | TIFF | Lossless, for print and archives. |
| Convert | BMP | Uncompressed, for software that asks for it. |
| Convert | PDF | One PDF per image, at the image's own size, or on A4 or Letter pages from Settings. |
| Tools | Compress… | Opens a window to pick a target size or a percentage. Saves smaller JPG or WEBP copies. |
| Tools | Crop… | Opens a window to drag a frame over the photo or pick a ratio. Saves a cropped copy in the same format. |
| Tools | Edit… | Opens a window with eight sliders for exposure, brightness, contrast, highlights, shadows, temperature, tint and saturation, and a live preview. Saves an edited copy. |
| Tools | Annotate… | Opens a window to draw arrows, boxes, circles, pen and highlighter strokes and text on a photo. Saves an annotated copy. |
| Tools | Rotate 90° | A quarter turn clockwise. |
| Tools | Metadata… | Opens a window to change the date, description and copyright, remove the location, or remove all metadata. The image is not encoded again. |
| Tools | Copy text | Reads the text in each image with the text recognition built into Windows and puts it on the clipboard, a line for each line. |
| Tools | Combine into PDF | All the dropped images in one PDF, a page each, in name order, on A4 or Letter pages if Settings says so. |
| Tools | Collage… | Opens a window to lay 2 to 20 images out in a grid, row, column or featured layout. Saves Collage.jpg, or Collage.png with a transparent background, next to the first one. |
| Tools | Strip metadata | Removes EXIF, XMP and IPTC, GPS location included. Keeps the colour profile. The image is encoded again, so JPEG photos use Metadata… instead. |

### PDF

| Tab | Wedge | What it does |
|---|---|---|
| Convert | PNG | Every page as a PNG at 150 dpi, or 300 or 600 from Settings. |
| Convert | JPG | Every page as a JPG at 150 dpi, or 300 or 600 from Settings. |
| Tools | Merge | Two or more PDFs into one, in name order. |
| Tools | Split into pages | One PDF per page. |
| Tools | Compress | Rewrites the file more compactly. Pages look exactly the same. |
| Tools | Rotate 90° | Every page a quarter turn clockwise. |
| Tools | Organize… | Opens a window to reorder, rotate, duplicate or delete pages. |
| Tools | Metadata… | Opens a window to change the title, author, subject and keywords, or to remove them all. |

### Audio

| Tab | Wedge | What it does |
|---|---|---|
| Convert | MP3 | Plays everywhere. 192 kbps, or another bitrate from Settings. |
| Convert | M4A | AAC at 192 kbps, or Apple Lossless from Settings. |
| Convert | WAV | Uncompressed, at the source's sample rate. |
| Convert | FLAC | Lossless and smaller than WAV. |
| Convert | OGG | Ogg Vorbis, about 192 kbps. |
| Convert | OPUS | Opus at 160 kbps, small and clear. |
| Convert | AIFF | Uncompressed, the Mac way. |
| Convert | WMA | Windows Media Audio at 192 kbps, or another bitrate from Settings. |
| Tools | Compress… | Opens a window to pick a target size or a percentage. Saves smaller MP3, M4A or OPUS copies. |
| Tools | Trim… | Opens a window to keep the part you choose. |
| Tools | Normalize… | Opens a window to measure the loudness and save copies at the level you choose. |
| Tools | Channels… | Opens a window to make mono, keep one side, set each side's volume or swap them. |
| Tools | Bleep… | Opens a window to cover the parts you mark with a bleep or with silence. |
| Tools | Visualizer… | Opens a window to turn a sound into an MP4 with a moving waveform or a picture. |
| Tools | Metadata… | Opens a window to change title, artist, album, year, track, genre and cover, or to remove every tag. The audio is not encoded again. |

### Video

| Tab | Wedge | What it does |
|---|---|---|
| Convert | MP4 | H.264 up to 1080p, plays almost everywhere. Up to 4K or HEVC from Settings. |
| Convert | WEBM | VP9 and Opus up to 1080p, for the web. |
| Convert | GIF | Animated, 480 px and 15 frames a second, no sound. Videos up to 2 minutes. |
| Convert | MP3 | Just the sound, as MP3. |
| Convert | M4A | Just the sound, as M4A. |
| Tools | Compress… | Opens a window to pick a target size or a percentage. Saves smaller MP4 copies. |
| Tools | Trim… | Opens a window to keep the part you choose. |
| Tools | Crop… | Opens a window to keep part of the picture. |
| Tools | Speed… | Opens a window to make a faster or slower copy. The voice keeps its pitch. |
| Tools | Split… | Opens a window to cut it into clips. |
| Tools | Frames… | Opens a window to pick frames and save them as PNG. |
| Tools | Mute | The same video without sound. |
| Tools | Join… | Opens a window to set the order and save one video. |

### Documents

| Tab | Wedge | What it does |
|---|---|---|
| Convert | PDF | Pages as they print, with fonts and pictures in place. |
| Convert | DOCX | A Word document, from Markdown, text, web pages, RTF or old .doc files. |
| Convert | TXT | Only the words, in UTF-8. |
| Convert | MD | Markdown with headings, lists and tables; pictures go in a folder beside it. |
| Convert | HTML | One web page with the pictures inside, opens in any browser. |
| Convert | EPUB | A reflowable e-book with a table of contents from the headings. |
| Convert | PNG | One picture per page, at the resolution chosen in Settings. |
| Convert | JPG | One picture per page, smaller than PNG. |

### Slides

| Tab | Wedge | What it does |
|---|---|---|
| Convert | PDF | One page per slide, to send or print. |
| Convert | PNG | One picture per slide, at the resolution chosen in Settings. |
| Convert | JPG | One picture per slide, smaller than PNG. |

### Spreadsheets

| Tab | Wedge | What it does |
|---|---|---|
| Convert | PDF | The sheets as they print. |
| Convert | XLSX | An Excel workbook, from CSV, TSV or old .xls files. |
| Convert | CSV | One file per sheet, values as they appear, commas between. |
| Convert | TSV | One file per sheet, values as they appear, tabs between. |
| Convert | ODS | An OpenDocument workbook for LibreOffice and others. |

### Any file or folder

| Tab | Wedge | What it does |
|---|---|---|
| Actions | Float | Park files on a small glass shelf, then drag them into any app. |
| Actions | Copy path | Full paths on the clipboard, one per line. |
| Actions | ZIP | One archive next to the first item. Folders included. |
| Actions | Share | The Windows share sheet. |
| Actions | Copy to… | Pick a folder; Windows copies, with its own progress and undo. |
| Actions | Move to… | Pick a folder; Windows moves, with its own progress and undo. |
| Actions | Terminal | Opens Windows Terminal in the folder, or PowerShell if it is not installed. |
| Actions | Unzip | Extracts each ZIP, TAR or GZ file next to it, with no folder inside a folder. |

## Settings

- Give each tab its own key: Shift, Ctrl, Alt, F8 or F9.
- Pick a small, medium or large wheel, put its wedges in your order, hide the ones you don't use and give it an accent colour.
- Set the quality of JPG, WEBP, AVIF and HEIC, MP4 up to 4K and in HEVC, the audio bitrates, Apple Lossless and the page size of PDFs.
- Turn the soft tick and the key bar next to the pointer on or off.
- Light and dark follow Windows, and so do the high contrast themes.

## Privacy

Everything runs on your PC and no file is ever uploaded. There is no account, no ads and no analytics. Pomelo's log never holds file names, paths or file contents, and it is never sent anywhere. The [privacy policy](https://pomeloapp.net/privacy/) says what the developer receives if you write to him or send a report.

## Price

Convert and Tools start with 20 free files, and Actions are always free. Unlock Pomelo, a one-time in-app purchase of USD 19.99 or the equivalent in your currency, removes the limit. There is no subscription. The [terms](https://pomeloapp.net/terms/) cover the licence.

## Requirements

- Windows 11 version 22H2 or later, x64.
- A mouse or a touchpad and a keyboard: the wheel opens on drags that start in File Explorer or on the desktop.
- HEIC files need the HEIF Image Extensions and the HEVC Video Extensions from the Microsoft Store. HEVC, VP9 and AV1 video need their Windows video extensions.
- Windows N editions need the Media Feature Pack for audio and video.
- The interface is in English.

## Support

- [Open an issue](https://github.com/andrealo20/pomelo/issues/new/choose) for a bug or an idea.
- [Report a problem](https://pomeloapp.net/feedback/) privately, with a log or a screenshot.
- Write to [support@pomeloapp.net](mailto:support@pomeloapp.net).
- [Help](https://pomeloapp.net/help/) explains the gesture, the keys and every window.

## About this repository

Pomelo is closed source, so this repository holds no code. It is the app's public page: what it does, what changed in each version ([CHANGELOG.md](CHANGELOG.md)) and an issue tracker. The open-source libraries Pomelo ships with, and the source code their licences ask for, are on [pomeloapp.net/source](https://pomeloapp.net/source/).

© 2026 Andrea Loroni. All rights reserved.

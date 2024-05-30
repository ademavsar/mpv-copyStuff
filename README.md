# mpv-copyStuff

Bu script panoya kopyalar:
- Dosya Adı (Uzantısı ile) veya URL Linki
- Tam Dosya Adı Yolu
- Geçerli Video Süresi (HH:MM:SS.MS)
- Geçerli Gösterilen Altyazı Metni
- Video Metadata

## Installation

Script dosyasını `copyStuff.lua` scripts klasörünüze koyun, genellikle:
- Windows: `"C:\Users\Username\AppData\Roaming\mpv\scripts"`.
- Linux ve MacOS: `"~/.config/mpv/scripts/"`.

Scriptin çalışabilmesi için:
- Windows: `Powershell`.
- Linux/X11: `xclip`.
- Linux/Wayland : `xclip` veya `wl-clipboard`.
- MacOS: `pbcopy` (test edilmedi).

## Hotkeys

<div align="center">

| Kopyalanan                          | Hotkey     |
| ----------------------------------- | ---------- |
| **Dosya Adı veya URL Linki**        | **CTRL+f** |
| **Tam Dosya Adı Yolu**              | **CTRL+p** |
| **Geçerli Video Süresi (HH:MM:SS.MS)** | **CTRL+t** |
| **Geçerli Gösterilen Altyazı Metni** | **CTRL+s** |
| **Video Süresi**                    | **CTRL+d** |
| **Video Metadata**                  | **CTRL+m** |

</div>

# Screenshots

![ss1](https://raw.githubusercontent.com/rofe33/screenshots/main/mpv-copyStuff/example_01.png)
![ss2](https://raw.githubusercontent.com/rofe33/screenshots/main/mpv-copyStuff/example_02.png)
![ss4](https://raw.githubusercontent.com/rofe33/screenshots/main/mpv-copyStuff/example_04.png)
![ss5](https://raw.githubusercontent.com/rofe33/screenshots/main/mpv-copyStuff/example_05.png)

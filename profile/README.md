<div align="center">

# Verity Local

### Clarity, without the cloud.

PDF-first document review, with evidence you can inspect and a local desktop companion.

**[Download for macOS & Windows](https://veritylocal.github.io/)** · **[Source](https://github.com/VerityLocal/Main)** · **[Development releases](https://github.com/VerityLocal/Main/releases)**

No account or API key. Automatic runtime setup, pairing and helper startup.

</div>

---

## Review the document. Understand the evidence.

- Read the active PDF, including supported embedded PDFs, or a read-only website.
- Inspect source-overlap highlights, attributed links and search coverage.
- Export a JSON or text report; clear the panel when finished.
- Keep authorship inference local. Web source comparison requires explicit consent
  and shares short excerpts with search services.

## Download and install

**[Download the browser extension ZIP](https://github.com/VerityLocal/Main/releases/download/v0.2.0-dev.1/Verity-Extension.zip)**
— one shared Chrome/Edge package for macOS and Windows. **The local companion is
still required** for PDF extraction and analysis. Companion installers already
include the extension; use this ZIP to load or update it separately.

| Platform | Requirements | Development download |
| --- | --- | --- |
| **macOS** | macOS 14+, Intel or Apple Silicon | [Download ZIP](https://github.com/VerityLocal/Main/releases/download/v0.2.0-dev.1/Verity-macOS.zip) |
| **Windows** | Windows 10/11 x64 | [Download ZIP](https://github.com/VerityLocal/Main/releases/download/v0.2.0-dev.1/Verity-Windows.zip) |

1. Extract the ZIP and open the installer if the operating system permits it.
2. Approve installation; the runtime and permitted local models are provisioned
   automatically where hardware permits.
3. Enable Developer mode in Chrome/Edge and **Load unpacked** using the extension
   folder shown in Finder/Explorer, or the **Verity Extension** folder from the
   separate extension ZIP. Pairing and helper startup/restart are automatic.

First installation requires internet: about **1.9 GB** of Desklib/BGE downloads on
supported machines, plus runtime/browser/ML dependencies. The Falcon pair adds
about **29 GB** only on machines with 64 GiB+ RAM. No terminal, Python setup or token entry is
needed for installer users. Firefox compatibility is experimental; Linux, Safari,
mobile, native Windows ARM64 and 32-bit Windows are not supported.

### Development status — please read

Both installers are **unsigned development builds**, not production releases.
Operating systems may warn or block them. **Do not disable OS security.** Windows
installation/browser integration and Intel macOS execution are not yet tested.
Signed installers are not yet available.

**AI percentages remain Unavailable until independently calibrated.** Desklib and
BGE-small use fixed revisions and verified hashes. The full Binoculars pair has
not been tested on the 16 GiB Mac; GPTSniffer checkpoint permission and a production
known-AI code corpus remain unresolved. Setup completion is not inference readiness.
No detector accuracy or fine-tuning claim is made. Source overlap is
evidence to review, not proof of plagiarism or misconduct; missing coverage does
not establish originality. Do not use results as authorship proof or for discipline.

## Project

- [Product source, builds and tests](https://github.com/VerityLocal/Main)
- [Download website](https://veritylocal.github.io/)
- [Release/platform limitations](https://github.com/VerityLocal/Main/blob/main/docs/DISTRIBUTION.md)
- [Privacy and security](https://github.com/VerityLocal/Main/blob/main/docs/SECURITY.md)
- [Model and calibration guidance](https://github.com/VerityLocal/Main/blob/main/docs/MODELS.md)

## Built by

**[Akash Majumdar](https://github.com/Kannicknotfound)** and
**[Bhumit Maru](https://github.com/bhumitmaru)**<br>
B.Tech in Artificial Intelligence & Data Science (AI&DS)<br>
**K. J. Somaiya School of Engineering, Mumbai**

Upstream dependencies and optional model assets retain their own licenses.
Required installer/compiler notices are retained; restricted models are not bundled.

Found a bug? **[Open an issue](https://github.com/VerityLocal/Main/issues)**.

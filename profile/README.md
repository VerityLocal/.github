<div align="center">

<img src="https://raw.githubusercontent.com/VerityLocal/Main/main/extension/icons/icon-128.png" width="80" alt="Verity Local">

# Verity Local

### A closer look. Without the cloud.

Local PDF and source-file review, with signals you can explore and evidence you can follow.

[**Website**](https://veritylocal.github.io/) · [**Downloads**](https://veritylocal.github.io/#downloads) · [**Setup guide**](https://veritylocal.github.io/#setup) · [**Source**](https://github.com/VerityLocal/Main)

</div>

![Verity Local reviewing a public demonstration PDF](https://raw.githubusercontent.com/VerityLocal/Main/main/docs/screenshots/review-overview.webp)

## A little more clarity. A lot more privacy.

Verity Local pairs a **Chrome/Edge extension** with a **Python backend on your computer**. Review PDFs, Python, JavaScript, and UTF-8 text without sending your documents to an external inference service.

- **A quick view:** analyze a PDF from the toolbar popup and return to the same background session.
- **A detailed view:** inspect passages and jump to their highlighted locations in the original document.
- **Clear coverage:** see what was read, skipped, excluded, or unsupported.
- **Separate signals:** English prose and Python/JavaScript code have independent summaries.
- **Local models:** pinned Desklib text weights and CodeBERT + custom LoRA code weights, verified before loading.

Detector outputs are experimental signals, not proof of authorship. Percentages describe the share of **analyzed content** flagged; neither detector is validated for university submissions.

## Get started

1. [Download Verity Local v0.4.0](https://github.com/VerityLocal/Main/releases/download/v0.4.0/Verity-Local-v0.4.0.zip) and extract the project.
2. Install Python dependencies and model files with the [illustrated setup guide](https://veritylocal.github.io/#setup).
3. Load the included extension using Chrome/Edge's **Load unpacked**.
4. Start the backend with your extension ID, then connect in **Settings**.
5. Try the included public demonstration PDF and explore the evidence.

**Python 3.11+ · Chrome 116+ / compatible Edge · macOS / Linux · Windows via WSL 2**

The complete project ZIP includes a built extension. Separate [extension](https://github.com/VerityLocal/Main/releases/download/v0.4.0/Verity-Local-Extension-v0.4.0.zip), [text model](https://github.com/VerityLocal/Main/releases/download/v0.4.0/Verity-Local-Text-Model-v0.4.0.zip), and [code model](https://github.com/VerityLocal/Main/releases/download/v0.4.0/Verity-Local-Code-Model-v0.4.0.zip) downloads are also available, with [checksums](https://github.com/VerityLocal/Main/releases/download/v0.4.0/SHA256SUMS.txt).

## Around the project

| Repository | What lives here |
| --- | --- |
| [**Main**](https://github.com/VerityLocal/Main) | Application source, tests, documentation, models metadata, and downloadable releases |
| [**.github**](https://github.com/VerityLocal/.github) | This organization profile and project overview |
| [**veritylocal.github.io**](https://github.com/VerityLocal/veritylocal.github.io) | The website, downloads, screenshots, and setup walkthrough |

[Read the documentation](https://github.com/VerityLocal/Main/blob/main/docs/SETUP.md) · [Understand the models](https://github.com/VerityLocal/Main/blob/main/docs/MODELS.md) · [Report an issue](https://github.com/VerityLocal/Main/issues)

<div align="center">

# Verity Local

### Clarity, without the cloud.

Private AI-writing, source-similarity, and factual-claim analysis inside your browser.

**[Get the extension](https://veritylocal.github.io/project-final-deployment/)** · **[Download v1.0.0](https://github.com/VerityLocal/project-final-deployment/releases/download/v1.0.0/verity-local-extension-v1.0.0.zip)** · **[Explore the research](https://github.com/VerityLocal/project-build-up)**

No account. No API key. No Python, terminal, server, or backend pairing.

</div>

---

## Your words. Your browser. Your control.

Verity Local is an open-source, browser-only text-analysis extension. Paste text
or read the current page, choose your analysis engines, and explore the findings
in a side panel. Your document and reference passages stay in your browser.

| Engine | What it helps you explore |
| --- | --- |
| **AI writing** | Document and sentence-level signals from an English research-pilot detector—not proof of authorship. |
| **Source similarity** | Textual and semantic overlap with passages you supply in your local knowledge library. |
| **Factual claims** | Experimental, evidence-dependent claim labels based on your supplied references. |

There is **no cloud inference, external search, or analytics in the extension**.
Models download from versioned GitHub releases on first use, are checked against
pinned sizes and SHA-256 hashes, and are cached in your browser profile. Selected
engines work offline once their models are cached. GitHub receives ordinary
download requests and your IP address—not your document text.

## Install in four steps

1. **[Download the extension ZIP](https://github.com/VerityLocal/project-final-deployment/releases/download/v1.0.0/verity-local-extension-v1.0.0.zip)** and extract it.
2. Open `chrome://extensions`, `brave://extensions`, or `edge://extensions` on your desktop browser.
3. Enable **Developer mode**, click **Load unpacked**, and select the extracted folder containing `manifest.json`.
4. Pin **Verity Local**, click its icon, paste text or choose **Read current page**, then **Analyze locally**.

**Requirements:** desktop Chrome, Brave, or Edge 116+ with WebAssembly SIMD and
side-panel support. Firefox, Safari, and mobile are not supported. This is a
manual, unpacked installation—not a browser-store listing.

**First use:** the extension ZIP is about **4.8 MiB**. Models download separately:
about **575 MB** for AI detection, or **1.44 GB** for all models. Keep the side panel
open during setup and analysis; downloads can take several minutes and FP32
inference requires substantial free memory.

**[Full installation guide & download website →](https://veritylocal.github.io/project-final-deployment/)**

## Explore the project

| Repository | What's inside |
| --- | --- |
| **[project-final-deployment](https://github.com/VerityLocal/project-final-deployment)** | Directly loadable MV3 browser extension, downloadable releases, model card, and the download website. |
| **[project-build-up](https://github.com/VerityLocal/project-build-up)** | Source and pinned dependencies, training, dataset preparation, evaluations, browser-model releases, verification evidence, and preserved development history. |

- [Extension releases](https://github.com/VerityLocal/project-final-deployment/releases)
- [Versioned browser models](https://github.com/VerityLocal/project-build-up/releases/tag/browser-models-v1)
- [Browser architecture & reproduction](https://github.com/VerityLocal/project-build-up/blob/main/docs/browser-native.md)
- [Real-browser verification evidence](https://github.com/VerityLocal/project-build-up/tree/main/reports/browser-native)

## A signal, not a verdict

This is a **research pilot**, not authorship, plagiarism, or misconduct proof.

- The detector's original held-out document accuracy is **79.75%**, with a
  **23.14% human false-positive rate** at threshold 0.5. These are bounded pilot
  measurements, not a guarantee for new writing or domains.
- Its document score estimates whether a document contains annotated AI content,
  including mixed writing—not the percentage of AI-written words. English input
  is limited to **512 tokens / 128 sentences** without silent truncation.
- Similarity and claim outputs are experimental and uncalibrated. You supply
  the references and judge their trust. A source URL is only a citation; it is
  not fetched. Missing evidence does **not** establish that a claim is false.
- Page reading inspects rendered DOM. Google Docs canvas, closed shadow roots,
  and unrendered virtualized content are unsupported; paste text instead.
- Do not use findings as authorship proof or for disciplinary decisions.

Read the **[model card](https://github.com/VerityLocal/project-final-deployment/blob/main/MODEL_CARD.md)**
and **[full extension limits](https://github.com/VerityLocal/project-final-deployment#limits)**
before relying on results.

## Built by

**[Akash Majumdar](https://github.com/Kannicknotfound)** and
**[Bhumit Maru](https://github.com/bhumitmaru)**<br>
B.Tech in Artificial Intelligence & Data Science (AI&DS)<br>
**K. J. Somaiya School of Engineering, Mumbai**

Original code is [MIT licensed](https://github.com/VerityLocal/project-final-deployment/blob/main/LICENSE).
Upstream assets retain their own licenses; see
[third-party notices](https://github.com/VerityLocal/project-final-deployment/blob/main/THIRD_PARTY_NOTICES.md).

Found a bug? **[Open an extension issue](https://github.com/VerityLocal/project-final-deployment/issues)**
or **[a research issue](https://github.com/VerityLocal/project-build-up/issues)**.

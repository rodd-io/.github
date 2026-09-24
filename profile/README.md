<div align="center">

# rodd

**A Nordic Data Infrastructure Company**

Transform messy legacy knowledge into open standards, then train local models strictly behind your firewall.

[Website](https://rodd.io) • [Documentation](https://docs.rodd.io) • [Contact](mailto:hello@rodd.io)

</div>

---

### Overview

Most enterprise data remains trapped in legacy silos—scanned PDFs, stale wikis, and proprietary database formats. Moving to modern AI workflows typically forces teams into another proprietary vendor ecosystem.

**Rodd** provides the data plumbing for true digital sovereignty:

1. Extract and normalize legacy records into portable, open text formats.
2. Structure that clean corpus to train or fine-tune local models hosted exclusively on your hardware.

---

### Core Architecture

```text
[Legacy Silos] (PDFs, ERPs, Confluence)
       │
       ▼  RODD UNBIND
[Portable Open Markdown & JSON]
       │
       ▼  RODD FORGE
[Private Local Model] 
```
---

### Products

#### [rodd / unbind](https://github.com/rodd-io/unbind)
*Transform legacy knowledge into open text standards.*
* Extracts data from proprietary file formats, OCR archives, and relational dumps.
* Strips boilerplate formatting and broken XML.
* Outputs organized, model-ready Markdown file trees with normalized metadata.

#### [rodd / forge](https://github.com/rodd-io/forge)
*Train private local models exclusively on your data.*
* Prepares instruction-tuning pairs and clean JSONL datasets from your Markdown corpus.
* Runs efficient fine-tuning (LoRA / QLoRA) on open-weight models.
* Exports quantized checkpoints (`.gguf`) for on-prem execution via Ollama or vLLM.
* 100% air-gapped: zero tokens or internal records leave your local infrastructure.

---

### Principles

* **Open Standards First:** Knowledge should be stored in human-readable, portable formats, not locked inside database black boxes.
* **Complete Data Sovereignty:** Models are trained on your machines and serve your team behind your firewall.
* **No Vendor Lock-In:** Retain full ownership of both your raw documentation and your final fine-tuned weights.

---

<div align="center">
  <sub>Built in Denmark. Focused on open standards and private infrastructure.</sub>
</div>

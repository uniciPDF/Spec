# UniciPDF

**UniciPDF** is an open initiative to standardize how PDF documents are designed, composed, rendered, and manipulated across platforms.  
Its goal is to provide a **unified, declarative, and language-agnostic API**, focused on clarity, precision, and interoperability.

---

## 🌐 Overview

PDF is a powerful format — but building, editing or rendering PDFs is often a nightmare of inconsistent tools, outdated specs and poor developer experience.

**UniciPDF** changes that. It defines a common, extensible standard (based on **JSON** and **CSS-like rulesets**) that can be implemented in any language.

---

## 🎯 Goals

- ✅ Define a unified JSON-based structure for document composition
- ✅ Use readable, CSS-like styling rules (including media print)
- ✅ Support modern layout: headers/footers, pagination, tables, sections…
- ✅ Enable real-time rendering, post-processing and digital signing
- ✅ Offer bindings in **PHP** and **JavaScript** (first), and encourage others
- ✅ Ensure full compliance with **PDF 2.0**, **PDF/A**, **PDF/UA**, **PDF/X**

---

## 🚀 Language support

UniciPDF is language-agnostic by design.  

We’re currently building first-party SDKs for:

- [x] PHP
- [x] JavaScript / Node.js
- [ ] Python *(planned)*
- [ ] .NET *(planned)*

> Contribute your own SDK or binding for any language — we’ll help review and document it.

---

## 📦 Package structure

| Repository              | Description                                  |
|-------------------------|----------------------------------------------|
| `unicipdf/spec`         | Core specification (JSON schema + rules)     |
| `unicipdf/php-sdk`      | PHP SDK for rendering and manipulation       |
| `unicipdf/js-sdk`       | JS SDK for rendering, browser and server     |
| `unicipdf/docs`         | Documentation, guides and examples           |
| `unicipdf/cli`          | Future CLI tool for conversion and linting   |

---

## 📄 License

UniciPDF is licensed under the **WordPress-style GPL-2.0-or-later** philosophy:  
free to use, modify, and distribute — but all **connectors, integrations and plugins must remain open and auditable**.

---

## 🤝 Contributing

We welcome contributions from developers, designers and technical writers.  
Whether you want to implement a new language binding or propose changes to the spec, feel free to open issues and pull requests.

- See `CONTRIBUTING.md` (soon)
- Follow the [roadmap](#roadmap)
- Join the discussion: coming soon on GitHub Discussions and Discord

---

## 🗺️ Roadmap (Q3 2025)

- [x] Define initial JSON + style format
- [x] Publish public repo and governance
- [ ] Build MVP PDF engine in PHP (w/ TCPDF backend)
- [ ] Build MVP renderer in JS (Canvas/WebWorker based)
- [ ] Support postprocessing: merge, split, watermark
- [ ] Add PDF/A and digital signature support
- [ ] Formalize test suite (PDF 2.0 spec-driven)
- [ ] Launch UniciPDF test compliance badge system

---

> Made with ambition and ethics.  
> For document creators, developers, and the open web.


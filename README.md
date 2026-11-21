# Cybersecurity Research

Independent cybersecurity research and technical white papers by **Wesley Atwell**.

This repository is the publication home for security-focused engineering papers covering operating-system internals, cryptography, secure networking, and container-management security. Each paper will have its own scope, supporting references, and publication history. The underlying software projects remain in their original repositories.

**Author:** Wesley Atwell  
**Website:** https://wesleyatwell.net  
**GitHub:** https://github.com/Wes2000ley  
**LinkedIn:** https://www.linkedin.com/in/wesleyatwell/

## Research papers

The following are **planned publications**, not completed or released papers. Titles and scope may be refined during research and writing.

| Working title | Research focus | Supporting project | Status |
| --- | --- | --- | --- |
| **Security and Reliability Engineering in the Linux Kernel** | Cryptographic API correctness, tracing failure paths, memory management, and TCP/IPv6 concurrency across seven accepted mainline patches. | [Linux contribution record](https://wesleyatwell.net/kernel/) · [Upstream author log](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=Wesley+Atwell) | Planned |
| **Security Architecture of a Windows TLS/DTLS VPN** | TrueTunnel's TLS 1.3/DTLS 1.3 profiles, authentication, key lifecycle, privilege boundaries, threat model, and documented limitations. | [TrueTunnel VPN](https://github.com/Wes2000ley/TrueTunnel-VPN) | Planned |
| **Experimental Authenticated Encryption: Design and Analysis** | Cobalt AEAD research, model-based analysis, differential/linear techniques, verification evidence, and unresolved assurance questions. | Crypto Lab (private research; selected findings may be published) | Planned |
| **Privilege Boundaries in Unified Container Management** | Authentication, Windows named-pipe authorization, engine access, credential handling, and isolation between desktop, browser, and privileged services. | [Unified Container Desktop](https://github.com/Wes2000ley/unified-container-desktop) | Planned |

## Publication format

Each completed paper is intended to live in its own directory under `papers/`, with a readable Markdown version, a PDF for sharing and archiving, and references or supporting material where useful.

```text
papers/
├── linux-kernel-security/
│   ├── paper.md
│   ├── paper.pdf
│   └── references.md
├── truetunnel-vpn-security/
│   ├── paper.md
│   ├── paper.pdf
│   └── references.md
├── experimental-aead-research/
│   ├── paper.md
│   ├── paper.pdf
│   └── references.md
└── container-management-security/
    ├── paper.md
    ├── paper.pdf
    └── references.md
```

This is a **planned layout**. Directories and files will be added as their respective publications are prepared; no draft is represented as a released paper.

## Research and publication principles

- Clearly distinguish observed results, reproduced findings, design assumptions, and unresolved questions.
- Cite upstream source code, standards, research, and other primary references where available.
- Document meaningful threat models, limitations, and known security tradeoffs rather than implying unverified assurance.
- Record a version and publication date in each finished paper; use releases or archival DOIs when appropriate.
- Publish only material authorized for public disclosure. No employer-controlled, restricted, sensitive, or private source information belongs here.

The publications are technical analyses, not claims of third-party audit, certification, or production suitability unless independently substantiated.

## Citation

When citing a completed paper, include **Wesley Atwell**, the exact paper title, its publication date and version, and the paper's permanent URL or DOI if one is assigned. Paper-specific citation information will accompany each publication.

## License

Unless a file explicitly states otherwise, **original written research, papers, and author-created diagrams published in this repository** are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE) for the complete legal text.

The license covers only material for which the author has the necessary rights. Third-party material remains under its original terms. Links to other repositories do not change those projects' licenses. Any executable source code subsequently added here should carry its own explicit software license; do not assume this research-publication license applies to code in linked projects.

Copyright © 2026 Wesley Atwell.

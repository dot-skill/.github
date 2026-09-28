<div align="center">

<a href="https://skillerr.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dot-skill/skillerr-browser/main/.github/assets/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dot-skill/skillerr-browser/main/.github/assets/banner-light.png">
    <img alt="skillerr: the browser that skills your AI" src="https://raw.githubusercontent.com/dot-skill/skillerr-browser/main/.github/assets/banner-light.png" width="520">
  </picture>
</a>

**Research like it was meant to be.**<br>
See what your AI browses. Keep what it learns.

<a href="https://skillerr.com"><b>Website</b></a> ·
<a href="https://github.com/dot-skill/skillerr-releases/releases/latest"><b>Download</b></a> ·
<a href="https://github.com/dot-skill/skillerr-browser"><b>Source</b></a> ·
<a href="https://skillerr.com/agents.md"><b>Let your AI install it</b></a>

</div>

## Skillerr Browser

A free, open-source desktop browser (macOS, Windows, Linux) that your own AI drives: Claude Desktop, Claude Code, Cursor
or a local model, over MCP.

- **Visible:** every page your AI reads opens as a real tab you can watch, many at once.
- **Governed:** pause, take over and undo; payments, passwords, sign-ins and deletions wait for your OK.
- **Kept:** research stays on your computer, as a research memory, folders and skills any AI can use.
- **Light and private:** Chrome's page speed with less memory, and no telemetry.

<img alt="Skillerr's fleet view: an AI researching power bank rules across four live tabs" src="https://raw.githubusercontent.com/dot-skill/skillerr-browser/main/.github/assets/fleet.png" width="100%">

```bash
curl -fsSL https://skillerr.com/install.sh | sh     # macOS and Linux
irm https://skillerr.com/install.ps1 | iex          # Windows (PowerShell)
```

| Repository | What it is |
|---|---|
| [**skillerr-browser**](https://github.com/dot-skill/skillerr-browser) | The browser: app, MCP bridge and install scripts. AGPL-3.0. |
| [**skillerr-releases**](https://github.com/dot-skill/skillerr-releases) | Installers for every platform. |

## In progress: the Open `.skill` Protocol

A sealed, inspectable package format for AI skills: typed inputs and outputs, a workflow, pinned knowledge and digests,
so a skill can be checked before it runs and handed between agents. Skills in Skillerr Browser will be able to use it.
Early work, not yet part of the browser.

| Repository | What it is |
|---|---|
| [skillerr](https://github.com/dot-skill/skillerr) | The protocol and its reference CLI (`npm i -g skillerr`). Apache-2.0. |
| [skill-score](https://github.com/dot-skill/skill-score) | A vendor-neutral scoring protocol for `.skill` packages. MIT. |
| [skillerr-com](https://github.com/dot-skill/skillerr-com) | Protocol documentation. |

<sub>Made by Bharat Dudeja · <a href="https://skillerr.com">skillerr.com</a></sub>

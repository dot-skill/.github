<p align="center">
  <img src="https://raw.githubusercontent.com/dot-skill/dot-skill/main/assets/skillerr-mark.png" alt="Skillerr — the Dotling" width="128" height="128" />
</p>

<h1 align="center">Skillerr</h1>

<p align="center"><strong>Open protocol and portable <code>.skill</code> format for AI skills.</strong></p>

<p align="center">
  Install once. Point your AI at the work.<br/>
  Agents create, inspect, hand off, and dry-run skills — you review and approve releases.
</p>

<p align="center">
  <a href="https://skillerr.com">skillerr.com</a> ·
  <a href="https://github.com/dot-skill/dot-skill">dot-skill/dot-skill</a> ·
  <a href="https://www.npmjs.com/package/skillerr"><code>npm i -g skillerr</code></a>
</p>

---

## Why Skillerr

Plain markdown “skills” and chat exports break down: every model re-interprets prose, context dies across tools, and there is no integrity story before something runs.

**`.skill`** is a sealed, inspectable package — typed I/O, workflow, pinned knowledge, redacted provenance, digests, optional mint. **Skillerr** is the open protocol; **`skillerr`** is the reference CLI your agent uses.

The mark is the **Dotling** — the living `.` in `.skill`.

## Start here

```bash
npm i -g skillerr
```

Then paste this into Cursor, ChatGPT, Claude, Codex, or any agent with shell tools:

```text
Install skillerr if needed. Set SKILL_HOST to your host id. From this conversation,
create a portable .skill with a redacted journey and exact sections I approved
(secrets as {{refs}}). Checkpoint for handoff, or compile --approve --mint when
release-complete. Do not invent filler. Show status and the output path.
```

More agent prompts and docs: [dot-skill/dot-skill](https://github.com/dot-skill/dot-skill) · [skillerr.com](https://skillerr.com)

## Trust honesty

Inspect TrustView (digests/seals) before run. Declared host/model fields are self-reported provenance — not cryptographic proof of authorship. Reference mint HMAC in the repo is development-only.

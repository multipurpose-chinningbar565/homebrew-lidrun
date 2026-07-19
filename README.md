# LidRun — Homebrew tap

Install [**LidRun**](https://lidrun.com) with Homebrew — the macOS menu-bar app
that keeps AI agents and long-running dev jobs alive on a Mac **even with the lid
closed** (clamshell), with battery + thermal guardrails so nothing cooks or drains.

```sh
brew tap aibrickai/lidrun
brew install --cask lidrun
```

Homebrew 6+ refuses a third-party tap until trusted. If you see
`Refusing to load cask ... from untrusted tap`, trust it once:

```sh
brew trust aibrickai/lidrun
brew install --cask lidrun
```

The DMG is **Developer-ID signed and notarized** — it installs with no Gatekeeper
warning, and LidRun keeps itself updated via Sparkle (`auto_updates`).

## What LidRun does

- Keep a MacBook awake with the **lid closed** for Claude Code, Cursor, Codex,
  Ollama, Docker, long builds and overnight automation.
- A safe **runtime layer**, not just an anti-sleep toggle: low-battery auto-sleep,
  thermal awareness, process auto-watch, a `lidrun` CLI, and push notifications.
- Free forever for keep-awake; no trial, no subscription.

Website: **https://lidrun.com** · Changelog: https://lidrun.com/changelog

## Uninstall

```sh
brew uninstall --cask lidrun          # remove the app
brew uninstall --zap --cask lidrun    # also remove LidRun's local data
```

LidRun's privileged helper (closed-lid feature) is a system Login Item — turn it
off in System Settings → General → Login Items & Extensions before uninstalling to
remove it fully.

# drawover

Ask your AI agent a question and it draws the answer live on your screen: 3D models built part by part with labels and motion, hand-drawn whiteboard diagrams, and sticky notes.

Inspired by [Clicky](https://heyclicky.com), an AI buddy that sits next to your cursor, sees your screen and points at things.

## Install

```
npx skills add mesomya/drawover
```

Or copy `SKILL.md` and the `references` folder into a `drawover` folder in your agent's skills folder, for example `~/.agents/skills/drawover` (Codex) or `~/.claude/skills/drawover` (Claude Code).

The skill itself is [SKILL.md](SKILL.md); the full drawing language is in [references/reference.md](references/reference.md).

## Use

Works with the Codex app and CLI, and any agent that can run shell commands. Call the skill (`$drawover` in Codex, `/drawover` in Claude Code), or just ask your agent to draw something:

```
$drawover how does a car engine work?
```

## The app

The first time you use the skill, it installs drawover, a small app made with [Tauri](https://tauri.app) for Windows and macOS. It is a see-through layer over your screen that shows the drawings.

- It only accepts drawings from programs on your own computer.
- It starts when you log in. Turn this off from its icon in the taskbar tray (Windows) or menu bar (macOS).
- Remove it on Windows from Settings > Apps > drawover. On macOS, quit it from the menu bar icon, then delete `drawover` from the `Applications` folder in your home folder.

drawover runs on Windows and macOS (Apple Silicon and Intel). macOS support is new.

## License

MIT, for the skill files in this repository.

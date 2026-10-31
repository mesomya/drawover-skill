# drawover

Ask your AI agent a question and it draws the answer live on your screen: 3D models built part by part with labels and motion, hand-drawn whiteboard diagrams, and sticky notes.

Inspired by [Clicky](https://heyclicky.com), an AI buddy that sits next to your cursor, sees your screen and points at things.

## Install

```
npx skills add mesomya/drawover-skill
```

Or copy the `skills/drawover` folder into your agent's skills folder, for example `~/.agents/skills/` (Codex) or `~/.claude/skills/` (Claude Code).

## Use

Works with the Codex app and CLI, and any agent that can run shell commands. Call the skill (`$drawover` in Codex, `/drawover` in Claude Code), or just ask your agent to draw something:

```
$drawover how does a car engine work?
```

## The app

The first time you use the skill, it installs drawover, a small (about 2 MB) Windows app made with [Tauri](https://tauri.app). It is a see-through layer over your screen that shows the drawings.

- It only accepts drawings from programs on your own computer.
- It starts with Windows. Turn this off from its tray icon.
- Remove it from Settings > Apps > drawover.

drawover runs on Windows only for now.

## License

MIT, for the skill files in this repository.

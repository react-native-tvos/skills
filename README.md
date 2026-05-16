# RNTV Skills

AI agent skills for building React Native apps for Apple TV and Android TV using `react-native-tvos`.

## Skills

| Skill | Description |
|---|---|
| [project-create](./plugins/rntv/skills/project-create/) | Creating new TV projects with Expo or Community CLI |
| [specific-features](./plugins/rntv/skills/specific-features/) | Focus navigation, remote input, accessibility, and other TV-specific features |
| [platform-detection](./plugins/rntv/skills/platform-detection/) | Platform detection APIs and TV-specific file extensions |
| [build-configuration](./plugins/rntv/skills/build-configuration/) | Build configuration for New Architecture, Hermes, Podfiles, and Maven |
| [third-party](./plugins/rntv/skills/third-party/) | TV features in third-party packages (Expo, react-native-reanimated, Nativewind/Tailwind, etc.) |
| [update-skills](./plugins/rntv/skills/update-skills/) | Updates the RNTV skills installed on your computer |

## Installation

### Claude Code

Add the marketplace:

```
/plugin marketplace add react-native-tvos/skills
```

Install the plugin:

```
/plugin install rntv
```

### Cursor

**Install from GitHub**

1. Open Cursor Settings (Cmd+Shift+J / Ctrl+Shift+J)
2. Navigate to `Rules & Command` → `Project Rules` → Add Rule → Remote Rule (GitHub)
3. Enter: `https://github.com/react-native-tvos/skills.git`

Skills are automatically discovered and used by the agent based on context.

### Any agent

```
bunx skills add react-native-tvos/skills
```

### Manual installation (symlinks)

Your system's default version of Node must be 22.18.0 or newer.

Clone the `main` branch of this repository and run `./install`. The installation script creates symlinks in `~/.claude/skills` to your clone of this repository.

```sh
git clone https://github.com/react-native-tvos/skills.git && cd skills && ./install
```

## Updating

To update your RNTV skills, ask your AI agent to "Update RNTV skills." This runs the "Update RNTV Skills" skill, which pulls the latest changes and reinstalls the skills.

You can also just run `git pull` and `./install` again.

## License

MIT

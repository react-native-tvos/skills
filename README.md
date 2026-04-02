# RNTV Skills

AI agent skills for building React Native apps for Apple TV and Android TV.

## Skills

| Skill | Description |
|---|---|
| [rntv-project-create](skills/rntv-project-create/) | Creating new TV projects with Expo or Community CLI |
| [rntv-specific-features](skills/rntv-specific-features/) | Focus navigation, remote input, accessibility, and other TV-specific features |
| [rntv-platform-detection](skills/rntv-platform-detection/) | Platform detection APIs and TV-specific file extensions |
| [rntv-build-configuration](skills/rntv-build-configuration/) | Build configuration for New Architecture, Hermes, Podfiles, and Maven |

## Installation

Your system's default version of Node must be version 22.18.0 or newer.

Clone the `main` branch of this repository and run `./install`. The installation script creates symlinks in `~/.claude/skills` to your clone of this repository.

```sh
git clone https://github.com/react-native-tvos/skills.git && cd skills && ./install
```


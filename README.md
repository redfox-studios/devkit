# RedFox Studios DevKit

> Centralized design + branding asset repository for RedFox Studios projects.

## Overview

RedFox Studios DevKit is a modular repository containing shared assets used across RedFox Studios projects. These include:

- Logos (SVG, PNG, etc.)
- Brand color palettes
- Typography and style guides
- Images and icons
- Shared design components

> [!NOTE]
> This repository is typically used as a Git submodule in other projects (e.g. websites, games) to ensure consistency and minimize duplication.

> [!IMPORTANT]
> The DevKit is not final. Many things may change, and the repository may be split into multiple repositories in the future.

## Use Cases

- **Next.js Websites:** Primary use case. Assets imported and rendered statically or dynamically.
- **Games:** Can be used for in-game UI, splash screens, branding overlays, and more.
- Can also be used in more cases than just these 2 above.

## Installation (Submodule)

```bash
git submodule add https://github.com/redfox-studios/devkit.git path/to/devkit
git submodule update --init --recursive
```

### Updating Submodules

When pulling from a repo using this as a submodule:

```bash
git submodule update --init --recursive
```

## Contribution Guidelines

- **Do not modify files directly inside this submodule from dependent projects.**
- If you want to change or improve assets, **open a pull request** to this repository.
- If you're unsure how to implement something, **open an issue** and explain your idea.

## Maintainers

- RedFox Studios - [https://github.com/redfox-studios](https://github.com/redfox-studios)
- Michal Flaška - [https://github.com/pilot2254](https://github.com/pilot2254)

# YAKW - Yet Another KOSS Website

This is the repository for development of (yet another) new and improved KOSS website. Currently deployed at https://beta.kossiitkgp.org and under heavy development.

This website is created using [Astro](https://astro.build).

## Table of Contents

- [Development](#development)
  - [Website Design](#website-design)
  - [Setting Up Locally](#setting-up-locally)
  - [Yarn Commands](#yarn-commands)
- [Project Structure](#project-structure)
  - [File Structure](#file-structure)
  - [Routes](#routes)

## Development

### Website Design

- The designing of this website is being done in figma. Please refer to this [file](<https://www.figma.com/file/Ig70QETLgR6Y0ZPj8ZJuTr/KOSS-Website-(Astro)?type=design&node-id=0%3A1&mode=design&t=RozP8tupGSpVSKtF-1>).
- For edit permissions please request for the same in figma.

### Setting Up Locally

- Install the latest version of [NodeJS](https://nodejs.org/en).
- Install [Yarn](https://yarnpkg.com/) the package manager used in this project instead of `npm`. See the [Yarn docs](https://yarnpkg.com/getting-started/install) for installation instructions.
- Clone this repository.
- Run `yarn install` in a terminal to install all the dependencies.
- Run `yarn dev` to start a local development server at http://localhost:3000.
- Optional: Install the official [Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode) language extension in VSCode to enable syntax highlighting and intellisense for `.astro` files.

### Yarn Commands

All commands are run from the root of the project, from a terminal:
| Command | Action |
| :--------------------- | :----------------------------------------------- |
| `yarn install` | Installs dependencies |
| `yarn dev` | Starts local dev server at `localhost:3000` |
| `yarn build` | Build your production site to `./dist/` |
| `yarn preview` | Preview your build locally, before deploying |
| `yarn astro ...` | Run CLI commands like `astro add`, `astro check` |
| `yarn astro -- --help` | Get help using the Astro CLI |

## Project Structure

### File Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

### Routes

- `/` (Index)
  - File: `src/pages/index.astro`.

---

> Please update this documentation if you make changes to the KOSS website. Future humans will praise you.


### Credits

- “Home” icon by [Dariush](https://www.figma.com/@dariush) from [IconaMoon](https://www.figma.com/community/file/1014143897459418663) - CC BY 4.0
- “About” icon from [Google Material Icons](https://pictogrammers.com/contributor/google/) - Apache v2.0
- “Team” icon from [Microsoft](https://www.iconfinder.com/icons/8675239/ic_fluent_people_team_regular_icon) - CC BY 4.0
- “Events” icon from [Clarity Design System](https://core.clarity.design/foundation/icons/shapes/) - MIT License

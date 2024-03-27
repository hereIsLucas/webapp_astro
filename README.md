# webapp_astro

## Ecosystem Matrix
Name: Astro ist ein relativ neues Framework, das sich durch seine Fähigkeit auszeichnet, schnelle Websites, clientseitige Webanwendungen und dynamische API-Endpunkte zu erstellen.

Age: Astro ist ein relativ neues Framework, das 2024 als Teil der aktuellen Entwicklungen im Web-Entwicklungsumfeld betrachtet wird.

Usage: Astro wird für eine Vielzahl von Anwendungsfällen eingesetzt, einschließlich der Erstellung von Websites, die auf Geschwindigkeit und Leistung optimiert sind. Es unterstützt die Integration von Komponenten aus verschiedenen Frameworks wie React, Svelte und Vue.js, was es zu einem vielseitigen Werkzeug für Entwickler macht.

Documentation: Astro bietet umfangreiche Dokumentation, die Entwicklern hilft, das Framework effektiv zu nutzen. Die Dokumentation deckt Themen wie die Einrichtung eines neuen Astro-Projekts, das Hinzufügen von UI-Frameworks, das Aufbauen von Layouts und das Fetchen von Dashboard-Daten ab.
Issues and Bug Fixes: Astro hat eine aktive Community und regelmäßige Updates, was bedeutet, dass die meisten Probleme und Fehler schnell behoben werden. Entwickler können auch Unterstützung in Form von Diskussionen und Tutorials in der Astro-Community finden.

Migration: Astro unterstützt die Migration zu neuen Frameworks oder Sets von Frameworks, was es zu einem wertvollen Werkzeug für Entwickler macht, die ihre Anwendungen auf neue Technologien aktualisieren möchten. Dies spart Zeit, Bemühungen und Ressourcen.

# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
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

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

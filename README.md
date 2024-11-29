# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Estructura del Portfolio

Dentro de este proyecto podremos ver la siguiente estructuracion de carpetas y archivos:

```text
├── public/
│   └── AstroLogo.svg
│   └── cabecera_2.png
│   └── Caratula X.jpg
│   └── Carnet_Dcg.jpg
│   └── certificado_cohorte3_david_cuevas_gil.pdf
│   └── CSSLogo.svg
│   └── DCG - certificado_cohorte3_david cuevas gil
│   └── email.svg
│   └── FigmaLogo.svg
│   └── github.png
│   └── HTMLogo.svg
│   └── Imagen_wallapop.jpg
│   └── InstagramLogo.svg
│   └── JavaLogo.svg
│   └── JavaScriptLogo.svg
│   └── Linkedin.png
│   └── linkedin.svg
│   └── Logo_pdf.svg
│   └── Node.jsLogo.svg
│   └── phone.svg
│   └── php_logo.png
│   └── portfolio.jpg
│   └── PythonLogo.svg
│   └── ReactLogo.svg
│   └── SpringLogo.svg
│   └── SQLogo.svg
│   └── TailwindLogo.svg
│   └── telefono.svg
│   └── Twitter.jpg
│   └── UbicacionLogo.svg
├── src/
│   ├── components/
│   │   └── Contacto.astro
│   │   └── Experiencia.astro
│   │   └── Formacion.astro
│   │   └── Habilidades.astro
│   │   └── Header.astro
│   │   └── Menu.astro
│   │   └── Proyectos.astro
│   │   └── Referencias.astro
│   │   └── SobreMi.astro
│   │   └── Skills.astro
│   ├── data/
│   │   └── formacion.json
│   │   └── experiencia.json
│   │   └── habilidades.json
│   │   └── referencias.json
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── env.d.ts
├── .gitignore
├── astro.config.mjs
├── package-lock.json
├── package.json
├── README.md
├── tailwind.config.mjs
└── tsconfig.json
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

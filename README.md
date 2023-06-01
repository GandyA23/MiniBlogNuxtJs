# Miniblog (Nuxt)

<br>

## About
This is a personal repository to practice with Nuxt 3, the project (miniblog) is a copy from [Curso de Server Side Rendering con Nuxt 2](https://platzi.com/cursos/nuxt/), the project in the course is in Nuxt 2, but this repository is an attempt to programming in Nuxt 3. You are free to clone and comment, the feedback would be greatly appreciated.

<br>

## Prerequisites
You need [Visual Studio Code](https://code.visualstudio.com/) and [Docker](https://www.docker.com/) installed, because this repository use a [devcontainer](https://containers.dev/), it has many benefits that you can read and learn [here](https://code.visualstudio.com/docs/devcontainers/containers). After, you need to install [Dev Container Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) in VSCode.

<br>

## Run locally
Firstly, Init the docker service in your machine with the next command: 

```bash 
sudo systemctl start docker
```

Open the repository folder in VSCode, then press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (or <kbd>Shift</kbd> + <kbd>Command</kbd> + <kbd>P</kbd> in Mac) and select `Dev Containers: Rebuild container`.

And that is all, only you need to wait for the build, and after you can access the terminal in the container from VSCode.

<br>

## Extensions within the devcontainer.
| Name | Unique Identifier |
| ------ | ------ |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | `dbaeumer.vscode-eslint` |
| [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=znck.vue) | `znck.vue` |
| [Vue](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) | `naumovs.color-highlight` |
| [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) | `octref.vetur` |
| [Vue Language Features](https://marketplace.visualstudio.com/items?itemName=vue.volar) | `vue.volar` |
| [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | `christian-kohler.npm-intellisense` |
| [Tailwind CSS Intellisense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) | `bradlc.vscode-tailwindcss` |
| [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | `eamodio.gitlens` |
| [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | `esbenp.prettier-vscode` |

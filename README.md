<p align="center">
    <a href="https://github.com/robinwalterfit/editorjs-plugins">
        <img height="128" src="https://github.com/robinwalterfit/editorjs-plugins/">
        <h1 align="center">Editor.js Plugins</h1>
    </a>
</p>

This monorepo provides different plugins for [Editor.js](https://editorjs.io/)
to combine it with other great projects.

-   [MUI](https://mui.com/): you've built an amazing app with the MUI framework
    and want to integrate Editor.js for convenient content creation? This project
    got you covered, try out the [editorjs-plugin-mui](https://github.com/robinwalterfit/editorjs-plugins/tree/main/packages/editorjs-plugin-mui).

<p align="center">
    <a aria-label="License" href="https://github.com/robinwalterfit/editorjs-plugins/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/github/license/robinwalterfit/editorjs-plugins?style=for-the-badge">
    </a>
    <a aria-label="Commitizen friendly" href="http://commitizen.github.io/cz-cli/">
        <img alt="Commitizen friendly" src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=for-the-badge">
    </a>
</p>

-   [Developing](#developing)
    -   [Building](#building)
-   [Features](#features)
-   [Contributing](#contributing)
-   [Links](#links)
-   [Licensing](#licensing)

## Developing

To contribute to the project open up a terminal and run the following commands:

```shell
git clone https://github.com/robinwalterfit/editorjs-plugins.git
cd editorjs-plugins/
pnpm install
```

The first command clones the project into your current directory. Then changes
into the project directory and last but not least installs all dependencies
that are needed for development.

### Building

This project uses [pnpm](https://pnpm.io/) as a package manager and to manage
this monorepo. There are different ways to build this project.

First it's possible to build every package individually, e.g. editorjs-plugin-mui:

```shell
cd packages/editorjs-plugin-mui
pnpm run generate
```

This way only the `editorjs-plugin-mui` package will be built.

It's also possible to build all packages at once by just running the following
command in the root project folder:

```shell
pnpm run generate
```

The difference is that this will invoke the `do:build` script in all packages
(if it is defined).

## Features

With the help of this project it's possible to extend the functionality of
Editor.js in the following ways:

-   MUI:
    -   [ ] Typography

## Contributing

You want to contribute to `editorjs-plugins`? Great! Please make sure to read
`CONTRIBUTING.md` first.

## Links

-   Project homepage: https://robinwalterfit.github.io/editorjs-plugins
-   Repository: https://github.com/robinwalterfit/editorjs-plugins
-   Issue tracker: https://github.com/robinwalterfit/editorjs-plugins/issues
    -   In case of sensitive bugs like security vulnerabilities, please contact
        hello@robinwalter.me directly instead of using issue tracker. We value your
        effort to improve the security and privacy of this project!
-   Related projects:
    -   Editor.js: https://github.com/codex-team/editor.js
    -   Awesome Editor.js: https://github.com/editor-js/awesome-editorjs
    -   MUI: https://github.com/mui/material-ui

## Licensing

The code in this project is licensed under Apache-2.0.

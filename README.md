# Nextron TypeScript Template

## Description

### What is Nextron?

[Nextron](https://github.com/saltyshiomix/nextron) is a framework for building desktop applications with Electron and Next.js. With Nextron, you can use all the features of Next.js, such as server-side rendering and code splitting, in your Electron app. Nextron also provides a development environment that enables you to develop your app with hot reloading. It also provides a way to use [TypeScript](https://github.com/microsoft/TypeScript) in your app and an easy way to build your app for distribution.

For more information, see the official [Nextron documentation](https://github.com/saltyshiomix/nextron) and the [repository](https://github.com/saltyshiomix/nextron).

### What is this template?

This template is a boilerplate for building desktop applications with Nextron. It includes the following features:

- [TypeScript](https://github.com/microsoft/TypeScript) support.
- [Tailwind CSS](https://tailwindcss.com/) for styling.
- [File Structure](#file-structure) already set up.
- [Electron Builder](https://www.electron.build/configuration/configuration) for building your app for distribution.
- [Next.js](https://nextjs.org/) for server-side rendering and code splitting.

> **Note**: The renderer (nextjs) file structure is configured for my personal preference. The initial structure is the same as the one created by nextron tailwindcss example.

### File Structure

```bash
.
├── main/       # Main process code
├── renderer/   # Renderer process code (Next.js)
└── resources/  # Resources for your app
```

## Development

### Install dependencies

```bash
# with npm
npm install

# with yarn
yarn
```

### Run development

```bash
# with npm
npm run dev

# with yarn
yarn dev
```

### Build

```bash
# with npm
npm run build

# with yarn
yarn build
```

> **Note**: For the build you can select the platform you want, all the options are in the [package.json](package.json) file.

## License

This project is licensed under the terms of the [MIT license](./LICENSE).

# alt:V TypeScript Starter

The goal of this project is to provide a minimal base for alt:V projects. This project aims to minimize boilerplate code, build time and finally valuable development time.

### Features
- 💆 Zero configuration (thanks to [Parcel](https://github.com/parcel-bundler/parcel))
- 👌 Typings included (client, server, natives)
- ⚡ The fastest bundle times (multi-core compilation, filesystem cache and more)
- 📦 Out of the box support for HTML and CSS
- ✨ Built-in Support for CSS pre-processors (LESS, Stylus, [or install SASS](#installing-sass-scss-support))

---

## Getting started

Getting started with this starter project couldn't be easier. It consists of a single step:
```bash
# Yarn
yarn install

# NPM
npm install
```

## Build your resource

Building your resource also requires only a single command:
```bash
# Yarn
yarn build

# NPM
npm run build
```

You can also build the client and server resources seperately:
```bash
# Yarn
yarn build:client
yarn build:server

# NPM
npm run build:client
npm run build:server
```

## Installing SASS (SCSS support)<a href="installingSass"></a>

To add support for SASS/SCSS, you simply have to install the SASS package:

`yarn add -D sass`

Parcel will take care of the rest. That means: No configuration required 🎉

## ToDo
- TSLint
- CLI
- [*I'm open to suggestions*](https://github.com/leNicDev/altv-typescript-starter/issues/new)
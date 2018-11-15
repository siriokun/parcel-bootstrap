<p align="center">
  <a class="header-logo-invertocat" href="https://parceljs.org/">
    <img alt="Parcel" src="https://user-images.githubusercontent.com/19409/31321658-f6aed0f2-ac3d-11e7-8100-1587e676e0ec.png" height="150">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a class="header-logo-invertocat" href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/docs/4.1/assets/brand/bootstrap-solid.svg" alt="Bootstrap" height="150">
  </a>
</p>

## Features

- 🚀 **Blazing fast** bundle times - multicore compilation, and a filesystem cache for fast rebuilds even after a restart.
- 📦 Out of the box support for JS, CSS, HTML, file assets, and more - **no plugins to install**.
- 🐠 **Automatically transforms modules** using Babel, PostCSS, and PostHTML when needed - even `node_modules`.
- ✂️ Zero configuration **code splitting** using dynamic `import()` statements.
- 🔥 Built in support for **hot module replacement**
- 🚨 Friendly error logging experience - syntax highlighted code frames help pinpoint the problem.
- 🅱 **Bootstrap 4** - Sleek, intuitive, and powerful front-end framework for faster and easier web development.

## For Development

1.  Install with yarn:

```shell
yarn global add parcel-bundler
```

2.  Parcel has a development server built in, which will automatically rebuild your app as you change files and supports hot module replacement for fast development.

```shell
yarn dev
```
It will open http://localhost:1234/ in your browser.

## For Production

1.  Close current `yarn dev` with Ctrl+C then run :

```shell
yarn build
```

2. Now you have working static files inside `dist` folder ready for real world 🎉✨

## License

Code released under the [MIT License](LICENSE).

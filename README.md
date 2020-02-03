# Jungle

A custom theme for [Ghost](http://github.com/tryghost/ghost/). This is the latest development version of Jungle. If you're just looking to download the latest release, head over to the [releases](https://github.com/florianschmidt1994/ghost-theme-jungle/releases) page.

&nbsp;

![screenshot-desktop](https://user-images.githubusercontent.com/6798306/73660366-55ff7600-4698-11ea-8eb3-6fed4c105211.png)

&nbsp;

# Development

Casper styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
$ yarn install
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
$ yarn zip
```

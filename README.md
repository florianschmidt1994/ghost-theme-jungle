<p align="center">
<img 
  src="https://user-images.githubusercontent.com/6798306/73664385-96162700-469f-11ea-80b1-3bacb2583462.png" 
  alt="logo"
  width=200
  height=200>
</img>
</p>
<h1 align="center">Jungle</h1>
<p align="center"><a href="https://github.com/florianschmidt1994/ghost-theme-jungle/releases">Download</a> | <a href="https://florianschmidt.me/">Demo</a></p>

A custom theme for [Ghost](http://github.com/tryghost/ghost/). This is the latest development version of Jungle. If you're just looking to download the latest release, head over to the [releases](https://github.com/florianschmidt1994/ghost-theme-jungle/releases) page. See a live version of this theme on my [personal website](https://florianschmidt.me)

# Preview
<p align="center">
<img width=500 src="https://user-images.githubusercontent.com/6798306/73660366-55ff7600-4698-11ea-8eb3-6fed4c105211.png" alt="A screenshot of the theme"></img>
</p>

# How to use this theme
This theme supports having separate overview pages for both projects (i.e. portfolio) and a blog page. The blog can be found at `yourghostblog.tld/blog` and the projects can be found at `yourghostblog.tld/projects`.

!! For this to work you need to create two blank pages in your ghost admin panel. One has to be named "blog" and one has to be named "projects". None of the content on these pages will be displayed and an overview of your blog articles or projects will be injected instead !!


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

A custom theme for [Ghost](http://github.com/tryghost/ghost/). This is the latest development version of Jungle. If you're just looking to download the latest release, head over to the [releases](https://github.com/florianschmidt1994/ghost-theme-jungle/releases) page. See a live version of this theme on my [personal website](https://florianschmidt.me)

# Attributions
- The icons are adapted from icons made by smashicons on flaticon.cc
- The theme is based on the Ghost Casper Theme

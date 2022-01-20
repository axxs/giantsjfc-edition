# Giants JFC Theme

Go check out the [Giants Junior Football Club](http://giantsjfc.com.au) 

Based off the Edition theme for [Ghost](http://github.com/tryghost/ghost/). This is the latest development version of Giants JFC theme! If you're just looking to download the latest release, download the theme [here](https://github.com/axxs/giantsjfc-edition/archive/refs/heads/master.zip).

&nbsp;

# Development

Giants JFC styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
# create .zip file
yarn zip
```

# PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.

# Copyright & License

Edition code is Copyright (c) 2013-2022 Ghost Foundation and Released under the [MIT license](LICENSE).

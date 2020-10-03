# Fast ⚡️
### Develop, build, deploy, redeploy, and teardown frontend projects fast ⚡️.

## ⬇️ Get Fast.
To get fast, [clone](https://github.com/reblim/fast.git) or [download](https://github.com/reblim/fast/archive/main.zip) the repository.

## 📖 About Fast.
With so many frontend technologies available nowadays, sometimes it may feel a bit cumbersome to get started with a project.

**Fast** aims to alleviate this by providing a simple, yet powerful boilerplate, to get you started with any frontend project.

With fast, you can `develop`, `build`, `deploy`, `redeploy`, and `teardown` frontend projects fast, **really fast ⚡️**.

## 💾 Core technologies.
At the core, **Fast** uses [Normalize.css](https://necolas.github.io/normalize.css/), [PostCss](https://postcss.org/), [Sass](https://sass-lang.com/), [Babel](https://babeljs.io/), [Parcel](https://parceljs.org/), and [Surge](https://surge.sh/).

### Normalize.css.
[Normalize.css](https://necolas.github.io/normalize.css/) makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing.

### PostCSS.
We use [Autoprefixer](https://github.com/postcss/autoprefixer#readme), a [PostCSS](https://postcss.org/) plugin to parse CSS and add vendor prefixes to CSS rules using values from Can I Use. It is recommended by Google and used in Twitter and Alibaba. This allows you to write your CSS rules without vendor prefixes.

### Sass.
We use Node-sass, a library that provides binding for Node.js to LibSass, the C version of the popular stylesheet preprocessor, [Sass](https://sass-lang.com/). It allows you to natively compile `.scss` files to CSS at incredible speed and automatically via a connect middleware.

### Babel.
We use [Babel](https://babeljs.io/) with [@babel/preset-env](https://babeljs.io/docs/en/babel-preset-env), a smart preset that allows you to use the latest JavaScript without needing to micromanage which syntax transforms (and optionally, browser polyfills) are needed by your target environment(s). This both makes your life easier and JavaScript bundles smaller!

### Parcel.
We use [Parcel](https://parceljs.org/) for Blazing fast bundle times. [Parcel](https://parceljs.org/) uses worker processes to enable multicore compilation and has a filesystem cache for fast rebuilds even after a restart.

### Surge.
We use [Surge](https://surge.sh/) for fast and simple, static web publishing through a single command. [Surge](https://surge.sh/) allows you to deploy, update deploys (redeploy), and teardown your frontend projects in just a few seconds using default or custom domains for free.

## License.
[MIT License](LICENSE)

Copyright (c) 2020 Milber Ferreira

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

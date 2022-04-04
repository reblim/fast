# **Fast** ⚡️

### Develop, build, deploy, redeploy, and teardown frontend projects fast ⚡️.

![This is Fast](https://ph-files.imgix.net/7e2b9781-81b1-422c-8112-4e3469c7d1d7.gif 'This is Fast explainer')

## ❤️ Become a sponsor.

[![Become a sponsor](https://i.ibb.co/CJxDLSf/fast-donate-QR-code.png?raw=true 'Become a sponsor')](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9X7WHKVVBLEYC)

## 📖 About Fast.

With so many frontend technologies available nowadays, sometimes it may feel a bit cumbersome to get started with a project.

**Fast** aims to alleviate this by providing a simple, yet powerful boilerplate, to get you started with any frontend project.

With Fast, you can `develop`, `build`, `deploy`, `redeploy`, and `teardown` frontend projects fast, **really fast ⚡️**.

## ⬇️ Get Fast.

To get fast, [clone](https://github.com/reblim/fast.git) or [download](https://github.com/reblim/fast/archive/main.zip) the repository.

## 🚏 Use Fast.

Using **Fast** is super simple. Simply `open the Fast folder` using your favorite code editor and install the necessary dependencies.

**Note:** _**Fast** uses [Yarn](https://yarnpkg.com/) for fast, reliable, and secure dependency management but feel free to use [NPM](https://www.npmjs.com/) if you prefer._

### ⚠️ Are you on Windows?

**Replace all instances of `$npm_execpath` in the [package.json](package.json) file with:**

```
%npm_execpath%
```

### Installing the necessary dependencies.

**Using Yarn:**

```
yarn
```

or

```
yarn install
```

**Using NPM:**

```
npm install
```

That's it! Now you are ready to start developing your awesome project 😎

## 💻 Start developing.

To start developing, run:

**Using Yarn:**

```
yarn start
```

or

```
yarn serve
```

**Using NPM:**

```
npm run start
```

or

```
npm run serve
```

The `start` script will start the server using the default port `3000`. However, you will have to manually open your default browser on [`http://localhost:3000/`](http://localhost:3000/).

The `serve` script will start the server and open your default browser on [`http://localhost:3000/`](http://localhost:3000/).

**Note:** _If you would like to run the server on a different port, simply update the port `3000` provided in the start script to the port of your preference._

## 🏗 Build for production.

If you would like to `build` the project to use your own deployment pipeline, you can run the build command:

**Using Yarn:**

```
yarn build
```

**Using NPM:**

```
npm run build
```

## 🚀 Deploy your project.

Deploying your project couldn't be easier! Thanks to [Surge](https://surge.sh/), you can deploy your entire project to your custom domain, or to a free `surge.sh` sub-domain e.g. `your-awesome-project.surge.sh`.

**Note:** _To deploy to a custom domain, read [Surge's documentation](https://surge.sh/help/adding-a-custom-domain)._

To deploy your project, run:
**Using Yarn:**

```
yarn deploy
```

**Using NPM:**

```
npm run deploy
```

...and follow the command-line instructions. It's that easy!

## 🏁 Redeploy your project.

If you made further changes and need to redeploy your project, simply run `yarn redeploy` providing the deployment URL as the last argument to the command, like so:

**Using Yarn:**

```
yarn redeploy your-awesome-project.surge.sh
```

or _(if using a custom domain)_

```
yarn redeploy your-custom-domain.com
```

**Using NPM:**

```
npm run redeploy your-awesome-project.surge.sh
```

or _(if using a custom domain)_

```
npm run redeploy your-custom-domain.com
```

## ⚰️ Tear down your project.

There is a time when all projects must come to an end.

To tear down your project, run:

**Using Yarn:**

```
yarn teardown your-awesome-project.surge.sh
```

or _(if using a custom domain)_

```
yarn teardown your-custom-domain.com
```

**Using NPM:**

```
npm run teardown your-awesome-project.surge.sh
```

or _(if using a custom domain)_

```
npm run teardown your-custom-domain.com
```

## 🚧 Custom 404 page.

[Surge](https://surge.sh/) also allows you to [add a custom 404 – Not Found page](https://surge.sh/help/adding-a-custom-404-not-found-page).

You can override Surge’s default 404 – Not Found page with your own, completely custom one by **simply adding a 404.html file in the root of your project**.

## 💾 Core technologies.

At the core, **Fast** uses [Parcel](https://parceljs.org/), [Surge](https://surge.sh/), [Normalize.css](https://necolas.github.io/normalize.css/), [Sass](https://sass-lang.com/), and [Babel](https://babeljs.io/).

### Parcel.

**Fast** uses [Parcel](https://parceljs.org/) for Blazing fast bundle times. [Parcel](https://parceljs.org/) uses worker processes to enable multicore compilation and has a filesystem cache for fast rebuilds even after a restart. **Parcel** uses [Autoprefixer](https://github.com/postcss/autoprefixer#readme), a [PostCSS](https://postcss.org/) plugin to parse CSS and add vendor prefixes to CSS rules using values from Can I Use. It is recommended by Google and used in Twitter and Alibaba. This allows you to write your CSS rules without vendor prefixes.

**Note:** If your project needs to support older browsers, simply update the `browserslist` declaration in the [package.json](package.json) file to your desired configuration, and both [Babel](https://babeljs.io/) and [PostCSS's](https://postcss.org/) [Autoprefixer](https://github.com/postcss/autoprefixer#readme) will update to provide the necessary transformations through [Parcel](https://parceljs.org/).

### Surge.

**Fast** uses [Surge](https://surge.sh/) for fast and simple, static web publishing through a single command. [Surge](https://surge.sh/) allows you to deploy, update deploys (redeploy), and teardown your frontend projects in just a few seconds using default or custom domains for free.

### Normalize.css.

[Normalize.css](https://necolas.github.io/normalize.css/) makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing.

### Sass.

**Fast** uses Node-sass, a library that provides binding for Node.js to LibSass, the C version of the popular stylesheet preprocessor, [Sass](https://sass-lang.com/). It allows you to natively compile `.scss` files to CSS at incredible speed and automatically via a connect middleware.

### Babel.

**Fast** uses [Babel](https://babeljs.io/) with [@babel/preset-env](https://babeljs.io/docs/en/babel-preset-env) through [Parcel's](https://parceljs.org/) default configuration, which is triggered based on the `browserslist` declaration in the [package.json](package.json) file. [@babel/preset-env](https://babeljs.io/docs/en/babel-preset-env) is a smart preset that allows you to use the latest JavaScript without needing to micromanage which syntax transforms (and optionally, browser polyfills) are needed by your target environment(s). This both makes your life easier and JavaScript bundles smaller!

## 🚨 Found issues?

[Please create a ticket.](https://github.com/reblim/fast/issues)

## 🎗 Would you like to contribute?

[Read the Contributing Guidelines](https://github.com/reblim/fast/blob/main/.github/CONTRIBUTING.md).

[Report an issue](https://github.com/reblim/fast/issues).

[Create a pull request](https://github.com/reblim/fast/pulls).

[Become a sponsor ❤️](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9X7WHKVVBLEYC)

## 🙌 Credits.

Thank you to [all our contributors](https://github.com/reblim/fast/graphs/contributors).

## 👩‍⚖️ License.

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

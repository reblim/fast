# Fast ⚡️
### Develop, build, deploy, redeploy, and teardown frontend projects fast ⚡️.

## Get fast.
To get fast, [clone](https://github.com/reblim/fast.git) or [download](https://github.com/reblim/fast/archive/main.zip) the repository.

## About fast.
With so many frontend technologies available nowadays, sometimes it may feel a bit cumbersome to get started with a project.

Fast aims to alleviate this by providing a simple, yet powerful boilerplate, to get you started with any frontend project.

With fast, you can develop, build, deploy, redeploy, and teardown frontend projects fast, really fast.

## Core technologies.
At the core, Fast uses Normalize.css, PostCss, Sass, Babel, Parcel, and Surge.

### Normalize.css.
Normalize.css makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing.

### PostCSS.
We use Autoprefixer, a PostCSS plugin to parse CSS and add vendor prefixes to CSS rules using values from Can I Use. It is recommended by Google and used in Twitter and Alibaba. This allows you to write your CSS rules without vendor prefixes.

### Sass.
We use Node-sass, a library that provides binding for Node.js to LibSass, the C version of the popular stylesheet preprocessor, Sass. It allows you to natively compile .scss files to CSS at incredible speed and automatically via a connect middleware.

### Babel.
We use Babel with @babel/preset-env, a smart preset that allows you to use the latest JavaScript without needing to micromanage which syntax transforms (and optionally, browser polyfills) are needed by your target environment(s). This both makes your life easier and JavaScript bundles smaller!

### Parcel.
We use Parcel for Blazing fast bundle times. Parcel uses worker processes to enable multicore compilation and has a filesystem cache for fast rebuilds even after a restart.

### Surge.
We use Surge for fast and simple, static web publishing through a single command. Surge allows you to deploy, update deploys (redeploy), and teardown your frontend projects in just a few seconds using default or custom domains for free.

<p align="center">
  <a href="https://cdn.itwcreativeworks.com/assets/itw-creative-works/images/logo/itw-creative-works-brandmark-black-x.svg">
    <img src="https://cdn.itwcreativeworks.com/assets/itw-creative-works/images/logo/itw-creative-works-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/itw-creative-works/itwcw-package-analytics.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/itwcw-package-analytics.svg">
  <img src="https://img.shields.io/bundlephobia/min/itwcw-package-analytics.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/itw-creative-works/itwcw-package-analytics.svg">
  <img src="https://img.shields.io/npm/dm/itwcw-package-analytics.svg">
  <img src="https://img.shields.io/node/v/itwcw-package-analytics.svg">
  <img src="https://img.shields.io/website/https/itwcreativeworks.com.svg">
  <img src="https://img.shields.io/github/license/itw-creative-works/itwcw-package-analytics.svg">
  <img src="https://img.shields.io/github/contributors/itw-creative-works/itwcw-package-analytics.svg">
  <img src="https://img.shields.io/github/last-commit/itw-creative-works/itwcw-package-analytics.svg">
  <br>
  <br>
  <a href="https://itwcreativeworks.com">Site</a> | <a href="https://www.npmjs.com/package/itwcw-package-analytics">NPM Module</a> | <a href="https://github.com/itw-creative-works/itwcw-package-analytics">GitHub Repo</a>
  <br>
  <br>
  <strong>itwcw-package-analytics</strong> is the official npm module of <a href="https://itwcreativeworks.com">ITWCW Prepare Package</a>, a free app for creating custom text snippets that you can access on all of your devices!
</p>

## 🌐 ITWCW Prepare Package Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## 🦄 Features
* Getting proxy lists

## 🔑 Getting an API key
You can use so much of `itwcw-package-analytics` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a ITWCW Prepare Package account](https://itwcreativeworks.com/signup).

## 📦 Install ITWCW Prepare Package
### Option 1: Install via npm
Install with npm if you plan to use `itwcw-package-analytics` in a Node project or in the browser.
```shell
npm install itwcw-package-analytics
```
If you plan to use `itwcw-package-analytics` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const itwcw-package-analytics = new (require('itwcw-package-analytics'))({
  // Not required, but having one removes limits (get your key at https://itwcreativeworks.com).
  apiKey: 'api_test_key'
});
```

### Option 2: Install via CDN
Install with CDN if you plan to use ITWCW Prepare Package only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/itwcw-package-analytics@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var itwcw-package-analytics = new ITWCWPreparePackage({
    // Not required, but having one removes limits (get your key at https://itwcreativeworks.com).
    apiKey: 'api_test_Key'
  });
</script>
```

### Option 3: Use without installation
You can use `itwcw-package-analytics` in a variety of ways that require no installation, such as `curl` in terminal/shell.

```shell
# Standard
curl -X POST https://api.itwcreativeworks.com
```

## ⚡️ Usage
### itwcw-package-analytics.run(options)
```js
itwcw-package-analytics.run(options);
```

## 📘 Using ITWCW Prepare Package
After you have followed the install step, you can start using `itwcw-package-analytics` to create custom text snippets that you can access on all of your devices

For a more in-depth documentation of this library and the ITWCW Prepare Package service, please visit the official ITWCW Prepare Package website.

## 📝 What Can ITWCW Prepare Package do?
ITWCW Prepare Package is a free text snippet manager that lets you [create custom text snippets](https://itwcreativeworks.com) that you can access on all of your devices!

## 🗨️ Final Words
If you are still having difficulty, we would love for you to post
a question to [the ITWCW Prepare Package issues page](https://github.com/itw-creative-works/itwcw-package-analytics/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## 📚 Projects Using this Library
* [ITW Creative Works](https://itwcreativeworks.com)
* [Somiibo](https://somiibo.com)
* [Slapform](https://slapform.com)
* [StudyMonkey](https://studymonkey.ai)
* [DashQR](https://dashqr.com)
* [Replyify](https://replyify.app)
* [SoundGrail](https://soundgrail.com)
* [Trusteroo](https://trusteroo.com)

Ask us to have your project listed! :)

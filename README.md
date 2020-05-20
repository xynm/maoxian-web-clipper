
# MaoXian Web Clipper

[Home Page](https://mika-cn.github.io/maoxian-web-clipper/index.html)

## Intro

MaoXian Web Clipper is a browser extension to clip information from web page and save it to your **local machine** to avoid information invalidation.

That's it, Not bored registration, Not charged.


## Features

* Local Storage - All file will save in local hard disk, you can control your data totally (e.g. Use dropbox to sync files)
* Free Selection - You can select which area you want to clip.
* Adjust Focus - After you focus a area, you can adjust your selection use hotkeys.
* Category And Tag - Before your clipping, you can change title, input category and some tags.
* Clipping History - Extension will record clipping history, and support search history (through title/category/tag).
* Reset History - When you install this extension in new computer, you can reset your clipping history

## Software Preview
* [screenshots](https://mika-cn.github.io/maoxian-web-clipper/screenshots.html)

## Install

* Firefox - [https://addons.mozilla.org/en-US/firefox/addon/maoxian-web-clipper/](https://addons.mozilla.org/en-US/firefox/addon/maoxian-web-clipper/)
* Chrome - [https://chrome.google.com/webstore/detail/maoxian-web-clipper/kjahokgdcbohofgdidndeiaigkehdjdc](https://chrome.google.com/webstore/detail/maoxian-web-clipper/kjahokgdcbohofgdidndeiaigkehdjdc)
* Chrome - [install by crx](https://mika-cn.github.io/maoxian-web-clipper/chrome-install-by-crx.html)

## Get involved

You should create your own branch from develop and send a pull request back to it.

1. install dependencies

```shell
npm install
```

2. run the project


**Developing**

```shell
npm run watch
```

This command do three things. First, Compile the project. Second, watch the project's code modification and automatically compile it. Third, auto reload MaoXian that had been installed on browser.

All compiled code will placed in `dist/extension/maoxian-web-clipper`. After running this command, you need to install MaoXian into your browser.

If you use Chrome(or Chromium) to developing.

* Go to extensions page(by visit url: `chrome://extensions/`)
* Enable developer mode
* Load unpacked(select `dist/extension/maoxian-web-clipper`)

If you use Firefox to developing.

* Go to debugging page(by visit url: `about:debugging`)
* Check _Enable add-on debugging_
* Load Temporary Add-on(select `dist/extension/maoxian-web-clipper`)

**Testing**

```shell
npm test
```

## Third party library

Thanks to these awesome libraries for making MaoXian's development become easier.

* [webextension-polyfill](https://github.com/mozilla/webextension-polyfill)
* [JavaScript-MD5](https://github.com/blueimp/JavaScript-MD5)
* [i18njs](http://i18njs.com/)
* [turndown](https://github.com/domchristie/turndown)
* [turndown-plugin-gfw](https://github.com/domchristie/turndown-plugin-gfm)
* [mathml2latex](https://github.com/mika-cn/mathml2latex)
* [strip-css-comments](https://github.com/sindresorhus/strip-css-comments)
* [awesomplete](https://github.com/LeaVerou/awesomplete)
* [pikaday](https://github.com/Pikaday/Pikaday)


## Contribution
You could help MaoXian Web Clipper development in many ways.

* [Sending feedback and suggestion](https://github.com/mika-cn/maoxian-web-clipper/issues).
* Spread and promote this extension to your friend. Popularity is a strong power to drive developers.
* If you're software developer, pull requests are welcome.

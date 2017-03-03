# Awesome WebExtensions [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 

> A curated list of awesome resources for [WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) development.

WebExtensions are a cross-browser system for developing browser add-ons. To a large extent the system is compatible with the [extension API](https://developer.chrome.com/extensions) supported by Google Chrome and Opera. Extensions written for these browsers will in most cases run in Firefox or [Microsoft Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/documentation/extensions/) with just [a few changes](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).

## Contents

- [Getting Started](#getting-started)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Tools](#tools)
- [Boilerplates](#boilerplates)
- [Sample Extensions](#sample-extensions)

## Getting started

- [Chrome Extensions documentation](https://developer.chrome.com/extensions)
- [Chrome Extensions API](https://developer.chrome.com/extensions/api_index)
- [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/Add-ons/WebExtensions)
- [Mozilla's WebExtensions implementation status](http://arewewebextensionsyet.com/) - WebExtensions are not yet fully compatible/implemented in Firefox, this helps you see what isn't.
- [Microsoft Edge WebExtension API roadmap](https://docs.microsoft.com/en-us/microsoft-edge/extensions/api-support/extension-api-roadmap)
- [Support for Chrome & WebExtension APIs across Browsers](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs)
- [Guide to port a Chrome Extension to work in Firefox](https://hacks.mozilla.org/2015/10/porting-chrome-extensions-to-firefox-with-webextensions/)

## Libraries and Frameworks

Code meant become part of the extension.

- [webext-options-sync](https://github.com/bfred-it/webext-options-sync) - Helps you manage and autosave your extension's options.
- [webext-inject-on-install](https://github.com/bfred-it/webext-inject-on-install) - Automatically add content scripts to existing tabs when your extension is installed. Chrome + Firefox.
- [chrome-promise](https://github.com/tfoxy/chrome-promise) - Promised version of `chrome.*` callback-style functions.

## Tools

Apps that help you manage your extensions.

- [Chrome Webstore Upload](https://github.com/DrewML/chrome-webstore-upload-cli) - Upload the extension to the Chrome Web Store via cli (or on Travis, automatically).
- [mozilla/Web-ext](https://github.com/mozilla/web-ext) Command line tool to help build, run, and test WebExtensions.
- [Extensionizr](http://extensionizr.com/) - Web UI that helps you create an initial configuration and files.
- [chromepet](https://github.com/ZenHubIO/chromepet) - Get notified when your new version has been published.
- [inline-install](https://github.com/alykoshin/inline-install) - Simplify the installation of the extension directly from your website.
- [wemf](https://github.com/pastak/wemf) - Format and validate `manifest.json`.
- [maniver](https://github.com/ragingwind/maniver) - Bump the extension version via cli.
- [chrome-ext-downloader](https://github.com/jiripospisil/chrome-ext-downloader) - Download any extension on Chrome Web Store to see how they do it.
- [chrome-i18n](https://github.com/Ragnarokkr/chrome-i18n) - Helps build a locales database from some project files.

## Boilerplates

- [extensionizr.com](http://extensionizr.com/) - Basic Boilerplate.
- [generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) - Boilerplate based on gulp & babel.
- [generator-chrome-extension-kickstart](https://github.com/handtrix/generator-chrome-extension-kickstart) - Flexible Boilerplate based on gulp, webpack & babel.
- [react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) - React boilerplate with Hot reloading.

## Sample Extensions

These are simple and modern WebExtensions repositories that could help you figure out where pieces go, including automatic deployment via Travis CI.

- [npm-hub](https://github.com/zeke/npm-hub)
- [Sticky Pinned Tabs](https://github.com/bfred-it/sticky-pinned-tabs)
- [Dim Files on GitHub](https://github.com/bfred-it/dim-files-on-github)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Federico Brigante](http://bfred.it) has waived all copyright and related or neighboring rights to this work.

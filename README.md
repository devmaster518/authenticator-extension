# authenticator-extension

> Authenticator that generates 2-Step Verification codes in your browser built with `vue` + `typescript`

![Google Authenticator App](images/icon128.png)

## Available for Chrome, Firefox, MS Edge and Safari

[<img src="https://raw.githubusercontent.com/wiki/Authenticator-Extension/Authenticator/readme-images/chrome-web-store.png" title="Chrome Web Store" width="170" height="48" />](https://chrome.google.com/webstore/detail/authenticator/bhghoamapcdpbohphigoooaddinpkbai)

## Build Setup

```bash
# install development dependencies
npm install
# compile for chrome
npm run chrome
```

To reproduce a build:

```bash
npm ci
npm run prod
```

## Development (Chrome)

```bash
# install development dependencies
npm install
# compiles the Chrome extension to the `./test/chrome` directory
npm run dev:chrome
# load the unpacked extension from the `./test/chrome/ directory in Chrome
```

### Note that Windows users should download a tool like [Git Bash](https://git-scm.com/download/win) or [Cygwin](http://cygwin.com/) to build.

&copy; 2017 - 2024 @codeguru827

All rights reserved.

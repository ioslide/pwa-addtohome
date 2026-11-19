# PWA_Addtohome

## Just Click to add a PWA application

[![Addtohome](https://forthebadge.com/images/badges/built-with-love.svg)](https://pwa.notredame.xhy.im)
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://pwa.notredame.xhy.im)

## Local preview

```bash
git clone https://github.com/ioslide/pwa-addtohome.git
cd pwa-addtohome
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://localhost:8000/> in your browser. Serve the repository root because
scripts and service worker cache entries use root-relative paths. Service workers
require HTTPS when deployed; localhost can be used for local development.

## Customization

| File | Settings |
| --- | --- |
| `manifest.json` | App name, short name, theme color, start URL, and icons |
| `js/application.js` | Add-to-home-screen prompt options and callbacks |
| `index.html` | Page title, metadata, and Apple touch icons |

The app uses root-relative URLs. When deploying your own version, serve it from
the origin root and update `CNAME` if you use GitHub Pages with a custom domain.

## Browsers support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png" alt="Samsung" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Samsung | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| Edge| last 3 versions| last 3 versions| last 2 versions| last 2 versions| last 3 versions| last 2 versions

## Preview

<div>
	<img src="https://i.loli.net/2019/05/26/5cea44667d0c083212.jpg">
	<img src="https://i.loli.net/2019/05/26/5cea44668baa944978.jpg">
</div>


## License

``` bash

MIT License

Copyright (c) 2019 XHY

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

```

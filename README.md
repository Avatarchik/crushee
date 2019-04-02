# Crushee for Desktop

*An image squisher*

Crushee is an image compression tool, powered by Electron and Node.js. It accepts JPEG, PNG, GIF, SVG, and WebP files, and will output to JPEG, PNG, or WebP. It's useful for batch optimization and resizing images. You can carefully tune your images to meet your needs without having to re-upload or restart every time.

Crushee was primarily built with [Electron](https://electronjs.org/), [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [sharp](https://github.com/lovell/sharp/), and [compress-images](https://github.com/semiromid/compress-images).



## Requirements

- **Node.js** (v10+)

- **libjpeg** (Actual library depends on your OS)

- What what I've experienced, all other image libraries should come pre-built through *npm install*



## Usage

- Download or clone
- Additionally, download the [Crushee server](https://github.com/xanderfrangos/crushee-server) to the *crushee-server* folder. The Crushee server runs along side the Electron app at startup.
- Run *npm install* in both the root folder and *crushee-server*.
- If you're missing any image libraries (depending on your OS), get those and re-run *npm install* as needed
- Run *npm start*



## License

Copyright © 2019 Xander Frangos

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

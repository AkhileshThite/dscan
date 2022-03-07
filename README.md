<p align="center">
    <img align="center" src="/src/img/logo.png" width="150" height="150"></img>
</p>

<h1 align="center">DScan</h1>

<div align="center">
    <img src="https://img.shields.io/badge/extension-DScan-2C80C1" alt="Platform" />
    <img src="https://img.shields.io/github/v/release/akhileshthite/dscan?color=1FC71F" alt="Release version" />
    <img src="https://img.shields.io/badge/contributions-welcome-orange.svg?" alt="Contributions welcome">
</div><br>

DScan allows you to quickly upload files as well as folders to [IPFS](https://ipfs.io/) by using [web3.storage](https://web3.storage/) and get a "decentralized QR code" with IPFS [CID](https://docs.ipfs.io/concepts/content-addressing/). Later you can share the QR code or hosted gateway link with everyone for easy and decentralized file sharing.<br>
For more information, you can read this [blog post](https://dev.to/akhileshthite/dscan-decentralized-qr-code-generator-use-web3-for-file-sharing-2lp8). If you have any queries, then follow this [discussion thread](https://github.com/filecoin-project/community/discussions/410).

## Extension
| <img src="https://unpkg.com/@browser-logos/chrome/chrome_16x16.png" width="16" height="16"> [Chrome](https://www.google.com/chrome/) \| <img src="https://unpkg.com/@browser-logos/brave/brave_16x16.png" width="16" height="16"> [Brave](https://brave.com/) \| <img src="https://unpkg.com/@browser-logos/opera/opera_16x16.png" width="16" height="16"> [Opera](https://www.opera.com/)  \| <img src="https://unpkg.com/@browser-logos/edge/edge_16x16.png" width="16" height="16"> [Edge](https://www.microsoftedgeinsider.com/) |
| ------------- |
| [![Install from Chrome Store](https://ipfs.io/ipfs/QmU4Qm5YEKy5yHmdAgU2fD7PjZLgrYTUUbxTydqG2QK3TT)<br>![](https://img.shields.io/chrome-web-store/users/idpfgkgogjjgklefnkjdpghkifbjenap?label=Chrome%20Web%20Store%20users&style=social)](https://chrome.google.com/webstore/detail/dscan-decentralized-qr-co/idpfgkgogjjgklefnkjdpghkifbjenap) |


## Development
The extension's development code is placed in `/src` folder. manifest.json is in `/public` folder. For webpack settings, follow the `webpack.config.js` file.

1. Install dependencies.

```bash
npm install
```

2. After development of the extension, run the following command. This will create a `production` build.

```bash
npm run build
```

3. Now, the `buidl` will appear in the root directory.

4. Select `Developer mode` in your browser extensions tab.

5. Select `Load unpacked extension` and open the `buidl` folder.

*After every change, run `npm run build` command and it will update `buidl` folder automatically, so you don't have to manualy upload the folder after every change.*

For more information, read the [Webpack docs](https://webpack.js.org/concepts/) and the [Chrome Extension docs](https://developer.chrome.com/docs/extensions/mv3/getstarted/).

## Contribute
* Thanks for your interest in contributing to DScan. There are many ways you can contribute to the project.
* To start, take a few minutes to read the "[contribution guide](https://github.com/buidltools/dscan/blob/main/.github/CONTRIBUTING.md)".
* We look forward to your [pull requests](https://github.com/buidltools/dscan/pulls) and / or involvement in our [issues page](https://github.com/buidltools/dscan/issues).


## License
DScan is licensed under the [MIT License](https://github.com/buidltools/dscan/blob/main/LICENSE).


<hr>
Don't forget to leave a star ⭐️ ~ <a href="https://twitter.com/buidltools" target="_blank"><img src="https://img.shields.io/twitter/follow/buidltools?style=social" alt="twitter" /></a>


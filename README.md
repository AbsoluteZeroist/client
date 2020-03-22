# Aragon <a href="https://aragon.org/"><img align="right" src="https://github.com/aragon/design/blob/master/readme-logo.png" height="80px" /></a>

[![Build Status](https://travis-ci.org/aragon/aragon.svg?branch=master)](https://travis-ci.org/aragon/aragon)
[![All Contributors](https://img.shields.io/badge/all_contributors-36-orange.svg?style=flat-square)](#contributors)

**🌎🚀 Trusted by over 1000 organizations, securing more than $20MM in funds. [Try it out.](https://mainnet.aragon.org)**

<a href="https://mainnet.aragon.org/#/a1/"><img src=".github/screenshot.png" /></a>

- 📚 Read the [User Guide](https://help.aragon.org/) first, if you have any questions as a user.
- 💻 You may be interested in [Aragon Desktop](https://github.com/aragon/aragon-desktop/), the most decentralized Aragon experience to date.
- 🏗 If you'd like to develop an Aragon app, please visit the [Aragon Developer Portal](https://hack.aragon.org).
- 📝 Please report any issues and feedback in the [Aragon Client channel](https://spectrum.chat/aragon/aragon-client).
- 🔧 For technical stuff, use this project's [issues](http://github.com/aragon/aragon/issues) or join the technical conversation in our [Developer hangout](https://spectrum.chat/aragon/general-development) channel.
- 📖 To learn more about contributing to the Aragon client itself, please check the [contributing guide](./CONTRIBUTING.md)
- 🚢 For an overview of what changed with each release, check the [releases](https://github.com/aragon/aragon/releases) and [changelog](https://github.com/aragon/aragon/blob/master/CHANGELOG.md).

## Quick start

`npm start` will launch the app, configured to connect to our Rinkeby deployment.

For connecting to other chains / deployments, a few useful npm scripts are provided:

- Mainnet: `npm run start:mainnet` will launch the app, configured to connect to our mainnet deployment
- Local development: `npm run start:local` will launch the app, configured to connect to our [aragen](https://github.com/aragon/aragen) local development environment. It will also use the local IPFS daemon, if it detects one exists. If you're using the [aragonCLI](http://github.com/aragon/aragon-cli), you'll want to run this to connect to its local chain.

**Note**: Windows users may need to install the [windows-build-tools](https://www.npmjs.com/package/windows-build-tools) before installing this project's dependencies.

More [configuration options](docs/CONFIGURATION.md) are available, and depending on your needs, you may find the [frontend development setup guide](docs/FRONTEND_SETUP.md) helpful.

## Deployments

The Aragon client undergoes a number of different deployments, based on build environments, major release timelines, and quality assurance checks.

### aragonPM

Regular updates, with incrementing minor or patch versions, are published onto the `aragon.aragonpm.eth` repo on all supported Ethereum environments.

These should be seen as "official" builds, whose distributions are secured by IPFS. Most users will likely see this version of the app, due to [mainnet.aragon.org](https://mainnet.aragon.org) and [rinkeby.aragon.org](https://rinkeby.aragon.org) pointing to these builds.

### Nightly / Per-PR builds

Automatic [nightly.aragon.org](https://nightly.aragon.org) and [nightly-rinkeby.aragon.org](https://nightly-rinkeby.aragon.org) deployments will occur for each PR and merge to master through [Now](https://zeit.co/now). These are useful for quickly testing a new feature, change, or hotfix.

The official [Now app for Github](https://zeit.co/github) is set up to publish nightlies against Rinkeby see [default Now configuration](./now.json). Travis is set up to publish nightlies against mainnet (see [mainnet Now configuration](./now-mainnet.json)).

## Contributing

#### 👋 Get started contributing with a [good first issue](https://github.com/aragon/aragon/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

**🎓 You may be interested in the [Aragon client architecture guide](./docs/ARCHITECTURE.md) if you're not familiar with how the project is set up.**

Don't be shy to contribute even the smallest tweak. 🐲 There are still some dragons to be aware of, but we'll be here to help you get started!

For other details about contributing to Aragon, more information is available in the [contributing guide](./CONTRIBUTING.md).

#### Issues

If you come across an issue with Aragon, do a search in the [Issues](https://github.com/aragon/aragon/issues?utf8=%E2%9C%93&q=is%3Aissue) tab of this repo and the [Aragon Apps Issues](https://github.com/aragon/aragon-apps/issues?utf8=%E2%9C%93&q=is%3Aissue) to make sure it hasn't been reported before. Follow these steps to help us prevent duplicate issues and unnecessary notifications going to the many people watching this repo:

- If the issue you found has been reported and is still open, and the details match your issue, give a "thumbs up" to the relevant posts in the issue thread to signal that you have the same issue. No further action is required on your part.
- If the issue you found has been reported and is still open, but the issue is missing some details, you can add a comment to the issue thread describing the additional details.
- If the issue you found has been reported but has been closed, you can comment on the closed issue thread and ask to have the issue reopened because you are still experiencing the issue. Alternatively, you can open a new issue, reference the closed issue by number or link, and state that you are still experiencing the issue. Provide any additional details in your post so we can better understand the issue and how to fix it.

#### Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://pierre.world/"><img src="https://avatars2.githubusercontent.com/u/36158?v=4" width="75px;" alt=""/><br /><sub><b>Pierre Bertet</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=bpierre" title="Code">💻</a></td>
    <td align="center"><a href="http://キタ.moe"><img src="https://avatars2.githubusercontent.com/u/4166642?v=4" width="75px;" alt=""/><br /><sub><b>Brett Sun</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=sohkai" title="Code">💻</a></td>
    <td align="center"><a href="http://AquiGorka.com"><img src="https://avatars3.githubusercontent.com/u/3072458?v=4" width="75px;" alt=""/><br /><sub><b>Gorka Ludlow</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=AquiGorka" title="Code">💻</a></td>
    <td align="center"><a href="http://izqui.me"><img src="https://avatars3.githubusercontent.com/u/447328?v=4" width="75px;" alt=""/><br /><sub><b>Jorge Izquierdo</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=izqui" title="Code">💻</a></td>
    <td align="center"><a href="http://aragon.org"><img src="https://avatars0.githubusercontent.com/u/718208?v=4" width="75px;" alt=""/><br /><sub><b>Luis Iván Cuende</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=luisivan" title="Code">💻</a> <a href="#design-luisivan" title="Design">🎨</a> <a href="#ideas-luisivan" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://notbjerg.me"><img src="https://avatars0.githubusercontent.com/u/8862627?v=4" width="75px;" alt=""/><br /><sub><b>Oliver</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=onbjerg" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/bingen"><img src="https://avatars0.githubusercontent.com/u/701095?v=4" width="75px;" alt=""/><br /><sub><b>ßingen</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=bingen" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://2color.me"><img src="https://avatars1.githubusercontent.com/u/1992255?v=4" width="75px;" alt=""/><br /><sub><b>Daniel Norman</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=2color" title="Code">💻</a></td>
    <td align="center"><a href="https://www.lightco.in"><img src="https://avatars1.githubusercontent.com/u/9424721?v=4" width="75px;" alt=""/><br /><sub><b>John Light</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=john-light" title="Documentation">📖</a> <a href="https://github.com/aragon/aragon/issues?q=author%3Ajohn-light" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Smokyish"><img src="https://avatars0.githubusercontent.com/u/21331903?v=4" width="75px;" alt=""/><br /><sub><b>Tatu</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=Smokyish" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/dizzypaty"><img src="https://avatars0.githubusercontent.com/u/7205369?v=4" width="75px;" alt=""/><br /><sub><b>Patricia Davila</b></sub></a><br /><a href="#design-dizzypaty" title="Design">🎨</a> <a href="#userTesting-dizzypaty" title="User Testing">📓</a></td>
    <td align="center"><a href="https://github.com/jounih"><img src="https://avatars0.githubusercontent.com/u/10109867?v=4" width="75px;" alt=""/><br /><sub><b>Jouni Helminen</b></sub></a><br /><a href="#design-jounih" title="Design">🎨</a> <a href="#userTesting-jounih" title="User Testing">📓</a></td>
    <td align="center"><a href="https://github.com/lkngtn"><img src="https://avatars0.githubusercontent.com/u/4986634?v=4" width="75px;" alt=""/><br /><sub><b>Luke Duncan</b></sub></a><br /><a href="#ideas-lkngtn" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://danielconstantin.net/"><img src="https://avatars1.githubusercontent.com/u/26041347?v=4" width="75px;" alt=""/><br /><sub><b>Daniel Constantin</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=0x6431346e" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://rjewing.com"><img src="https://avatars3.githubusercontent.com/u/30963004?v=4" width="75px;" alt=""/><br /><sub><b>RJ Ewing</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=ewingrj" title="Code">💻</a></td>
    <td align="center"><a href="https://twitter.com/0xca0a"><img src="https://avatars0.githubusercontent.com/u/2223602?v=4" width="75px;" alt=""/><br /><sub><b>Paul Henschel</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=drcmda" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/rperez89"><img src="https://avatars2.githubusercontent.com/u/11763623?v=4" width="75px;" alt=""/><br /><sub><b>Rodrigo Perez</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=rperez89" title="Code">💻</a></td>
    <td align="center"><a href="http://www.gasolin.idv.tw"><img src="https://avatars1.githubusercontent.com/u/748808?v=4" width="75px;" alt=""/><br /><sub><b>gasolin</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=gasolin" title="Code">💻</a></td>
    <td align="center"><a href="http://adamsoltys.com/"><img src="https://avatars0.githubusercontent.com/u/7641?v=4" width="75px;" alt=""/><br /><sub><b>Adam Soltys</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=asoltys" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/arku"><img src="https://avatars2.githubusercontent.com/u/7039523?v=4" width="75px;" alt=""/><br /><sub><b>Arun Kumar</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=arku" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/bvanderdrift"><img src="https://avatars1.githubusercontent.com/u/6398452?v=4" width="75px;" alt=""/><br /><sub><b>Beer van der Drift</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=bvanderdrift" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/danielcaballero"><img src="https://avatars1.githubusercontent.com/u/1639333?v=4" width="75px;" alt=""/><br /><sub><b>Daniel Caballero</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=danielcaballero" title="Code">💻</a></td>
    <td align="center"><a href="https://twitter.com/deamlabs"><img src="https://avatars2.githubusercontent.com/u/9392750?v=4" width="75px;" alt=""/><br /><sub><b>Deam</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=deamme" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/uniconstructor"><img src="https://avatars3.githubusercontent.com/u/1384545?v=4" width="75px;" alt=""/><br /><sub><b>Ilia Smirnov</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=uniconstructor" title="Documentation">📖</a> <a href="#tool-uniconstructor" title="Tools">🔧</a></td>
    <td align="center"><a href="https://github.com/JulSar"><img src="https://avatars0.githubusercontent.com/u/28685529?v=4" width="75px;" alt=""/><br /><sub><b>julsar</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=JulSar" title="Documentation">📖</a></td>
    <td align="center"><a href="https://pascalprecht.github.io"><img src="https://avatars1.githubusercontent.com/u/445106?v=4" width="75px;" alt=""/><br /><sub><b>Pascal Precht</b></sub></a><br /><a href="#tool-PascalPrecht" title="Tools">🔧</a></td>
    <td align="center"><a href="https://rudygodoy.com"><img src="https://avatars2.githubusercontent.com/u/2400137?v=4" width="75px;" alt=""/><br /><sub><b>Rudy Godoy</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=rudygodoy" title="Documentation">📖</a></td>
    <td align="center"><a href="http://spacedecentral.net"><img src="https://avatars3.githubusercontent.com/u/2584493?v=4" width="75px;" alt=""/><br /><sub><b>Yalda Mousavinia</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=stellarmagnet" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/decodedbrain"><img src="https://avatars3.githubusercontent.com/u/18285094?v=4" width="75px;" alt=""/><br /><sub><b>decodedbrain</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=decodedbrain" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/jvluso"><img src="https://avatars2.githubusercontent.com/u/8061735?v=4" width="75px;" alt=""/><br /><sub><b>jvluso</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=jvluso" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/MarkGeeRomano"><img src="https://avatars1.githubusercontent.com/u/13630752?v=4" width="75px;" alt=""/><br /><sub><b>mark g romano</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=MarkGeeRomano" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/mul53"><img src="https://avatars0.githubusercontent.com/u/19148531?v=4" width="75px;" alt=""/><br /><sub><b>mul53</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=mul53" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Schwartz10"><img src="https://avatars1.githubusercontent.com/u/12353734?v=4" width="75px;" alt=""/><br /><sub><b>Jon</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=Schwartz10" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/abhinavsagar"><img src="https://avatars0.githubusercontent.com/u/40603139?v=4" width="75px;" alt=""/><br /><sub><b>Abhinav Sagar</b></sub></a><br /><a href="#maintenance-abhinavsagar" title="Maintenance">🚧</a></td>
    <td align="center"><a href="http://geleeroyale.netlify.com"><img src="https://avatars1.githubusercontent.com/u/317685?v=4" width="75px;" alt=""/><br /><sub><b>geleeroyale</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=geleeroyale" title="Documentation">📖</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/ottodevs"><img src="https://avatars2.githubusercontent.com/u/5030059?v=4" width="75px;" alt=""/><br /><sub><b>Otto G</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=ottodevs" title="Code">💻</a></td>
    <td align="center"><a href="https://adamboro.com/"><img src="https://avatars0.githubusercontent.com/u/7383192?v=4" width="75px;" alt=""/><br /><sub><b>Adam Boro</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=adekbadek" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/e18r"><img src="https://avatars3.githubusercontent.com/u/16065447?v=4" width="75px;" alt=""/><br /><sub><b>Emilio Silva Schlenker</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=e18r" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/osarrouy"><img src="https://avatars1.githubusercontent.com/u/86822?v=4" width="75px;" alt=""/><br /><sub><b>Olivier Sarrouy</b></sub></a><br /><a href="https://github.com/aragon/aragon/commits?author=osarrouy" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

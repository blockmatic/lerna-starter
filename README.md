<p align="center">
	</a>
	<a href="https://git.io/col">
		<img src="https://img.shields.io/badge/%E2%9C%93-collaborative_etiquette-brightgreen.svg" alt="Collaborative Etiquette">
	</a>
  <a href="https://developers.blockmatic.io">
		<img src="https://img.shields.io/badge/code%20style-blockmatic-brightgreen.svg" alt="Blockmatic Standard">
	</a>
	<a href="https://twitter.com/intent/follow?screen_name=blockmatic_io">
		<img src="https://img.shields.io/twitter/follow/blockmatic_io.svg?style=social&logo=twitter" alt="Follow on Twitter" />
	</a>
	<a href="https://t.me/blockmatic">
		<img src="https://img.shields.io/badge/-Chat%20on%20Telegram-blue?style=social&logo=telegram" alt="Chat on Telegram">
	</a>
</p>

# Monorepo Starter

Splitting up large codebases into separate independently versioned packages is extremely useful for code sharing. However, making changes across many repositories is _messy_ and difficult to track, and testing across repositories gets complicated really fast.

Lerna is a tool that optimizes the workflow around managing multi-package repositories with git and npm.

TypeScript references are a new feature in TypeScript 3.0 that allow you to structure your TypeScript programs into smaller pieces.

By doing this, you can greatly improve build times, enforce logical separation between components, and organize your code in new and better ways.

We’re also introducing a new mode for tsc, the --build flag, that works hand in hand with project references to enable faster TypeScript builds.

## Usage

**Global Dependencies**

- Install node.js v11 on your machine. We recommend using [nvm](https://github.com/creationix/nvm) or [n](https://github.com/tj/n), and [avn](https://github.com/wbyoung/avn) to manage multiple node.js versions on your computer.
- Yarn https://yarnpkg.com/lang/en/docs/install/.

**Initial Setup**

Run `yarn install`, `yarn bootstrap` to setup the project. Copy `.env-sample` and create `.env` file with your `GITHUB_TOKEN` for deployment with `lerna release`.

## Commands

- `yarn test`: lerna run test --stream
- `yarn build`: tsc --build (with ts references)
- `yarn lint`: lerna run lint --stream
- `yarn commit`: dev-scripts commit
- `yarn bootstrap`: lerna bootstrap --use-workspaces
- `yarn release`: env-cmd lerna publish
- `yarn diff`: lerna diff

## Contributing

Read the [contributing guidelines](https://developers.blockmatic.io) for details.

## Blockmatic

Blockmatic is building a robust ecosystem of people and tools for the development of blockchain applications.

[blockmatic.io](https://blockmatic.io)

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<!-- display the social media buttons in your README -->

[![Blockmatic Twitter][1.1]][1]
[![Blockmatic Facebook][2.1]][2]
[![Blockmatic Github][3.1]][3]

<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[1.1]: http://i.imgur.com/tXSoThF.png 'twitter icon with padding'
[2.1]: http://i.imgur.com/P3YfQoD.png 'facebook icon with padding'
[3.1]: http://i.imgur.com/0o48UoR.png 'github icon with padding'

<!-- icons without padding -->

[1.2]: http://i.imgur.com/wWzX9uB.png 'twitter icon without padding'
[2.2]: http://i.imgur.com/fep1WsG.png 'facebook icon without padding'
[3.2]: http://i.imgur.com/9I6NRUm.png 'github icon without padding'

<!-- links to your social media accounts -->
<!-- update these accordingly -->

[1]: http://www.twitter.com/blockmatic_io
[2]: http://fb.me/blockmatic.io
[3]: http://www.github.com/blockmatic

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

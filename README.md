<!--suppress HtmlDeprecatedAttribute -->
<div align="center">

![](media/monorepo.png)

Template project for setting up a TypeScript monorepo

[![Build Status](https://travis-ci.com/NiGhTTraX/ts-monorepo.svg?branch=master)](https://travis-ci.com/NiGhTTraX/ts-monorepo)

</div>

---

## Features

The main focus of this repo is making the `Go to definition` feature in IDEs work without any surprises, meaning it will work after a fresh clone without needing to build the project.

![find-usage](./media/find-usage.gif)

The secondary focus is to remove surprises when publishing packages. The repo is set up so that each package gets a clean build output without any artifacts from other packages.

![build-output](./media/build-output.png)

## Setup

This repo uses [yarn workspaces](https://classic.yarnpkg.com/en/docs/workspaces/) and [Lerna](https://lerna.js.org/). I recommend `yarn` for monorepos due to its easier setup, but everything here works with `npm` and `lerna bootstrap` as well and you can check that out in the [`npm` branch](https://github.com/NiGhTTraX/ts-monorepo/tree/npm).

```
yarn install
```

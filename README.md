# Guide

This is a guide for configuring husky to your project

## Installation

If you have your package.json and .git files in the same directory then just head over to husky's documentation and follow the recommended installation. But if you have your package.json and .git in seperate dirctories then Follow the manual installation guide with some tweaks. Steps:

1. Run `npm install husky --save-dev`
2. Then run: `npm pkg set scripts.prepare="cd to_your_root_dir && husky install"`
   This would modify the _package.json_ file.
3. Now you can run `npm run prepare` for the first time to create .husky directory. After that this will be created automatically on `npm install`.

## Usage

You can now use popular hooks such as `lint-staged`, `commitlint` etc. Checkout this repository for basic example.

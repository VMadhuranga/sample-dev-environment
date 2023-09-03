# Sample Dev Environment

This is initial webpack development environment 

### Usage

- Create a repo using this template ([here's how to do it](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template))
- inside the repo run `npm install` in the terminal

### OR

If you want to setup manually

- Inside your local repo run following command in the terminal
    - `npm init -y`
    - `npm install webpack webpack-cli --save-dev`
    - `npm install --save-dev style-loader css-loader`
    - `npm install --save-dev html-webpack-plugin`
    - `npm install -D babel-loader @babel/core @babel/preset-env webpack`
    - `npm install --save-dev webpack-merge`
    - `npm init @eslint/config`
    - `npm install --save-dev --save-exact prettier`
    - `echo {}> .prettierrc.json`
    - `npm install --save-dev eslint-config-prettier`

- Copy `scripts` inside `package.json`
- Copy the `webpack.*.js`, `.eslintignore`, `package.json`, `.gitignore` files to root directory
- Create `src` directory
- Copy `index.js` and `template.html` to `src` directory

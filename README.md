<h1 align="center">
  React Vitest Template
</h1>

<p align="center">
  <a href="https://github.com/criesbeck/react-vitest/releases">
    Releases
  </a>
</p>

<p align="center">
  A starter template for building React + Vitest apps with Vite.
</p>

## Folder Structure

```
your-app-name
├── node_modules
├── public
│   ├── favicon.svg
│   └── robots.txt
└── src
    ├── App.css
    ├── App.jsx
    ├── index.css
    ├── index.jsx
    └── logo.svg
├── .gitignore
├── index.html
├── package.json
├── README.md
├── vite.config.js
```

## Install

To get a local copy of the code, use [degit](https://github.com/tiged/tiged)

```
mkdir your-app-name
cd your-app-name
npx degit criesbeck/react-vitest
npm install
```
# Test

Start a local web server by running:

```
npm start
```

Open http://localhost:3000 in a browser.

## Scripts

**package.json** defines the following scripts:

| Script         | Description                                         |
| -------------- | --------------------------------------------------- |
| npm run dev  n | Runs the app in the development mode.               |
| npm run build  | Builds the app for production to the `dist` folder. |
| npm run serve  | Serves the production build from the `dist` folder. |
| npm run vitest | Starts a Jest-like test loop                        |

## Credits

React-Vitest built and maintained by [Chris Riesbeck](https://github.com/criesbeck).

Inspired by [SafdarJamal/vite-template-react](https://github.com/SafdarJamal/vite-template-react).
Expanded to include Vitest and some sample tests.

Gitignore file created with [the Toptal tool](https://www.toptal.com/developers/gitignore/api/react,firebase,visualstudiocode,macos,windows).


## License

This project is licensed under the terms of the [MIT license](./react-vitest/blob/main/LICENSE).

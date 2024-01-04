# This a React Project bootstraped with Vite.

## What is Vite?

In simpler terms vite is a bundler, but what is bundler?. As we are web developers we tend to have multiple types of files in our daily work life, like fonts, images, svgs, javascript, html, and many more to come in future.

But ultimately browser expects us to ship HTML, Javascript, CSS and maybe assets we have within our codebase, to achieve the simplicity and more developer friendly nature we have bundlers in which bundlers takes all the types of files we have with our codebase and spit out the files that are required for browsers display what we need to do.

An example picture of depicting can be found here at https://webpack.js.org/

> [!IMPORTANT]  
> Bundlers are dependent on plugins, a plugin can process one type or multiple types of files.

For example, if we want to process react or `.jsx` file we will be using a plugin called `babel-loader` or `esbuild` which will process the `.jsx` files and transform them `js` file for browser to understand what it need.

So, about using vite? and what are other types of bundlers available?

We have different types of bundlers available, to name a few vite, rspack, esbuild, rollup and webpack. To say prominently rollup and webpack are the most advanced and matured bundlers.

**Vite** uses two bundlers under the hood to give the performance speed i.e `esbuild` for development time and `rollup` when building the application.

## Why vite?

- Huge eco-system
- Multiple plugins available
- Faster development & build times
- Good Developer Experience.

## About task.

Under `<roo>/day-1/src/App.jsx` file we have two `img` tags that are being used to render `svg` files.

**Use Vite plugins to help import the `svg` files are React Components**

> Current Output

```jsx
<img src={reactLogo} className="logo react" alt="React logo" />
```

> Expected Output

```jsx

<ReactLogo className="logo react">

```

## Setting the project.

To run the project you need to install the required dependencies i.e `node_modules`, to install them run

```sh
npm install
```

To run development server run the following command

```sh
npm run dev
```

The above command will spin a dev server at `http://localhost:5001`, visit the given URL to see live changes happening with your code.

### Hints

Checkout awesome available vite plugins: https://github.com/vitejs/awesome-vite
SVGR - SVGReact for short - https://react-svgr.com/docs/getting-started, https://react-svgr.com/docs/rollup/, https://www.npmjs.com/package/esbuild-plugin-svgr

## Plugins

SVGR - https://github.com/pd4d10/vite-plugin-svgr

# React Create App Quickstart
> Skeleton of a React app - based on the React Create App template


## About

- A simple React scaffold
- Based on the React quickstart app that is generated by the React CLI's `create-react-app` command.
- Instructions are provided to create an fresh app or use create a Github repo immediately using this template.


## Documentation

Follow the setup instructions using this repo a template copied to your own repos.

Then you can run a start command to build and run the app, then you can view the app in the browser.

See [docs](/docs/README.md).


## How it works

- React's `.js` or `.jsx` files cannot be run directly - you need to use Babel as part of React's install and run flow.
- A React app typically runs as a Node.js server, especially locally.
- The app can be compiled to a build directory for running as a static site - this means you can deploy to GitHub Pages or Netlify.


## Create a fresh project

From [Getting started](https://create-react-app.dev/docs/getting-started/).

Run the `NPM` command which required [Node.js](https://gist.github.com/MichaelCurrin/aa1fc56419a355972b96bce23f3bccba) to be installed.

```sh
$ npx create-react-app my-app
$ cd my-app
$ npm start
```


## Resources

- [React](https://reactjs.org/) homepage
- [react](https://www.npmjs.com/package/react) package on NPM
- [create-react-app.dev](https://create-react-app.dev/)


## Dev notes

- It is better to set state through a method rather than by changing state directly.
- The Foo component is based on part of this video: [Get started with React in under 10 minutes](https://youtu.be/K02AkMbV1HM)
- This project uses 3 main dependencies, which were included with the quickstart
    - `react` - for the core application.
    - `react-dom` - for using `ReactDom` in [App.js](/src/App.js).
    - `react-scripts` - used to setup the `script` commands in [package.json](/package.json).
- There are 3 testing libraries - these were moved to dev dependencies.


## License

No license until I can figure out how the create quick start from React should be licensed. And if I should use the original NPM package's license as this is a major part.

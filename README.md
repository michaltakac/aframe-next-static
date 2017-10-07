## Aframe-next-static

[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/michaltakac/aframe-next-static)

This boilerplate leverages extremely simple deployment flow from Zeit's Now, now available for WebVR with A-Frame and React!

### Libraries

- [A-Frame](https://aframe.io)
- [aframe-react](https://github.com/ngokevin/aframe-react)
- [Next.js](https://github.com/zeit/next.js)

### Installation

To get started:

```bash
npm install # or yarn install
npm run dev
```

Development server now lives at [http://localhost:3000](http://localhost:3000).

This project uses static exporting feature from Next.js. If you wan't to build a Multiverse of multiple "pages" or "routes" (or should I say worlds?) and navigate through them, you need to provide a map of the routes in `next.config.js`. Read more info [here](https://github.com/zeit/next.js#static-html-export).

Note: Next.js is universal, which means it executes code first server-side, then client-side. The window object is only present client-side, so if you absolutely need to have access to it in some React component, you should put that code in `componentDidMount`. Check the `/pages/index.js` how we're doing it right now. You can load A-Frame-specific librabries like that. More info [here](https://github.com/zeit/next.js/wiki/FAQ#i-use-a-library-which-throws-window-is-undefined).

Deploy with ▲Now:

```bash
npm run deploy
```

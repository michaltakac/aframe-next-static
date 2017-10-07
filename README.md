## Aframe-next-static

[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/michaltakac/aframe-next-static)

This boilerplate leverage extremely simple deployment flow from Zeit's Now, now available for WebVR with A-Frame and React!

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

Deploy with ▲Now:

```bash
npm run deploy
```

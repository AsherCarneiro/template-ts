# SReact App Default Typescript Template


- `npm start` — This will spawn a development server with a default port of `3000`.
- `npm run build` — This will output a production build in the `dist` directory.
- `npm run preview` — This will run the production build locally with a default port of `5173` (this will not work if you haven't generated the production build yet).
- `npm run typecheck` — This will run `tsc --noEmit` which basically just typechecks your project.
- `npm run typewatch` — This will run `tsc --noEmit --watch` which will typecheck your project as you make changes.

## Typechecking

Unfortunately, ViteJS does not perform typechecking. So you will need to make use of the `typecheck` and `typewatch` scripts above.

## Custom port

You can use the `-p` flag to specify a port for development. To do this, you can either run `npm start` with an additional flag:

```
npm start -- --port 1234
```

Or edit the `start` script directly:

```
vite --port 1234
```

## Adding styles

You can use CSS files with simple ES2015 `import` statements anywhere in your Javascript:

```js
import "./appstyle.css";
```

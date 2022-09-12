# astro-vanilla-extract-demo

This is a basic demo of using [Astro](https://astro.build) with [vanilla-extract](https://vanilla-extract.style).

Since Astro uses [Vite,](https://vitejs.dev) all we need to do is install `@vanilla-extract/vite-plugin` (along with `@vanilla-extract/css` for use within `.css.ts` files), then add an instance of the plugin to the `vite.plugins` array in our `astro.config.mjs` file. We're then free to create `.css.ts` files and import them within our `.astro` files.

## Getting started

This project uses [pnpm.](https://pnpm.io)

```bash
pnpm install
pnpm dev
```

## License

MIT.

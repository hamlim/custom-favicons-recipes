# Custom Favicon Recipes

This repo is meant to outline a few neat Favicon recipes that you can use on your own projects to improve the experience for your users and yourself too!

## Recipes:

- Customizing favicons based on `NODE_ENV`
- Light and Dark mode favicons

### Custom Dev/Prod Favicons

You can swap the favicon that you use based on the `NODE_ENV`, allowing you to easily distinguish between a development version of your site and a production version of your site.

Check out the [`./apps/environment-favicons`](./apps/environment-favicons) for details!

### Light and Dark Mode Favicons

You can swap the favicon that you use based on a `media` attribute on the favicon `<link />` element to serve different favicons based on the desired theme by the user.

Check out the [`./apps/light-dark-favicons`](./apps/light-dark-favicon) for details!

## Development:

### Tasks:

Since this is a `turborepo` monorepo, you can run some tasks across the repo with ease by using the configured "tasks" from the root `package.json` and `turbo.json` files. Currently the below tasks are supported:

- `build`
- `type-check`
- `lint`
- `format`

### Tools:

- [Bun](https://bun.sh)
- [Turborepo](https://turbo.dev/repo/docs)
- [Next.js](https://nextjs.org)
- [SWC](https://swc.rs/)
- [TypeScript](https://www.typescriptlang.org/docs/)
- [dprint](https://www.typescriptlang.org/docs/)
- [oxlint](https://oxc-project.github.io/docs/guide/usage/linter.html)

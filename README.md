# sveltekit-template

[sveltekit](https://kit.svelte.dev/docs/creating-a-project) + [tailwindcss](https://tailwindcss.com/docs/guides/sveltekit) + [vite](https://vitejs.dev/config/)

## Installation

### Via [degit](https://github.com/Rich-Harris/degit)

```bash
degit freearhey/svelte-template my_app
cd my_app
npm install
```

## Developing

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open

# to make the app accessible from another device on the local network, add the --host flag
npm run dev -- --open --host
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

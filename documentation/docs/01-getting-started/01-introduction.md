---
title: Introducción
---

¡Bienvenido a la documentación de referencia de Svelte! Esto está pensado como un recurso para personas que ya tienen cierta familiaridad con Svelte y desean aprender más sobre cómo utilizarlo.

Si aún no eres una de esas personas, es posible que prefieras visitar el [tutorial interactivo](https://learn.svelte-es.dev) o los [ejemplos](/examples) antes de consultar esta referencia. Puedes probar Svelte en línea utilizando el [REPL](/repl). Alternativamente, si deseas un entorno más completo, puedes probar Svelte en [StackBlitz](https://sveltekit.new).

## Comenzar un nuevo proyecto

Recomendamos utilizar [SvelteKit](https://kit.svelte-es.dev/), el marco de aplicación oficial del equipo de Svelte:

```
npm create svelte@latest myapp
cd myapp
npm install
npm run dev
```

SvelteKit will handle calling [the Svelte compiler](https://www.npmjs.com/package/svelte) to convert your `.svelte` files into `.js` files that create the DOM and `.css` files that style it. It also provides all the other pieces you need to build a web application such as a development server, routing, deployment, and SSR support. [SvelteKit](https://kit.svelte.dev/) uses [Vite](https://vitejs.dev/) to build your code.

### Alternatives to SvelteKit

If you don't want to use SvelteKit for some reason, you can also use Svelte with Vite (but without SvelteKit) by running `npm create vite@latest` and selecting the `svelte` option. With this, `npm run build` will generate HTML, JS and CSS files inside the `dist` directory. In most cases, you will probably need to [choose a routing library](/faq#is-there-a-router) as well.

Alternatively, there are [plugins for all the major web bundlers](https://sveltesociety.dev/tools#bundling) to handle Svelte compilation — which will output `.js` and `.css` that you can insert into your HTML — but most others won't handle SSR.

## Editor tooling

The Svelte team maintains a [VS Code extension](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode) and there are integrations with various other [editors](https://sveltesociety.dev/tools#editor-support) and tools as well.

## Getting help

Don't be shy about asking for help in the [Discord chatroom](https://svelte.dev/chat)! You can also find answers on [Stack Overflow](https://stackoverflow.com/questions/tagged/svelte).

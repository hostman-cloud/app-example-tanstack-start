# TanStack Start

Example of a [TanStack Start](https://tanstack.com/start) application that can be deployed to **Hostman** without configuration.

:tada: [Demo]()

:rocket: [Create your Apps](https://hostman.com/my/apps/create)

:books: [Hostman Apps Documentation](https://hostman.com/docs/app-platform/backend-apps/)

## Deployment settings

The app is deployed as a frontend: pages are prerendered to HTML at build time (`prerender` in `vite.config.ts`).

| Parameter       | Value           |
| --------------- | --------------- |
| Framework       | TanStack Start  |
| Build command   | `npm run build` |
| Build directory | `dist/client`   |

Server-side rendering example: [app-example-tanstack-start-ssr](https://github.com/hostman-cloud/app-example-tanstack-start-ssr).

## <a name="dev"></a>Running locally

```bash
# install dependencies
npm install

# run in development mode with file watching
npm run dev

# build for production with minification
npm run build

# preview the production build locally
npm run preview
```

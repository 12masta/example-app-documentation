# Frontend architecture

The SPA is a React 19 app with React Router 7. Routes are page-scoped: each page owns its loader, actions, paths, and UI under `src/pages/<page>/`.

Server state uses TanStack React Query together with generated Orval clients. Shared API types live under `src/shared/api/generated`. UI talks to `example-app-backend` over HTTP. The browser never holds organisation or Hub secrets.

# Node TypeScript containerized

This is a minimal Node TypeScript app containerized with live reloading.  It makes a good starting point for building on.  It uses Nodemon for watching for file changes, `ts-node` for transpiling TypeScript on the fly without a build step, and a Docker bind mount to the source directory so code changes are automatically reloaded in the running container.

## Setup

```
npm install
```

```
npm start
```



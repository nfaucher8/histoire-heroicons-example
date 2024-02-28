# Histoire-Heroicons example

This is a Minimal, Reproducible Example (MRE) to recreate the `ERR_UNSUPPORTED_DIR_IMPORT` error
that is generated when attempting to use [Heroicons](https://heroicons.com/) with [Histoire](https://histoire.dev/) and 
[Vue](https://vuejs.org/)

This error was reproduced using `node v18.18.2`

## Project Setup
```sh
npm install
```

## Run Histoire to produce `ERR_UNSUPPORTED_DIR_IMPORT`
```sh
npm run story:dev
```

## Run dev server to show icons import properly in Vue+Vite app
```sh
npm run dev
```

## Run production preview server to show icons import properly in final Vue+Vite app
```sh
npm run preview
```
> node -v
>
> npm -v
>
> npm init -y
>
> npm install --save-dev typescript
>
> npm install -g typescript
>
> tsc -v
>
> npx tsc --init --rootDir src --outDir dist \
>
> mkdir src
> 
> touch src/index.ts

add scripts to package.json

```
"scripts": {
   "start": "node dist/index.js",
   "build": "npx tsc"
}
```

> npm install --save-dev ts-node nodemon

```
"scripts": {
    "start": "ts-node ./src/index.ts"
}
```

> npm install --save-dev eslint
> 
> npx eslint --init

```
"scripts": {
    "lint": "eslint . --ext .ts",
}
```
# tailwind-crash2

## Project setup

```
npm init -y
```

### tailwindcss setup

```
npm i tailwindcss
```

### create src folder

### create style.css file

```
/*! @import */
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### create dist folder

### create dist/index.html file

### create dist/style.css file

### update build script in package.json

```
  "scripts": {
    "build:css": "postcss src/style.css -o dist/style.css"
  },
```

### build

```
npx tailwindcss init --full
npm i postcss-cli
npm run build:css
```

### live-server setup

```
npm i live-server -g
```

### run live-server

```
live-server dist
```

### Google Fonts

https://fonts.google.com/

### Icons

https://heroicons.dev/

### Icons

https://fontawesome.com/

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

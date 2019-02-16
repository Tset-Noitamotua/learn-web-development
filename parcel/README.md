# Web Development For Dummies
>Based on Medium article ["If you’ve ever configured Webpack, Parcel will blow your mind!"](https://medium.com/@ibrahimbutt/if-youve-ever-configured-webpack-parcel-will-blow-your-mind-b615468cee78)

## Getting Started


1. copy this project
2. yarn init
3. yarn add parcel-bundler
4. yarn start (will start development server)
5. edit files in src - and enjoy live-reloading
6. yarn build (when you are ready to deploy)


- editing pug templates is a joy - e.g. `index.pug`

```HTML
<!DOCTYPE html>
html(lang="en")
  head
    link(rel="stylesheet", href="../sass/main.sass")
  body
    script(src="../js/main.js")
```

- next time try [Poi](https://poi.js.org/) instead of Parcel

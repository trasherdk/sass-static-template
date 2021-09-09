# sass-static-template

Copied from [5t3ph/sass-static-package.json](https://gist.github.com/5t3ph/077d788501508ea9f2eefda90c1473e0)  
Found in [Build Tools and Extensions I Use In Front-End Projects](https://dev.to/5t3ph/build-tools-and-extensions-i-use-in-front-end-projects-2ko5)

## Project Structure

```sh
.
├── package.json
├── README.md
└── src
    ├── index.html
    └── sass
        └── style.scss
```

`npm start` - copies src files to dist/ and starts Browsersync server at localhost:3000  
`npm run build` - copies files to dist/ and autoprefixes/minifies css

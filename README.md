This project is structured using submodules:
- themes/alpha-church is a submodule targetting our fork of the theme
- papeleriakon-tiki.github.io targets the website development version code.
Do get those by executing
```
git submodule update
```

Development
```
hugo server --watch
```

Upload to development env:
```
hugo
```
Then upload files under papeleriakon-tiki.github.io by commiting chnages to development or uploading files to production


###### Production
```
hugo --config config_prod.toml
````

New files to upload will be find under folder *papeleriakon-tiki.com*
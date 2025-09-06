# Hugo theme mini

## exampleSite


build

```shell
docker run --rm -it -v $(pwd):/src hugomods/hugo build --minify --printI18nWarnings --source exampleSite --theme /src
```

run server

```shell
docker run --rm -it -v $(pwd):/src -p 1313:1313 hugomods/hugo server --buildDrafts --source exampleSite --theme /src
```

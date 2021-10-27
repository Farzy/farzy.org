# farzy.org

This is the source code for [farzy.org](https://farzy.org), written in [Hugo](https://gohugo.io).

## Setup

```shell
git submodule update --init
```

## Add content

```shell
hugo new books/XXXX/index.fr.md
```

If `archetypes/books.md` exists, it will be used as a template, otherwise `archetypes/default.md` 
is used.

Use `date -I` on Linux to generate the correct date format.

## Deploy

```shell
./deploy
```

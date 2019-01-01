# my-hp

## Requires

- node.js

## Getting Started

install firebase tools

```
$ npm install -g firebase-tools
```

setup firebase

```
$ cd my-hp
$ firebase login
$ firebase init
File public/index.html already exists. Overwrite? ←Noと答える
```

modify and build

```
$ vi config.toml
$ hugo # public/index.htmlが更新される
```

deploy

```
$ firebase deploy
```

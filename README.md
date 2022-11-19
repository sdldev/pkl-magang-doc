# PKL MAGANG DOC
Dokumentasi untuk anak2 PKL


## About
Repo ini digunakan khusus untuk panduan dan dokumentasi PKL. Dibuat dengan [Docusaurus 2](https://docusaurus.io/),untuk memudahkan penulisan dokumentasi dalam bentuk MD 

### Installation
```
$ npm install
```
```
$ yarn
```
### Local Development
```
$ npm run start
```
```
$ yarn start
```
This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.
### Build

```
$ npm run build
```

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

### Continuous Integration

Some common defaults for linting/formatting have been set for you. If you integrate your project with an open source Continuous Integration system (e.g. Travis CI, CircleCI), you may check for issues using the following command.

```
$ yarn ci
```

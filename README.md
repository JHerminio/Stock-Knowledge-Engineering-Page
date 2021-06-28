## Website

This website is built using [Visual Studio Code](https://code.visualstudio.com/), is a code editor redefined and optimized for building and debugging modern web and cloud applications.

### Installation

```console
visual studio code install
```

### Local Development

```console
visual studio start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```console
yarn build

``` 

-->statement for hosting website

### Deployment

```console
GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `master` branch.

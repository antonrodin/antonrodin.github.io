Some instructions...
====================

The source files are located on src branch... To deploy the site:

1. Build the project.

```shell
webpack --config=config/webpack.dev.js
```

2. Merge src and master branches.

```shell
git merge src
```

3. Deploy from master brunch to github repo using this command.

```shell
git subtree push --prefix dist origin master
```
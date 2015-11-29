# dokku-buildtime-env

For use with [dokku](https://github.com/progrium/dokku)

Run commands in the container before its deployment. Using this plugin allows to use commands that needs volumes for example.

## Requirements

* Dokku version `0.4` or higher

## Installation

On the dokku server, you need to install the plugin in the standard Dokku way. Specifically:

```
# dokku 0.4.x
dokku plugin:install https://github.com/jdacosta/dokku-buildtime-env.git
```

## Thanks
Thanks to [dokku-predeploy-tasks](https://github.com/michaelshobbs/dokku-app-predeploy-tasks).
Thanks to [dokku-deploy-script](https://github.com/OzConseil/dokku-deploy-script).

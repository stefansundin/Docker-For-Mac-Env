Launch Docker For Mac with custom environment variables. Simply launch this app to launch Docker.app with environment variables defined in `Docker-Env.sh`.

As an example, you can use this in case you want to load multiple kubeconfig files.

See https://github.com/docker/for-mac/issues/2635

Install with:
```
cp -r Docker-Env-app/ /Applications/Docker-Env.app
```

To have it launch on startup, open _System Preferences_, go to _Users & Groups_, and add `Docker-Env` to your _Login Items_.

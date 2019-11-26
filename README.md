# pjlamb12/angular-cli

This is the repo for the [pjlamb12/angular-cli](https://hub.docker.com/repository/docker/pjlamb12/angular-cli) Docker image. The image is based on the [node alpine](https://hub.docker.com/_/node) image, and then the @angular/cli package installed as well.

To use the image:

```bash
docker pull pjlamb12/angular-cli
```

Or, in the `Dockerfile`:

```Dockerfile
FROM pjlamb12/angular-cli
```

Contributions welcome, with the plan to push a new version each time a major LTS version of Node is released (even numbers) or a new version of the Angular CLI is released.

[![Deploy](https://cdn.wedeploy.com/images/deploy.svg)](https://console.wedeploy.com/deploy?repo=https://github.com/wedeploy-examples/gitlab-example)

# GitLab

A example of [Gitlab](https://about.gitlab.com/) on [WeDeploy](https://wedeploy.com/).

## Instructions

1. Install the [WeDeploy CLI](https://wedeploy.com/docs/intro/using-the-command-line/).
2. Clone this repository.
3. Open the project folder with your command line and run **we deploy -p yourproject**.

## Note

Gitlab [official image](https://hub.docker.com/r/gitlab/gitlab-ce/~/dockerfile/) adds a volume to `/var/opt/gitlab`. This path is not allowed when deploying to WeDeploy since we do not support *.socket files inside our volumes.

## License

[BSD-3-Clause](./LICENSE.md), © Liferay, Inc.

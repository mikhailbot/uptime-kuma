# Uptime kuma

Configuration for running [Uptime Kuma](https://github.com/louislam/uptime-kuma) on [fly.io](https://fly.io/) for monitoring my personal sites.

The included `fly.toml` file combined with the below command should get a new instance up and running. If creating a new instance be sure to set a new app name.

```bash
flyctl deploy -i louislam/uptime-kuma
```
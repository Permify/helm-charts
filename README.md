<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Permify/permify/raw/master/assets/logo-permify-dark.png">
    <img alt="Permify logo" src="https://github.com/Permify/permify/raw/master/assets/logo-permify-light.png" width="40%">
  </picture>
</div>
<h1 align="center">
    Permify Helm Charts
</h1>
<p align="center">
    <a href="https://artifacthub.io/packages/search?repo=permify" target="_blank"><img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/permify&style=for-the-badge" alt="GitHub package.json version" /></a>&nbsp;
    <a href="https://github.com/Permify/permify" target="_blank"><img src="https://img.shields.io/github/license/Permify/helm-charts?style=for-the-badge" alt="Permify Licence" /></a>&nbsp;
    <a href="https://discord.gg/MJbUjwskdH" target="_blank"><img src="https://img.shields.io/discord/950799928047833088?style=for-the-badge&logo=discord&label=DISCORD" alt="Permify Discord Channel" /></a>&nbsp;
</p>

Helm charts for deploying and managing Permify in Kubernetes environments.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
$ helm repo add permify https://permify.github.io/helm-charts
```

You can then run `helm search repo permify` to see the charts.

## License

[Apache 2.0 License](./LICENSE).

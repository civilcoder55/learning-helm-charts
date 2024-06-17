## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add <alias> https://civilcoder55.github.io/learning-helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the `express-mysql-redis` chart:

```sh
helm install my-release <alias>/express-mysql-redis
```

To uninstall the chart:

```sh
helm delete my-release
```
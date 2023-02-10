# starship
![Lint](https://github.com/mkRuby009/starship/actions/workflows/lint-check.yaml/badge.svg)
![Deploy](https://github.com/mkRuby009/starship/actions/workflows/release.yaml/badge.svg)

Universal interchain development environment in k8s. The vision of this project
is to have a single easy to use developer environment with full testing support
for multichain use cases

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

helm repo add <alias> https://mkRuby009.github.io/starship/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> <alias>/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>

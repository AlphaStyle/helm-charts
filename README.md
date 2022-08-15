## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

	helm repo add fork-grafana https://alphastyle.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
fork-grafana` to see the charts.

To install the loki-distributed chart:

	helm install loki-distributed fork-grafana/loki-distributed

To uninstall the chart:

	helm delete loki-distributed

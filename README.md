## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add aegis https://aegis-public.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
aegis` to see the charts.

To install the workspace-connector chart:

    helm install my-workspace-connector aegis/workspace-connector

To uninstall the chart:

    helm uninstall my-workspace-connector

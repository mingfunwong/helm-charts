## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add mingfunwong https://mingfunwong.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
mingfunwong` to see the charts.

To install the enu-node chart:

    helm install enu-node-1 mingfunwong/enu-node

To uninstall the chart:

    helm delete enu-node-1

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add helm-project https://fivetiger1.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
helm-project` to see the charts.

To install the helm-project chart:

    helm install helm-project helm-project/go-project

To uninstall the chart（版本更新 不再支持 delete）:

    helm uninstall go-project

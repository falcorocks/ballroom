# ballroom
helm chart to deploy stateful set with N replicas, N services, N ingresses

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

`helm repo add ballroom https://falcorocks.github.io/ballroom/`

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
ballroom` to see the charts.

To install the ballroom chart:

`helm install my-ballroom ballroom/ballroom --version 1.0.2`

To uninstall the chart:

`helm delete my-ballroom`

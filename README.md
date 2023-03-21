# Ballroom Chart

Helm chart to deploy:

* N replicas of a stateful set
* N services, one for each replica

Optionally:
* N ingresses (vanilla or istio), one for each service
* an ImagePullSecret

```
# add helm repository from project github pages
helm repo add ballroom https://ballroom.github.io/helm-charts

# fetch chart updates
helm repo update

# install chart
helm install my-ballroom ballroom/ballroom
```

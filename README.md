# Ontoserver on OpenShift 4.x

Artifacts to deploy CSIRO `ontoserver` instances to OpenShift.

## Deployment Approaches

There are broadly two approach to manage the life cycle of the application (build/deploy/update/delete) on the OpenShift cluster:

1. Imperative: An approach where engineers rely on tools to specify `how` to perform the desired actions. E.g.
    1. Use `oc ...` cli to deploy all k8s artifacts.
    1. Use `helm ...` cli to version control the deployable artifacts and releases.
1. Declarative: An approach where engineers specify the (`what`) desired state, and the configuration management tool determines how best to achieve it. Couple of examples are below. For example, using OpenShift GitOps (ArgoCD) to manage the deployment of ontoserver instances.

Presently this repository provides Helm charts to imperatively deploy ontoserver instances, covered [here](helm/ontoserver/README.md).

### Declarative approach to deploy OntoServer with OpenShift GitOps

> TBD

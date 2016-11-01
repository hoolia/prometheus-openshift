# prometheus-openshift
Prometheus metrics for OpenShift

# Install
```shell
oc new-project metrics
oc adm policy add-cluster-role-to-user cluster-admin system:serviceaccount:metrics:default
oc create -f https://raw.githubusercontent.com/hoolia/prometheus-openshift/master/prometheus-template.yml
```

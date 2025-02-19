# k8s-json-scheme
### k8s json schemas with some crds:

* VictoriaMetrics-operator https://raw.githubusercontent.com/VictoriaMetrics/helm-charts/refs/heads/master/charts/victoria-metrics-operator/charts/crds/crds/crd.yaml
* grafana-operator https://raw.githubusercontent.com/grafana/grafana-operator/master/deploy/helm/grafana-operator/crds/grafana.integreatly.org_grafana{s,alertrulegroups,contactpoints,dashboards,datasources,folders}.yaml
* velero https://raw.githubusercontent.com/vmware-tanzu/helm-charts/main/charts/velero/crds/{backuprepositories,backups,backupstoragelocations,datadownloads,datauploads,deletebackuprequests,downloadrequests,podvolumebackups,podvolumerestores,restores,schedules,serverstatusrequests,volumesnapshotlocations}.yaml
* k8up https://raw.githubusercontent.com/k8up-io/k8up/1088118931d95579d76d4b0b668214f21d63d01d/config/crd/apiextensions.k8s.io/v1/k8up.io_{archives,backups,checks,prebackuppods,prunes,restores,schedules,snapshots}.yaml
* aws-load-balancer-controller https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/main/helm/aws-load-balancer-controller/crds/crds.yaml
* cert-manager https://raw.githubusercontent.com/cert-manager/cert-manager/v1.14.4/deploy/crds/crd-{clusterissuers,certificates,challenges,clusterissuers,issuers,orders}.yaml
* helm-operator https://raw.githubusercontent.com/fluxcd/helm-operator/master/deploy/crds.yaml
* prometheus-operator https://raw.githubusercontent.com/prometheus-operator/prometheus-operator/master/example/prometheus-operator-crd/monitoring.coreos.com_{alertmanagerconfigs,alertmanagers,podmonitors,probes,prometheusagents,prometheuses,prometheusrules,scrapeconfigs,servicemonitors,thanosrulers}.yaml
* traefik-containo https://raw.githubusercontent.com/traefik/traefik-helm-chart/master/traefik/crds/traefik.containo.us_{ingressroutes,ingressroutetcps,ingressrouteudps,middlewares,middlewaretcps,serverstransports,tlsoptions,tlsstores,traefikservices}.yaml
* traefik-io_ingressroutes https://raw.githubusercontent.com/traefik/traefik-helm-chart/master/traefik/crds/traefik.io_{ingressroutes,ingressroutetcps,ingressrouteudps,middlewares,middlewaretcps,serverstransports,tlsoptions,tlsstores,traefikservices}.yaml
* kyverno_io https://github.com/kyverno/kyverno/releases/download/v1.13.0/kyverno.io_{cleanuppolicies,clustercleanuppolicies,clusterpolicies,globalcontextentries,policies,policyexceptions,updaterequests}.yaml
* reports_kyverno_io https://github.com/kyverno/kyverno/releases/download/v1.13.0/reports.kyverno.io_{clusterephemeralreports,ephemeralreports}.yaml
* wgpolicyk8s_io https://github.com/kyverno/kyverno/releases/download/v1.13.0/wgpolicyk8s.io_{clusterpolicyreports,policyreports}.yaml
* rbac-manager https://raw.githubusercontent.com/FairwindsOps/rbac-manager/a075baed876f991787e7b966c2faf7d51d2596d6/deploy/2_crd.yaml
* kubearmor https://raw.githubusercontent.com/kubearmor/KubeArmor/refs/heads/main/deployments/CRD/KubeArmor{ClusterPolicy,HostPolicy,Policy}.yaml
* 
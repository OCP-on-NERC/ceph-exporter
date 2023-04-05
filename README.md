# Deploy `ceph_export` on OpenShift

This repository has the manifests to deploy [ceph_exporter][] on our OpenShift cluster. We are using a [custom image][] that includes code to generate a Ceph configuration from secrets available in the `openshift-storage` namespace.

[ceph_exporter]: https://github.com/digitalocean/ceph_exporter
[custom image]: https://github.com/OCP-on-NERC/ceph-exporter-image

[Sysdig Cloud](http://www.sysdig.com/) is the first and only monitoring, alerting, and troubleshooting solution designed from the ground up to provide unprecedented visibility into containerized infrastructures.

Sysdig Cloud comes with built-in, first class support for Kubernetes. In order to instrument your Kubernetes environment with Sysdig Cloud, you simply need to install the Sysdig Cloud agent container on each underlying host in your Kubernetes cluster. Sysdig Cloud will automatically begin monitoring all of your hosts, apps, pods, and services, and will also automatically connect to the Kubernetes API to pull relevant metadata about your environment.

# Example Installation

Provided here are two example sysdig.yaml files that can be used to automatically deploy the Sysdig Cloud agent container across a Kubernetes cluster.

The recommended method is using daemon sets - minimum kubernetes version 1.1.1.

If daemon sets are not available, then the replication controller method can be used (based on [this hack](https://stackoverflow.com/questions/33377054/how-to-require-one-pod-per-minion-kublet-when-configuring-a-replication-controll/33381862#33381862 )).

# Install instructions

Please see the Sysdig Cloud support site for the latest documentation:
http://support.sysdigcloud.com/hc/en-us/sections/200959909

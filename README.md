# Fluent-bit
To establish efficient log aggregation and analysis within your Kubernetes cluster, you can set up Fluentbit to seamlessly stream logs from your pods to Elasticsearch, a critical step in configuring your EFK (Elasticsearch, Fluentd, Kibana) stack.

Flow the below sequence for Fluent-bit configuration
  1) service-account.yaml
  2) service-endpoint.yaml
  3) role.yaml
  4) role-binding.yaml
  5) configmap-fb.yaml
  6) daemonset.yaml

Once done we should see the below output

![kubectl_screenshot](https://github.com/Nuwas/Fluent-bit/assets/32307939/bce38ee9-874b-45b3-838a-debd5bd1c759)

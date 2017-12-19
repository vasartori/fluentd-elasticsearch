# Collecting Docker Log Files with Fluentd and Elasticsearch
This directory contains the source files needed to make a Docker image
that collects Docker container log files using [Fluentd][fluentd]
and sends them to an instance of [Elasticsearch][elasticsearch].
This image is designed to be used as part of the [Kubernetes][kubernetes]
cluster bring up process. 

# This image is a fork from [https://github.com/kubernetes/kubernetes/tree/master/cluster/addons/fluentd-elasticsearch]

[fluentd]: http://www.fluentd.org/
[elasticsearch]: https://www.elastic.co/products/elasticsearch
[kubernetes]: https://kubernetes.io


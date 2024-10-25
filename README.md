# spark-on-kubernetes-docker
Spark on Kubernetes infrastructure Docker images repo. Used as defaults for [spark-cluster](https://github.com/jahstreet/spark-on-kubernetes-helm/tree/master/charts/spark-cluster) Helm chart.
Feito novo build utilizando o código modificado nesse repo: [rangnar14](https://github.com/rangnar14/incubator-livy/tree/feature/ingress-api-update)
Realizado teste de deploy no k8s 1.29 livy agora funcionando como esperado.
Imagem desse build ja disponivel no meu docker hub 
https://hub.docker.com/layers/rincon/livy/0.8.0-incubating-spark_3.0.1_2.12-hadoop_3.2.0_cloud/images/sha256-2b93fb6d610c8b5d50d8d75b4a14a64b747328130fb239ddeeafd667f0b98e0e?context=repo

Para fazer o deploy no k8s e so alterar o repository no helm chart
https://github.com/JosemarRincon/spark-on-kubernetes-helm/blob/master/charts/livy/values.yaml


[PR for LIVY-588](https://github.com/apache/incubator-livy/pull/167) on integration with Kubernetes

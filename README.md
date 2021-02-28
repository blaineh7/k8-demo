# Kubernetes-Demo

Learning Objectives
  * Docker basics
  * Kubernetes system (k8) features
  * Launch looping Job from shell
  * Launch  limited job from shell
  * kubectl basic commands
    * list pods
    * get shell access (exec) into running container
  * get status of pod
  * remove job



Metadata
  github repo
    https://github.com/blaineh7/k8-demo.git
Cloud Shell
  * setup environment
    * gcloud config set project constellation-275522
    * gcloud container clusters get-credentials cluster-1 --zone us-east1-b  --project constellation-275522

kubectl commands
   * kubectl get pods
   * kubectl get pod {pod name}
   * kubectl apply -f {config.yaml}
   * kubectl exec --stdin --tty {container name} -- {command (/bin/ash   bash)}
   * kubectl logs {name}
   * kubectl delete -f {name}
   * kubectl describe pod {name}
   * kubectl describe job {name}  -get pod to exec into

linux commands
   * cat /etc/os-release  --get the version of linux running
docker commmands
   * ctrl p + ctrl q  --exit containter without stopping the container


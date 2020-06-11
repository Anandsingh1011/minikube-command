# minikube-command

List of minikube command


## Basic Command


| Name | Command |
|--|--|
| minikube lifecycle |minikube delete, minikube start, minikube status  |
| Version | minikube version |
| Start minikube | minikube start |
| Start minikube with different machine flavor | start --memory 5120 --cpus=4 |
| Start minikube with a specific k8s version | minikube start --kubernetes-version v1.11.0 |
| Start minikube with more customizations | minikube start –kubernetes-version v1.11.0 –feature-gates=AdvancedAuditing=true |
| Get minikube ip | minikube ip |
| SSH to minikube vm | minikube ssh |
| Use Your local docker to use minikube dockerd | `eval $(minikube docker-env)`, Then no need for `docker push` |

## Status Command
| Name | Command |
|--|--|
| Get minikube version | minikube version |
| Get cluster info | kubectl cluster-info |
| Get service info | minikube service SVR-NAME |
| List addons | minikube addons list |
| Get ip | minikube ip |
| Get minikube log | minikube logs |
| Get dashboard | minikube dashboard |


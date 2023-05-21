# Kubeplugin

## Description
Top metrics for pods/modes in namespace

## Installation
> make install

## How to use
```
kubeplugin <resource> <namespace>
```
> kubeplugin pod kube-system

## Reslut example
```
Resource: pod, Namespace: kube-system, Name: coredns-787d4945fb-n788d, CPU: 2m, Memory: 27Mi
Resource: pod, Namespace: kube-system, Name: etcd-minikube, CPU: 21m, Memory: 52Mi
Resource: pod, Namespace: kube-system, Name: kube-apiserver-minikube, CPU: 36m, Memory: 318Mi
Resource: pod, Namespace: kube-system, Name: kube-controller-manager-minikube, CPU: 17m, Memory: 61Mi
Resource: pod, Namespace: kube-system, Name: kube-proxy-bzbmp, CPU: 1m, Memory: 20Mi
Resource: pod, Namespace: kube-system, Name: kube-scheduler-minikube, CPU: 2m, Memory: 29Mi
Resource: pod, Namespace: kube-system, Name: metrics-server-6588d95b98-52zfj, CPU: 3m, Memory: 33Mi
Resource: pod, Namespace: kube-system, Name: storage-provisioner, CPU: 2m, Memory: 19Mi
```
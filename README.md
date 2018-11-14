# eks-workshop-x-ray-daemon

Foundation for the example [AWS X-Ray](https://aws.amazon.com/xray/) DaemonSet in the [EKS Workshop](https://eksworkshop.com/)

Based on the [aws-xray-kubernetes](https://github.com/aws-samples/aws-xray-kubernetes) project

See the [Application Tracing on Kubernetes with AWS X-Ray](https://aws.amazon.com/blogs/compute/application-tracing-on-kubernetes-with-aws-x-ray/) blog post for more info

Command reference:

Deploy the DaemonSet
```
kubectl apply -f xray-k8s-daemonset.yaml
```

Describe the DaemonSet
```
kubectl describe daemonset xray-daemon
```

Check the status of the pods
```
kubectl get pods
```

Delete the DaemonSet
```
kubectl delete daemonset xray-daemon
```



# k8s-demo

URL: [link](https://k8s-demo.k8s-facile.it/)

## Sample commands

```
kubectl rollout status deployment/k8s-demo-deployment
kubectl rollout history deployment/k8s-demo-deployment
kubectl rollout undo deployment/k8s-demo-deployment --to-revision=1
```

## Reference

- [Performing a Rolling Update](https://kubernetes.io/docs/tutorials/kubernetes-basics/update/update-intro/)
- [Kubernetes Rolling Update Configuration](https://www.bluematador.com/blog/kubernetes-deployments-rolling-update-configuration)
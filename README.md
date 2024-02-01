# k8s-hw
Simple K8s Hello World. It deploys the [Knapsack Stress API](https://github.com/pafmon/ks-api) with a NodePort connectivity.

### Deploy
```bash
$> make k8s_deploy
```

You can browse the api at <http://localhost:32607/> to test the API

To analyze the state of the pods:
```bash
$> kubectl get pods
```

### Clean up
```bash
$> make k8s_clean
```

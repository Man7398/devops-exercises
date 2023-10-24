## Certified Kubernetes Administrator (CKA)

### Pods

<details>
<summary>Deploy a pod called web-1985 using the nginx:alpine image</code></summary><br><b>

`kubectl run web-1985 --image=nginx:alpine --restart=Never`
</b></details>

<details>
<summary>How to find out on which node a certain pod is running?</summary><br><b>

`kubectl get po -o wide`
</b></details>

Some theory questions asked in the interview regarding Kubernetes-

1)What is Kubernetes?
2)Explain key Kubernetes components.
3)How do you create a Pod in Kubernetes?
4)What's the purpose of a Service in Kubernetes?
5)Distinguish between Deployments and StatefulSets.
6)How to upgrade a Kubernetes cluster?
7)Define the role of kubelet in a node.
8)Troubleshoot a Pod not starting.
9)What's RBAC in Kubernetes?
10)What are Namespaces used for?


# example_of_kubernetes_secrets

#### What are Kubernetes secrets, and how does it work?

A Kubernetes secret is a way to store sensitive data, such as passwords, OAuth tokens, or SSH keys, in a way that is safe and accessible to applications running in the cluster. Secrets are stored in a key-value format, and the keys are encrypted using a secret encryption key.

![image](https://github.com/git-black-ninja/example_of_kubernetes_secrets/assets/141961610/4833c80a-a5f6-42e5-99bf-259539d69c8a)




first, deploy all things.


```bash
git clone https://github.com/git-black-ninja/example_of_kubernetes_secrets.git
cd example_of_kubernetes_secrets/
kubectl apply -f .
```

Get the NodePort number of the wp service and open it on browser.

```bash
kubectl get svc
```
OutPut is look like this.
![image](https://github.com/git-black-ninja/example_of_kubernetes_secrets/assets/141961610/d22610a5-eac6-4a74-ac03-e0a22eaa00b7)

<p style="text-align: center"><img src="https://1000logos.net/wp-content/uploads/2022/07/Kubernetes-Logo.jpg" width="60%"></p>

# K8S

## Running a pod directly

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: posts
spec:
  containers:
    - name: posts
      image: david/posts:0.0.1
      ports:
        - containerPort: 4000
```

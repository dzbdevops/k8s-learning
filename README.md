# Example of using kubernetes based on Nana's tutorial
Link: https://www.youtube.com/watch?v=s_o8dwzRlu4
## Requirements:
- minikube
- kubectl

## Frontend:
- public docker Nana's image: nanajanashia/k8s-demo-app:v1.0

## How to use?
We build each file starting with:
```
- mongo-config.yaml
- mongo-secret.yaml
- mongo.yaml
- webapp.yaml
```
## Example:
`kubectl apply -f mongo-config.yaml`

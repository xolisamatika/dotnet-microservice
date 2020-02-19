## START minikube
```
minikube start
```

## Deploy
```
kubectl apply -f deployment.yaml
```

## Get URL
```
kubectl get service dotnet-microservice --watch
```
### In you browser enter `[YOUR URL]/WeatherForecast`

# test-helm
test helm

helm install app test-nginx --namespace wachira

helm upgrade app test-nginx --namespace wachira

helm uninstall  app  --namespace wachira

helm delete  test-nginx --namespace wachira


kubectl get -n wachira po

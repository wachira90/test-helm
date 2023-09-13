# test-helm
test helm


git clone -b main https://github.com/wachira90/test-helm.git test-nginx

helm install app test-nginx --namespace wachira

helm upgrade app test-nginx --namespace wachira

helm uninstall  app  --namespace wachira

helm delete  test-nginx --namespace wachira


kubectl get -n wachira po

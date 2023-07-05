# helm-openmrs
kubectl create ns dop -o yaml
helm install openmrsdeploy openmrs -n helm
kubectl port-forward deploy/openmrs-deploy 8080:8080 -n helm

http://localhost:8080/openmrs

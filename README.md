# Manifests for the installation of NextCloud in Kubernetes
Those manifests will install Nextcloud with a MariaDB instance.

## Usage
```
kubectl create namespace nextcloud
kubectl apply -f ./
```
## Configuration
You will need to change the following settings to suit your needs:
* Database passwords in environment.yml
* Domain name in the ingress section of nextcloud.yml

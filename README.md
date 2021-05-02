# Manifests for the installation of NextCloud in Kubernetes
Those manifests will install Nextcloud and a MariaDB instance for it

## Usage
```
kubectl create namespace nextcloud
kubectl apply -f ./
```
## Configuration
You will need to change the following settings to suit your needs:
* Database passwords in mariadb.yml
* Domain name in the ingress section of nextcloud.yml

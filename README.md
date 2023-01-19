Для запуска использовались команды:

`helm repo add bitnami https://charts.bitnami.com/bitnami`\
`helm install mariadb bitnami/mariadb --values mariadb.yaml` \
`helm install redis bitnami/redis --values redis.yaml` \
`helm install nginx-ingress-controller bitnami/nginx-ingress-controller` \
`helm install ctfd ctfd --values ctfd/values.yaml`

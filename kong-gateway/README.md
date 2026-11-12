DEPLOYMENT
============

1. helm repo add kong https://charts.konghq.com
2. helm repo update
3. helm upgrade --install kong kong/kong -n namespace -f values.yaml
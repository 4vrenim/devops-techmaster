k create deployment nginx --image nginx -r 2 --dry-run=client -o yaml > templates/nginx-deploy.yaml

k create service nodeport nginx --tcp=80:80 --dry-run=client -o yaml > templates/nginx-svc.yaml

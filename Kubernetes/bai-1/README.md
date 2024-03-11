k create deployment nginx --image nginx -r 2 --dry-run=client -o yaml > templates/nginx-deploy.yaml

k create service nodeport nginx --tcp=80:80 --dry-run=client -o yaml > templates/nginx-svc.yaml

![Image](https://github.com/4vrenim/devops-techmaster/blob/104317ad312e378dde5585aa31b61113f5213e7a/Kubernetes/bai-1/images/1.jpg)

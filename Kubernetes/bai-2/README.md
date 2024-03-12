k create cm web1-config --from-file web1.conf

k apply -f pv1.yaml

k apply -f pvc1.yaml

k apply -f web1-deploy.yaml

k apply -f web1-svc.yaml


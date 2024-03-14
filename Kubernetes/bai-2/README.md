k create cm web1-config --from-file web1.conf

k apply -f pv1.yaml

k apply -f pvc1.yaml

k apply -f web1-deploy.yaml

k apply -f web1-svc.yaml
>
>
![image](https://github.com/4vrenim/devops-techmaster/blob/786ede0740cd7b88714a0995535f8918bd9bc91d/Kubernetes/bai-2/images/cat_configmap.jpg)
>
>
![image](https://github.com/4vrenim/devops-techmaster/blob/786ede0740cd7b88714a0995535f8918bd9bc91d/Kubernetes/bai-2/images/get_info.jpg)
>
>
![image](https://github.com/4vrenim/devops-techmaster/blob/18050514957932f2a110a20894c062c6a39659f0/Kubernetes/bai-2/images/curl_web_1.jpg)




#  OKD   

https://www.okd.io/      


![okd](_image/okd.png)

#  Quick Start    

https://docs.okd.io/latest/getting_started/administrators.html    


```
./oc cluster up --skip-registry-check=true --public-hostname=10.254.21.1
```

--public-hostname=127.0.0.1


# Install

Q1:

```
Ensure that the Docker daemon is running with the following argument:
        --insecure-registry 172.30.0.0/16
```
S1:

vim `/etc/containers/registries.conf`

```
[registries.insecure]
registries = ['172.30.0.0/16']
```

参考：
https://developer.fedoraproject.org/deployment/openshift/about.html



---




#  get start

## oc install
https://docs.okd.io/latest/getting_started/administrators.html


https://docs.okd.io/latest/getting_started

https://github.com/openshift/origin/blob/v4.0.0-alpha.0/docs/cluster_up_down.md




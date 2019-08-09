# redhat-openshift-platform


#  OKD   
https://www.okd.io/      

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





#  get start

## oc install
https://docs.okd.io/latest/getting_started/administrators.html


https://docs.okd.io/latest/getting_started

https://github.com/openshift/origin/blob/v4.0.0-alpha.0/docs/cluster_up_down.md



## Course interactive 
https://learn.openshift.com/  


## A4
https://cheatsheet.dennyzhang.com/cheatsheet-openshift-a4

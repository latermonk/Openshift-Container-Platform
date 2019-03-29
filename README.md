# redhat-openshift-platform


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


#  get start

https://docs.okd.io/latest/getting_started

https://github.com/openshift/origin/blob/v4.0.0-alpha.0/docs/cluster_up_down.md



## Course interactive 
https://learn.openshift.com/  


## A4
https://cheatsheet.dennyzhang.com/cheatsheet-openshift-a4

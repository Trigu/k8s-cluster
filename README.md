# k8s-cluster

```bash
- control 
 |- worker1
 |- worker2 
```

spin up three node cluster

* requirements
```
vagrant
virtualbox
```
To start vms 
```
./create-cluster.sh
```
Then login to each node run  as root respectively

`./kubernetes/setup-docker.sh`

`./kubernetes/setup-kubetools.sh`

To clean up
```
clean-up.sh
```
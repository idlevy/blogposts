### Kubernetes ingress: use the GCE built-in nginx controllers in GKE [2/3]

This folder  contains the YAML files required to run the tutorial in this blogpost -> https://medium.com/p/117653d9f7c3

* Clone this repo and cd into this directory

* Connect to the target k8s cluster

* run `#$ create -f 00_backends.yaml` to creates the required backends 

* run `#$ create -f 01_ingress-gce.yaml` to create the ingress in front of the previous backends

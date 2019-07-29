# RethinkDB Image and Kubernetes files

This is the Docker image that's the basis for a Kubernetes RethinkDB Cluster. Ignore files in the the /old folder. They should not be needed if the following instructions are followed.

##Installation
###Build and upload image
Build the image and push it to an accessible repository:

```docker build -t <myrepo>/rethinkdb-cluster```

###In Rancher 2:
Create persistent volumes, either by using the /old/blah.yml or directly in Rancher2

# Kubernetes
This is just a repository in which I keep track of all the things I run in my home k8s cluster, so probably not interesting for anyone but me. 

# Setup secrets
NOTE: add secrets folder to .gitignore
Copy all template_secrets folder to a secrets folder in the same directory.
Specify the values in the .yaml files in the newly created secrets folders.

Then apply the files using: kubectl apply -f ...
### How to getting started with AWS cdk8s
```text
Today AWS just announced the cloud development kit for k8s

My hands on try on it, Documentation is lil confusing
My attempt to make it even much easier
```

### Steps that followed
```text
Start with a blank project, 
# cdk8s init 
Mention the TYPE as "python-app", "typescript-app"

So you need to run
# cdk8s init python-app hello-world

This above commands will create folder structure, then run
# pipenv install
# cdk8s import --language python

Add the python code in the main.py, then run
# cdk8s synth

This will create the deployment yaml of the python code



```
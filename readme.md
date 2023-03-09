# The K3S-HA Cluster Maker
This is a flexible Cluster maker program 
 
You can make the folowing clusters :
1. K3S-HA Cluster with muntiple Master Nodes and Multiple worker Nodes
2. K3S Cluster with one Master Nodes and Multiple worker Nodes
3. K3S Minimal Cluster with only a master Node

## This ships as two Python files and a Configuration yaml file
This is shipped as a Python program and also as a linux script.

These read the AllNodesConfig.yaml and generates the schedule text file for you 
to use to create your cluster

## To Configure the Cluster you want to create 
Edit the AllNodesConfig.yaml configuration file
```
nano AllNodesConfig.yaml
```
Now only populate the nodes you want and delete the ones you don't want in this file


## To run this program from Python
```
python3 k3s-cluster-maker.pyz AllNodesConfig.yaml
```

## To run this program using Linux Executable script

```
./k3s-cluster-maker-4-linux.pyz
```

## Tools used

### JSON Formatter validator
https://jsonformatter.curiousconcept.com/

### JSON to YAML Converter
https://www.json2yaml.com/


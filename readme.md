# The K3S-HA Cluster Maker
This is a Python program and a linux script that reads the AllNodesConfig.yaml and generates the schedule text file for you 
to use to generate the cluster

You only populate the nodes you want and delete the ones you don't want

## JSON Formatter validator
https://jsonformatter.curiousconcept.com/

## JSON to YAML Converter
https://www.json2yaml.com/

## To run this program
```
python3 k3s-cluster-maker.pyz AllNodesConfig.yaml
```

## To make this file Linux Executable

Put this ontop of the file
```
#!/usr/bin/env python3
```

And run this command
```
chmod +x k3s-cluster-maker.pyz
```




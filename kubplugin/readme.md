
## Script: kubplugin

The `kubplugin` script is a Bash script that allows you to retrieve resource usage statistics from Kubernetes and display them in a formatted manner. It accepts the following command-line arguments:

1.  `RESOURCE_TYPE`: Specifies the type of resource for which you want to retrieve the statistics. It can be one of the valid resource types in your Kubernetes cluster, such as `pods`, `nodes`, or `deployments`.

### Usage

To use the `kubplugin` script, follow these steps:
1. wget https://raw.githubusercontent.com/minasyanakk/scripts/main/kubplugin/kubplugin
2. chmod +x kubplugin
3. bash kubplugin pods argocd

### Output

The script will output the resource usage statistics in the following format:

Resource, Namespace, Name, CPU, Memory


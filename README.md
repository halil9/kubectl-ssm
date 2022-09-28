# kubectl-ssm

`kubectl-ssm` is a kubectl plugin that it provides to connect for your private nodes over AWS. 

## Requirements

- ssm plugin [installation documantation](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html)
- aws-cli
- awk command
- ssm role for nodes


for the usage, it is enough that you can just copy it to your executable file system.

```$ chmod +x ./kubectl-ssm```<br />
```$ mv ./kubectl-ssm /usr/local/bin```<br />
```$ kubectl ssm``` // it will list all worker nodes in your cluster.
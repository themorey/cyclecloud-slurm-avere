# CycleCloud Template to Mount Avere and create multiple NodeArrays/Partitions

This Slurm template includes 2 Avere mounts and multiple (5) nodearrays/partitions

Note this template does not install Avere, it only mounts preconfigured Avere namespace/junctions/exports

Download this file to your local computer or Azure Cloud Shell (wherever CycleCloud CLI is installed) and run the following command:

`cyclecloud import_template -f slurm-avere.txt --force`

NOTE:  the cluster creation will fail if it can not mount the Avere mounts as built in the template.

# Single Region High Availability Lab 
## Step 1 - Connect to the Azure Cloud Shell

In this lab we will be using the [Azure Cloud Shell](https://docs.microsoft.com/en-us/azure/cloud-shell/overview). This provides us the ability to use the Azure CLI 2.0 from within our browser without needing to install anything locally (PowerShell support coming soon). You can also use the Azure CLI 2.0 from the console on your computer ([More Info](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)). Additionally everything we are doing can also be done via the Portal, PowerShell or an ARM Template, however we will be focusing on the Azure CLI 2.0 commands in this lab.  

Lets begin by logging into the [Azure Portal](https://portal.azure.com). Once you are in, select the icon to launch the Cloud Shell in the upper right.

![Icon](./img/shell-icon.png)

You will now see a console at the bottom of your browser window. Here you will enter the commands below to complete the lab. 

Let's start by asking for some help from the Azure CLI 2.0. Enter the following command at the promt and observe the output. 

```
az -h
```

As you see adding the `-h` switch to the end of any Azure CLI 2.0 command will output the help file for that command. Lets investigate help a bit more, try the following command.

```
az vm -h
```

As you can see `vm` is a subgroup fo the `az` command, by combining them together with the `-h` switch we can find out all the things we can do with VMs in the CLI. 


## Lab Navigation
1. [Overview](./)
1. [Connect to the Azure Cloud Shell](./step01.html) *<-- you are here*
1. [Select your subscription](./step02.html)
1. [Create the Resource Group](./step03.html)
1. [Create the Availability Set](./step04.html)
1. [Create the first vm](./step05.html)
1. [Create the second VM same as the first](./step06.html)
1. [Add the load balancer](./step07.html)
1. [Look Mom its magic](./step08.html)
1. [Extending this lab and Cleanup](./step09.html)
1. [CLI commands Summary](./summary.html)

[Back to Index](../../index.html)
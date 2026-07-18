# Azure-Networking
Playing with Azure Network
# Azure Virtual Network Creation using Azure CLI

## Objective
Create an Azure Virtual Network (VNet) using Azure CLI.

## Azure CLI Command

```bash
az network vnet create \
  --resource-group MyResourceGroup \
  --name MyVNet \
  --address-prefix 10.0.0.0/16 \
  --subnet-name MySubnet \
  --subnet-prefix 10.0.1.0/24
```

## Output Screenshot

![VNet Created](screenshots/vnet-created.png)

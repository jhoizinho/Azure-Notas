# Comandos úteis do Azure CLI

## Autenticação

```bash
az login
az account show
az account list --output table
```

## Grupos de recursos

```bash
az group create --name MeuGrupo --location eastus
az group list
az group delete --name MeuGrupo
```

## Máquinas Virtuais

```bash
az vm create \
  --resource-group MeuGrupo \
  --name MinhaVM \
  --image UbuntuLTS \
  --admin-username usuario \
  --generate-ssh-keys
```

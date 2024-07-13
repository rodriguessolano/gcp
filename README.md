# gcp
Labs GCP



# Criar cluster GKE

> Status do projeto: Em desenvolvimento

Para rodar esse projeto na sua máquina, por favor digite:  

```
gcloud config set project sft-lab-solano#&NOME_DO_PROJETO
```

```
gcloud config set compute/zone us-east1 #$ZONA_PARA_CRIAÇÃO_DO_CLUSTER
```

```
gcloud container clusters create-auto cluster-gke --network=vnet-lab-01 --subnetwork=sub-linux
```

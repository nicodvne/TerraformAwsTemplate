# Terraform X AWS

> Cette documentation est a utiliser uniquement dans le cas ou les CLI AWS et Terraform sont installées sur la machine hôte
> 

## Initialisation du projet

1. Mise en place de la config AWS sur la CLI en local
    
    Ajout de la config récupérée sur AWS dans le fichier suivant :
    
    ```bash
    $HOME/.aws/credentials
    ```
    
2. Mise en place des variables d’environnements nécéssaires a Terraform 
    
    ```bash
    export AWS_ACCESS_KEY_ID=<<AWS_ACCESS_KEY_VALUE>>
    export AWS_SECRET_ACCESS_KEY=<<AWS_SECRET_ACCESS_KEY_VALUE>>
    ```
    
3. Initialisation du projet Terraform 
    
    ```bash
    terraform init
    ```
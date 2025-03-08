# Azure RBAC-Personalized-Stop-Start-VMs
RBAC Personalized to Stop, Start and Deallocate VMs

Este scritp em json pode ser util no seu ambiente de Azure para ser específico para um usuário somente realizar o Stop, Start e Deallocate das Virtual Machines.

No parâmetro: "assignableScopes": [
            "/providers/Microsoft.Management/managementGroups/HML"
        ],

Substitua pelo seu Management Group, Subscription ou Resource Group.



Importe esse script através do RBAC custom role e depois configure os usuários ou grupos que irão ter essa role atribuída.

##################

This JSON script can be useful in your Azure environment to be specific to a user only to perform Stop, Start and Deallocate of Virtual Machines.

Import this script through the RBAC custom role and then configure the users or groups that will have this role assigned.

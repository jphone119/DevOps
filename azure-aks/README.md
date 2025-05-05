Azure AKS Portal Information:

Portal link: https://portal.azure.com

Use the AKS documentation for reference: https://learn.microsoft.com/en-us/azure/aks/
Require tools installation documentation: https://azure.github.io/kubelogin/install.html

Step-by-Step
1. Once login in to the Azure Portal with the account, search for "Kubernetes Services"
2. Click on the "Kubernetes Services", you should a active cluster.
3. Click the "Connect" button for instructions
4. Click on the "Azure CLI", use the Azure CLI instructions and install the required tools
6. For first time connection, you may encounter an error if you try to do anything.
7. Switch to your namespace using the following command. Replace the number with your account.
	- k config set-context aks-lab-001 --namespace abc123
8. You should now able to deploy and get pods running.




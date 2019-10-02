# VeeamOnAzureLab
Contents:<br>
This lab is conducted as a guided workshop to give partner technical resources hands-on experience with Veeam Backup & Recovery and Microsoft Azure. The repo contains the following resources:<br><br>
<b>Veeam Lab Guide.pptx</b> - Start here for lab instructions<br>
<b>azuredeploy.json</b> - The ARM template to deploy Azure environment to run the lab.<br>
<b>azuredeploy.parameters.json</b> - Optional parameters file (not required for normal lab setup)<br>
<b>/scripts</b> - some powershell scripts that run automatically on the deployed servers as part of the ARM deployment.<br>
<br>
Use the Deploy to Azure button below to start deploying resources to Azure. Be sure to provide a globally unique name for the parameters capStorageName and diagnosticsStorageAccountName. These are storage accounts that get created as part of the deployment, and storage accounts must have a globally unique name between 3 and 24 characters (all lowercase, no special chars).<br><br>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fyouf05%2FVeeamOnAzureLab%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fyouf05%2FVeeamOnAzureLab%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a><br>
<i><b>IMPORTANT:</b> This repo is not meant for production use and should only be used for temporary lab environment scenarios. Do not deploy these templates into any production environment.</i>
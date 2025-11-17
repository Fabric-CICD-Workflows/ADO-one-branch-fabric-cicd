# Fabric CI/CD Project Demo
This sample project is based on a workflow with a single, long-lived **main** branchg and three workspaces which are **dev**, **test** and **prod**. The sample uses Fabric GIT synch to update the **dev** workspace and then uses the **fabric_cicd** library to publish changes to the **test** workspace and the **prod** workspace.

![workflow_with_fabric_cicd](/img/workflow.png "Workflow with fabric_cicd")


To get the Azure Dev Ops piplines with CI/CD logic workflow working correctly in an Azure Dev Ops project in the cloud, you will need to add the following variables and secret to your project in a variable library and make that library accessible to the pipelines.

![workflow_with_fabric_cicd](/img/variables.png "Adding variables and secretes")
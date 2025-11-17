# Fabric CI/CD Project Demo
This sample project is based on a workflow with a single, long-lived **main** branchg and three workspaces which are **dev**, **test** and **prod**. The sample uses Fabric GIT synch to update the **dev** workspace and then uses **fabric_cicd** library to publishes changes to the **test** workspace and the **prod** workspace. 

![workflow_with_fabric_cicd](/img/workflow.png "Workflow with fabric_cicd")
CloudFormation template for a Multi-AZ Cloud Foundry deployment to AWS

In a nutshell, a CloudFormation script with a sensible set of defaults that allows for customisation of all network ranges, optional IAM user creation, and basically implements this:

![](pcf_ha_diagram.png)


**NON PRODUCTION USE ONLY**

The RDS database instance deployed by this script is **not** configured for Multi-AZ nor backups. Either modify this template to suit your needs or provision RDS separately and leave the RDS fields in this template blank (so it doesn't create an RDS instance at all).

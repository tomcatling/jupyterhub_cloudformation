# jupyterhub_cloudformation

A set of CloudFormation templates to provision a JupterHub environment within a VPC where the Hub acts as a gateway.

Each user has an associated Role which is also applied to the instance profile for their Server. An EFS instance is also created for each
user as part of the Users stack, allowing work to persist across Server shutdowns.

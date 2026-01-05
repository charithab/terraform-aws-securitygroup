#Security Group Module
This module is created for Practice purpose. Project create security group using this module.

##Inputs
* sg_name(Required): The project name for which the security group is created
* sg_description(Required): The project purpose for which the security group is created.
* project(Required): The project name
* Environment(Required): The environment for which the project is created.
* sg_tags(optional): Tags related to the security group.
* vpc_id(Required): The vpc id in which the instance is created.

##Outputs
* sg_id - Exports sg_id created
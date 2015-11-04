About
=====

This is the platform pattern designed for using CloudConductor(http://cloudconductor.org) CC_CLI to build a Single Wordpress Website.

*tempate.json file content is same with WordPress_Single_Instance of AWS's CloudFormation template (https://s3-us-west-1.amazonaws.com/cloudformation-templates-us-west-1/WordPress_Single_Instance.template).
*task.yml is changed to do nothing by run script "exit 0"
*other file is coppied of Tomcat_Pattern of CloudConductor's Sample pattern (https://github.com/cloudconductor-patterns/tomcat_pattern).

Conclusion
=====
So, we can know that CloudConductor can execute a CloudFormation Template file, and can release, deploy an application withuot running cc_cli release and deploy command.

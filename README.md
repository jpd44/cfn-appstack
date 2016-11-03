# cfn-appstack
Cloudformation template (JSON) for a simple application stack.

Included is a simple bash script, provisionCloudFormation, which is just a wrapper around the cloudformation CLI.
Example with your template in the current directory:
./provisionCloudformation.sh dixonaws@amazon.com cfn-appstack.template.json

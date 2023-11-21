# NOTES

Update running stack:

https://stackoverflow.com/questions/46824171/how-do-i-force-a-cloudformation-stack-to-update-when-the-parameter-is-updated

aws cloudformation update-stack --stack-name MyStack --template-body file:///Users/Documents/Git/project/cloudformation/stack.json --parameters file:///Users/Documents/Git/project/cloudformation/parameters/stack-parameters.dev.json --capabilities CAPABILITY_IAM


------------



# Reference

- https://github.com/vatertime/minecraft-spot-pricing
- https://github.com/Finntaur/aws-cloudformation-minecraft
- https://github.com/thilinaba/eks-cloudformation
    - with: https://medium.com/cloud-life/organize-cloudformation-templates-with-external-parameters-file-7998098f1b8d




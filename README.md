# aws-patchingapproval

**Problems to solve**
1. Sending relevant patching information to business units
2. Asking for approval from business units to proceed with the patching process
3. Automatically create a maintenance window for patching activities
4. Sending notifications for patching results

**Solution**

The solution is to use AWS Systems Manager's automation feature to achieve the above purpose. SSM automation doucment will be created to conduct each step required in the patching process.

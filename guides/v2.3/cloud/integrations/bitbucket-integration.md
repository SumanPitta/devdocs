../../../v2.2/cloud/integrations/bitbucket-integration.md

In case if you accidentally delete the Integration branch in Magento cloud UI due to having a different branch structure in your Bitbucket, then 
1. Create Integration (branch it from the Master) in the Magento project UI
2. Then in your Bitbucket, you should create the identical project tree as in the Magento project UI
3. Git push from your local development machine to your Bitbucket's “Integration” branch

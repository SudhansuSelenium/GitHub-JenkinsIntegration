# GitHub-JenkinsIntegration
This is about GitHub integration with Jenkins and trigger build automatically

1. Install Git Integration plugin in Manage Plugin
2. Create new Freestyle Project
3. In General tab click GitHub project give the url eg. https://github.com/SudhansuSelenium/GitHub-JenkinsIntegration
4. In Source Code Management tab select Git and give repository url eg. https://github.com/SudhansuSelenium/GitHub-JenkinsIntegration.git
5. In Build trigger tab select GitHub hook trigger for GITScm polling
6. In Git repo setting select Webhooks-->click Webhook button
7. Give payload URL eg. localhost:8080/job/testing
8. Select content type as application/json-->click Add Webhook
9. Thats all.. Thanks

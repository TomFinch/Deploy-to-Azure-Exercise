# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

#### App Service cost less and has more availability zones compared to VM, and an App Service is easier to scale because Azure offer better support for it. 
#### An App Service is the appropriate option here, because this is a lightweight app and does not require much compute 

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

#### If the App when deployed begins to require a higher storage capacity, the storage capacity would need to be extended beyond what was initially set.
#### If I require more control over the compute resources, VM would be a better option.
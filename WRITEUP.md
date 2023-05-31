# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I decided to choose App Services for the following reasons:
- With less demand, the cost of App Service is cheaper than VM. App Serice is offer a free tier, with needs for development and testing
- With provide automatic scaling, which allows your app to handle more traffic without manual intervention. VMs require manual scaling, which can be time-consuming and may result in downtime
- With App Services, I don't care about infrastructure, I only care about software development.
- App Services have built-in high availability and can automatically recover from failures. VMs require manual configuration for high availability
- With App Services, easily to setup CI/CD with Git/GitHub, Azure DevOps.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 


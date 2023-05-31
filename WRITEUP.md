# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

I decided to choose App Services for the following reasons:
- With less demand, the cost of App Service is cheaper than VM. App Serice is offer a free tier, with needs for development and testing
- With provide automatic scaling, which allows your app to handle more traffic without manual intervention. VMs require manual scaling, which can be time-consuming and may result in downtime
- With App Services, I don't care about infrastructure, I only care about software development.
- App Services have built-in high availability and can automatically recover from failures. VMs require manual configuration for high availability
- With App Services, easily to setup CI/CD with Git/GitHub, Azure DevOps.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

- Complexity and customization: If your app requires a more complex setup, custom configurations, or specific software installations that are not supported by App Service, you might lean towards using a VM. VMs provide more control over the environment and allow you to configure it according to your needs.
- Resource usage: If your app starts to consume more resources (CPU, memory, storage) or experiences significant fluctuations in resource usage, you might want to consider using a VM. VMs can be more easily scaled vertically (by increasing the resources of a single instance) compared to App Services.
- Potentially higher costs: If you need to upgrade a portion of your App tier, such as storage, you must upgrade to the next plan tier. This may result in higher costs and underutilized resources


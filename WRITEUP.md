# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Costs
Azure VMs: Generally, VMs can be more cost-effective for resource-intensive workloads. However, they require you to manage the infrastructure, including OS patches, security, and scaling.
Azure App Service: This can be more expensive for production-level services but simplifies infrastructure management. For example, a P1v3 plan costs around $275.21 per month.

Scalability
Azure VMs: Scaling VMs requires manual intervention or setting up scale sets, which can be complex.
Azure App Service: Offers easier scalability with built-in auto-scaling features, making it ideal for web applications that need to handle varying loads.

Availability
Azure VMs: You have full control over the infrastructure, which can be beneficial for applications requiring specific configurations. However, this also means you are responsible for ensuring high availability.
Azure App Service: Provides high availability out-of-the-box, with built-in load balancing and failover capabilities.

Workflow
Azure VMs: Suitable for applications needing custom configurations or legacy systems. However, it requires more management and maintenance.
Azure App Service: Ideal for modern web applications and APIs, allowing developers to focus on code rather than infrastructure.

Recommendation
For a CMS app, Azure App Service is generally the better choice. It offers easier scalability, high availability, and simplifies the workflow by abstracting infrastructure management. This allows your team to focus on developing and maintaining the application rather than managing servers

App URL: https://udacitycms-d3g5bshya0b3a5dc.canadacentral-01.azurewebsites.net/login

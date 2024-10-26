VM: 
- Costs: more expensive due to infrastructure management costs and resource allocation.
- Scalable: via Virtual Machine Scale Sets and Load Balancers, but can be complex.
- Availability: high availability requires manual configuration.
- Workflow: allow you full access and control of the VM, requires maintenance.
=> providing full control over the OS and software, suitable for apps with specific configurations or legacy needs. Requires manual updates and maintenance.
App Service: 
- Costs: lower upfront costs, but need to pay for the service plan even when not in use.
- Scalable: easy adjusts resources based on demand, making it easier to handle traffic spikes with minimal setup..
- Availability: built-in high availability and load balancing managed by Azure.
- Workflow: focus on application development; Azure manages the infrastructure.
=> A managed platform  web apps and APIs, offering autoscaling, load balancing, and streamlined deployment. Ideal for modern web apps needing minimal maintenance.

In this project: 
    Deploy source, monitoring and logs activity and minimal maintenance.
    => App Service easier to do and suitable for this project
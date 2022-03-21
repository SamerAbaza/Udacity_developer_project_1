# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

##Answer:
For VM; VMs provide IAAS where it provides:

- Hardware.
- OS and software installed.
- support linux and windows.
- flexible types and size availability of CPU, RAM and storage 
- Spin up from 1 virtual CPU tp 100 cpus using VM scale sets and load balancers.

But:
- More expensive than app service
- full responsibility of maintenance and scaling should be considered
- labor intensive and time consuming

For APP service; it represents PAAS where it provides:

- High availability and supports multiple languages
- auto scaling, vertical and horizontal
- supports CD
- provides large set of service plans with free tier

But:

- Hardware limitations Ram and CPUs
- Limited access to host server(installing softwares and Os)
- always paying for service plan

#Choice:
I have chosen App service to deploy the image for my application 
where the deployed application is considered to be light with no requirements of high performance
and free tier is selected to remove extra payments required for test environment.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

## Answer:

I would go to VM when I need full control to OS and customsoftware and in case of high-performance required 
aswell as spinning up and down based on the required load (requests).

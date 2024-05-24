# Describe Azure virtual machines

## Virtual machines provide infrastructure as a service (IaaS)

- Virtualized server in the cloud
- Total control over the operating system (OS)
- Ability to run custom software
- Use custom hosting configurations

## Advantages of Azure VMs

- Flexibility of virtualization without owning physical hardware
- Rapidly provision VMs from pre-configured images
- Customize all software on the VM

## Scale VMs in Azure

### Virtual machine scale sets

- Create and manage a group of identical, load-balanced VMs
- Automatically scale number of VMs up or down based on demand or schedule
- Automatically deploys a load balancer

### Virtual machine availability sets

- Build a resilient, highly available environment
- Groups VMs across update domains and fault domains
- Update domains: VMs rebooted together during updates
- Fault domains: VMs grouped by common power and network resources

## Examples of when to use VMs

- Testing and development
- Running applications in the cloud
- Extending datacenter to the cloud
- Disaster recovery
- Migrating from physical servers (lift and shift)

## VM Resources

- Size (purpose, cores, RAM)
- Storage disks (HDD, SSD)
- Networking (virtual network, IP, ports)

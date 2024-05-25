# Describe Azure Storage Services

## Azure Blobs

- Massively scalable object store for text and binary data
- Includes support for big data analytics through Data Lake Storage Gen2
- Ideal for:
- Serving images or documents directly to a browser
- Storing files for distributed access
- Streaming video and audio
- Storing data for backup/restore, disaster recovery, and archiving
- Storing data for analysis by on-premises or Azure-hosted services

## Azure Files

- Managed file shares for cloud or on-premises deployments
- Accessible via SMB or NFS protocols
- Key benefits:
- Shared access with industry standard protocols
- Fully managed, no need to manage hardware or OS
- Scripting and tooling with PowerShell, CLI, portal, and Azure Storage Explorer
- Resiliency and high availability
- Familiar programmability with file system I/O APIs

## Azure Queues

- Service for storing large numbers of messages
- Messages can be accessed from anywhere via HTTP/HTTPS
- Commonly used to create a backlog of work to process asynchronously
- Can be combined with Azure Functions to trigger actions when messages are received

## Azure Disks

- Block-level storage volumes managed by Azure for use with Azure VMs
- Virtualized disks offering resiliency and availability
- Managed by Azure, you only need to provision the disk

## Azure Tables

- NoSQL datastore for structured, non-relational data
- Accepts authenticated calls from inside and outside Azure cloud
- Ideal for storing structured, non-relational data

## Benefits of Azure Storage

- Durable and highly available with redundancy and replication
- Secure with encryption and access control
- Scalable to meet data storage and performance needs
- Managed by Azure, handling maintenance and updates
- Accessible from anywhere via HTTP/HTTPS, with client libraries and REST API

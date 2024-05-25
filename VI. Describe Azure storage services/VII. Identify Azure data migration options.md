# Identify Azure data migration options

## Azure Migrate

Azure Migrate is a service that helps you migrate from an on-premises environment to the cloud. It provides:

- **Unified migration platform**: A single portal to start, run, and track your migration to Azure.
- **Range of tools**: A range of tools for assessment and migration, including:
- Azure Migrate: Discovery and assessment
- Azure Migrate: Server Migration
- Data Migration Assistant
- Azure Database Migration Service
- Azure App Service migration assistant
- **Assessment and migration**: In the Azure Migrate hub, you can assess and migrate your on-premises infrastructure to Azure.

### Integrated Tools

- **Azure Migrate: Discovery and assessment**: Discover and assess on-premises servers running on VMware, Hyper-V, and physical servers in preparation for migration to Azure.
- **Azure Migrate: Server Migration**: Migrate VMware VMs, Hyper-V VMs, physical servers, other virtualized servers, and public cloud VMs to Azure.
- **Data Migration Assistant**: A stand-alone tool to assess SQL Servers, pinpoint potential problems blocking migration, identify unsupported features, new features that can benefit you after migration, and the right path for database migration.
- **Azure Database Migration Service**: Migrate on-premises databases to Azure VMs running SQL Server, Azure SQL Database, or SQL Managed Instances.
- **Azure App Service migration assistant**: A standalone tool to assess on-premises websites for migration to Azure App Service. Use Migration Assistant to migrate .NET and PHP web apps to Azure.
- **Azure Data Box**: Use Azure Data Box products to move large amounts of offline data to Azure.

## Azure Data Box

Azure Data Box is a physical migration service that helps transfer large amounts of data (up to 80 TB) in a quick, inexpensive, and reliable way. A proprietary Data Box storage device is shipped to your datacenter, where you can transfer data to or from it, and then ship it back to Microsoft.

### Use Cases

- **One-time migration**: Move a large amount of on-premises data to Azure (e.g., media library, VM farm, SQL server, applications, historical data).
- **Initial bulk transfer**: Perform an initial bulk transfer using Data Box, followed by incremental transfers over the network.
- **Periodic uploads**: Move large amounts of data generated periodically to Azure.
- **Disaster recovery**: Export a copy of data from Azure to an on-premises network for disaster recovery.
- **Security requirements**: Export data out of Azure due to government or security requirements.
- **Migrate back**: Move all data back to on-premises or to another cloud service provider.

After data is uploaded or exported, the disks on the device are wiped clean in accordance with NIST 800-88r1 standards.

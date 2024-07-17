## Azure Storage:
# Learning objectives
After completing this module, you’ll be able to:

Compare Azure storage services.
Describe storage tiers.
Describe redundancy options.
Describe storage account options and storage types.
Identify options for moving files, including AzCopy, Azure Storage Explorer, and Azure File Sync.
Describe migration options, including Azure Migrate and Azure Data Box.

## The Azure Storage platform includes the following data services:

- Azure Blobs: A massively scalable object store for text and binary data. Also includes support for big data analytics through Data Lake Storage Gen2.
- Azure Files: Managed file shares for cloud or on-premises deployments.
- Azure Queues: A messaging store for reliable messaging between application components.
- Azure Disks: Block-level storage volumes for Azure VMs.
- Azure Tables: NoSQL table option for structured, non-relational data.

# Storage service	Endpoint
- [Blob Storage]	https://<storage-account-name>.blob.core.windows.net
- [Data Lake Storage Gen2]	https://<storage-account-name>.dfs.core.windows.net
- [Azure Files]	https://<storage-account-name>.file.core.windows.net
- [Queue Storage]	https://<storage-account-name>.queue.core.windows.net
- [Table Storage]	https://<storage-account-name>.table.core.windows.net

## Benefits of Azure Storage
Azure Storage services offer the following benefits for application developers and IT professionals:

- Durable and highly available. Redundancy ensures that your data is safe if transient hardware failures occur. You can also opt to replicate data across data centers or geographical regions for additional protection from local catastrophes or natural disasters. Data replicated in this way remains highly available if an unexpected outage occurs.
- Secure. All data written to an Azure storage account is encrypted by the service. Azure Storage provides you with fine-grained control over who has access to your data.
- Scalable. Azure Storage is designed to be massively scalable to meet the data storage and performance needs of today's applications.
- Managed. Azure handles hardware maintenance, updates, and critical issues for you.
- Accessible. Data in Azure Storage is accessible from anywhere in the world over HTTP or HTTPS. Microsoft provides client libraries for Azure Storage in a variety of languages, including .NET, Java, Node.js, Python, PHP, Ruby, Go, and others, as well as a mature REST API. Azure Storage supports scripting in Azure PowerShell or Azure CLI. And the Azure portal and Azure Storage Explorer offer easy visual solutions for working with your data.

## Azure Blob storage is ideal for:

- Serving images or documents directly to a browser.
- Storing files for distributed access.
- Streaming video and audio.
- Storing data for backup and restore, disaster recovery, and archiving.
- Storing data for analysis by an on-premises or Azure-hosted service.

## AZURE STOREAGE TIERS:

Azure Storage offers different access tiers for your blob storage, helping you store object data in the most cost-effective manner. The available access tiers include:

# Hot access tier: 
Optimized for storing data that is accessed frequently (for example, images for your website).
# Cool access tier: 
Optimized for data that is infrequently accessed and stored for at least 30 days (for example, invoices for your customers).
# Cold access tier: 
Optimized for storing data that is infrequently accessed and stored for at least 90 days.
# Archive access tier: 
Appropriate for data that is rarely accessed and stored for at least 180 days, with flexible latency requirements (for example, long-term backups).
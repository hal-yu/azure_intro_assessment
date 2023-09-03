# Part 2: Azure Exploration

## A & B. Identify Services and Provide Description 
### Database Services
1. Azure Cosmos DB: Globally distributed database designed to enable developers to build modern applications at any scale using a fast NoSQL database with open APIs. It offers single-digit millisecond response times, automatic and instant scalability, along with guarenteed speed at any scale. It is beneficial by providing automatic management, updates, and patching.
2. Azure SQL Database: Fully managed cloud-based relational database service to deploy and operate SQL server database. It handles database management functions such as upgrading, patching, backups, and monitoring. It offers high availability, performance, and sacalability and process non-relational database structures. 

### Storage Services
1. Managed Disks: A type of storage with high performance, durable block storage for Azure Virtual Machines with simplified management
2. Blob Storage: A cloud-based object storage for any type of unstructured data.

### Computing Services
1. Batch: A cloud-scale job scheduling and compute management. It allows for efficiency in running large-scale high perofmrance computing workloads in the cloud and manages tasks across virtual m achines or other resources.
2. Azure Web Apps: Cloud computing based platform for to quickly create and deploy critical web apps at scale. It is fully managed for building and hosting web applications using popular programming languages and developers can use different kinds of mobile applications or web applications.

## C. Python Interaction: 
### Database Services
1. Azure Cosmos DB: You can use Cosmos DB using Python applications can store and query JSON documents in a NoSQL data store. Use [pip install azure-cosmos] to install Azure Cosmos DB for Python. Then you have to connect Azure Cosmos DB using what you have installed to perform database operations. 
2. Azure SQL Database: You need to install the required libraries [pip install pyodbc] and import it. To configure the database, you need to go to the network page of server, add client IPv4 address and check the "allow azure services and resources to access this server." In the Azure Active Directory, find the Azure Directory and find the admin account and create a connection string using python. Python can create a table during startup, retreive records, and define functions to the database. 

### Storage Services
1. Managed Disks: You have to install the Azure SDK for managing Azure resources using [pip install azure-mgmt-disk]. This allows python to create, manage, attatch, detach, and interact with Azure Managed Disks programmatically. 
2. Blob Storage: You have to install teh Azure SDK for managing Blob Storage using [pip install azure-storage-blob]. This allows python to work with Azure Blob Storage and upload, download, list, or delete blobs. 

### Computing Services
1. Batch: install the client library [pip install azure-batch] to configure nodes, define and submit tasks, and run them in jobs. 
2. Azure Web Apps: Create a web application and using python, you can support the web framework like Flask or FastAPI. 
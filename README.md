# GSynergy
Downloaded all hierarchical and factual data from the drive to the local system.
Installed the Self-Hosted Integration Runtime (SHIR) locally.
Created a new Azure Resource Group, Azure Data Factory (ADF), and a folder in the ADLS container.
In ADF, navigated to Manage and create a new Self-Hosted Integration Runtime. Retrieved the authentication key from Azure Integration Runtime and added it to the locally installed Self-Hosted Runtime. Then, launched the Configuration Manager.
Configured the source by using File System as the Linked Service and provided the ADF Integration Runtime details, along with the local folder path, username, and password.
Used Azure Storage Explorer to load some files into the ADLS container.

# Azure Batch HPC (Big Compute) Lab
* Microsoft EMEA Big Compute (HPC) Team - <mailto:EMEAGBBBigComputeTSP @ microsoft.com>
* Initial versions by Karl Podesta, September 2017

## 1. Introduction

### 1.1  The Lab
This is a technical lab to help you get started with Azure Batch. You will log in to Azure, initiate Azure Batch, and run a few jobs.  You will learn about some of the different methods for doing this, and some of the different jobs you could run.  You will also learn where to get more information, and how to dig deeper for your particular use case.  The Lab should take approx 90 minutes to complete.  

Please share any thoughts, feedback, or improvements - this is a work in progress, and we want to make sure it helps you to get started in the right way with Azure Batch! 

### 1.2  Azure Batch
Azure Batch is a scalable job scheduling system leveraging the Microsoft Azure Cloud. Users can specify what their jobs are (e.g., executing a binary to process text data), when to run them, where to run them, and on what VM resources they are run on. The Azure Batch service takes care of the rest including: compute resource provisioning, task scheduling, automatic task recovery and retry on failure, automatic scaling of resources if specified, and many other complexities that exist at cloud-scale. There is no extra cost to use Azure Batch - Azure Batch is provided as a free value-added service on top of compute resources in Azure. Costs are incurred only for compute resources consumed and any assoicated datacenter data egress and storage costs, i.e., the same cost as if consuming Virtual Machines or Cloud Services directly.
Azure Batch can handle workloads on any point of the parallel and distributed processing spectrum, from embarassingly parallel workloads all the way to tightly-coupled message passing codes such as MPI jobs on Infiniband/RDMA.
If this is your first time with Azure Batch, you might want to read the <a href="https://docs.microsoft.com/en-us/azure/batch/batch-technical-overview">Azure Batch Overview</a> to get familiar with the concepts of Pools, Jobs, and Tasks. 

## 2. Install & Setup

The following steps will be needed for setup:
1. Login to Azure
2. Create an Azure Batch account (or use an existing one)
3. Create an Azure Storage account (or use an existing one)
4. Change/Review Azure limits
5. Download the "Batch Labs" GUI tool (beta) [optional]
6. Download the "Storage Explorer" GUI tool
7. Create a workstation (and connect to it)

### 2.1 Login to Azure
You can access Azure via <a href"https://portal.azure.com">https://portal.azure.com</a>.  You may have a subscription already.  If not, you can sign up for a subscription. 

### 2.2 Create an Azure Batch account (or use an existing one)
In the Azure Portal, go to "+ New", type "Azure Batch", and select "Batch Service". Click "create" and enter an account name, and a resource group where this Azure Batch account will live.  Full details for creating an Azure Batch account are at this link: <a href="https://docs.microsoft.com/en-us/azure/batch/batch-account-create-portal">Create Azure Batch</a>. 

### 2.3 Create an Azure Storage account (or use an existing one)
In the Azure Portal, go to "Storage accounts", click "+ Add", and enter the details.  You should only need to enter a "Name" and a "Resource Group" - the other default values should be fine. 

### 2.4 Change/Review Azure limits
There are default quotas and limits that apply to your Azure Batch account.  See here for more information: <a href="https://docs.microsoft.com/en-us/azure/batch/batch-quota-limit">Azure Batch Quotas and Limits</a>. 
You can find further details on that webpage for changing these quotas.  For our workshop, we can use the quotas we have already. 

### 2.5 Download the "Batch Labs" GUI tool (beta) 
You can download a recent build of "Batch Labs" for Windows from this GitHub repository. 
If you want to get the very latest version, and compile the code yourself, the link for that is here: <a href="https://github.com/Azure/BatchLabs/releases">Azure Batch Labs (beta)</a>.

### 2.6 Download the "Azure Storage Explorer" GUI tool
This is a nice GUI tool you can use to interact with your storage on Azure.  You can download it from here: <a href="https://azure.microsoft.com/en-gb/features/storage-explorer/">Azure Storage Explorer</a>. 

### 2.7 Create a workstation
In order to develop your Azure Batch job, and submit your job, you will do this from a workstation.  The following link will allow you to create a (Linux - Ubuntu 17.04) workstation in Azure, with all the dependencies you need. You can click on the "Deploy to Azure" button, and the workstation will take a few minutes to deploy.  Once it is deployed, you can inspect the connection details (public IP address, with the username and password you entered), and connect to this via SSH (e.g. if on Windows, you can use "PuTTY" software to connect).  The link is here: https://github.com/mkiernan/bigcomputebench
__Warning: you may want to shut down your Linux workstation when you complete the lab, as there is no security configured__

## 3. Access & Use

## 4. Azure Batch Shipyard

## 5. Scaling & Measurement

## 6. Scenarios
* __Azure Batch for Rendering:__ https://docs.microsoft.com/en-us/azure/batch/batch-rendering-service
* __Azure Batch for AI:__  
* __Data Analytics - R and doAzureParallel:__

## 7. Links & References
* <a href="https://docs.microsoft.com/en-us/azure/batch/">Azure Batch Service</a> - High level information about the Azure Batch service
* <a href="https://github.com/Azure/batch-shipyard">Azure Batch Shipyard</a> - Azure Batch + Docker containers = easy solutions!
* <a href="https://github.com/Azure/azure-batch-cli-extensions">Azure Batch CLI extensions (preview)</a> - new functionality for the Azure CLI!
* <a href="https://github.com/Azure/BatchLabs/releases">Azure Batch Labs (beta)</a> - GUI tool to monitor & manage Azure Batch workloads
* <a href="https://docs.microsoft.com/en-us/azure/storage/storage-use-azcopy">AzCopy (Windows)</a> - command line tool for copying data to Azure, fast!
* <a href="https://docs.microsoft.com/en-us/azure/storage/storage-use-azcopy-linux">AzCopy (Linux)</a> - command line tool for copying data to Azure, fast!



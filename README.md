# Azure Batch HPC (Big Compute) Lab
* Microsoft EMEA Big Compute (HPC) Team - <mailto:EMEABlackbeltHPCTSPs @ microsoft.com>
* Initial versions by Karl Podesta, September 2017

## 1. Introduction

### 1.1  The Lab
This is a technical lab to help you get started with Azure Batch. You will log in to Azure, initiate Azure Batch, and run a few jobs.  You will learn about some of the different methods for doing this, and some of the different jobs you could run.  You will also learn where to get more information, and how to dig deeper for your particular use case.  The Lab should take approx 90 minutes to complete.  

Please do share any thoughts, feedback, or improvements - this is a work in progress, and we want to make sure it helps you to get started in the right way with Azure Batch! 

### 1.2  Azure Batch
Azure Batch is a scalable job scheduling system leveraging the Microsoft Azure Cloud. Users can specify what their jobs are (e.g., executing a binary to process text data), when to run them, where to run them, and on what VM resources they are run on. The Azure Batch service takes care of the rest including: compute resource provisioning, task scheduling, automatic task recovery and retry on failure, automatic scaling of resources if specified, and many other complexities that exist at cloud-scale. There is no extra cost to use Azure Batch - Azure Batch is provided as a free value-added service on top of compute resources in Azure. Costs are incurred only for compute resources consumed and any assoicated datacenter data egress and storage costs, i.e., the same cost as if consuming Virtual Machines or Cloud Services directly.
Azure Batch can handle workloads on any point of the parallel and distributed processing spectrum, from embarassingly parallel workloads all the way to tightly-coupled message passing codes such as MPI jobs on Infiniband/RDMA.

## 2. Install & Setup
1. Login to Azure
2. Create an Azure Batch account (or use an existing one)
3. Create an Azure Storage account (or use an existing one)
4. Change/Review Azure limits
5. Download the "Batch Labs" GUI tool (beta) [optional]
6. Download the Azure CLI

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
* Azure Batch Labs (beta) - GUI tool to monitor & manage Azure Batch workloads
* <a href="https://docs.microsoft.com/en-us/azure/storage/storage-use-azcopy">AzCopy (Windows)</a> - command line tool for copying data to Azure, fast!
* <a href="https://docs.microsoft.com/en-us/azure/storage/storage-use-azcopy-linux">AzCopy (Linux)</a> - command line tool for copying data to Azure, fast!



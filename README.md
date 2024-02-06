# Azure-Data-Pipeline-Tokyo-Olympics

## Brief Description
In this project, I build a pipeline in Azure using Azure DataFactory, Azure DataBricks, Azure Synapse Analytics, Azure Storage and Azure Synapse SQL pool to perform data analysis on the 2021 Olympics dataset. Finally I connected Azure Synapse Analytics with PowerBI to build a dashboard and present findings

## Dataset Used
For this project, I worked with the 2021 Olympics dataset. This includes the information on more than 11,000 athletes competing in 47 sports for 743 Teams in the Tokyo Olympics in 2021. This dataset includes information on the participating Teams, Athletes, Coaches, and Entries by gender. 

## Tech Stack
Language: SQL
Services: Azure Synapse Analytics, Azure Storage, Azure Synapse SQL Pool,Azure DataBricks, Power BI

## Process
Create an azure storage account
Create a data factory pipeline to ingest data files from source to raw folder of azure data lake storage gen2
using azure databricks perform cleaning and transformation on the data and upload them to azure data lake storage gen2 transformed folder
Finally prepare dashboard in Power BI.
Publish Power BI dashboard in Azure synapse workspace.

## Architecture

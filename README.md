![Open-Source](https://img.shields.io/badge/Open%20Source-Good%20First%20Issue-blue?style=for-the-badge)
![Licence MIT](https://img.shields.io/github/license/msandfor/10-easy-steps?style=for-the-badge)

<p align="center">
<a href="https://codepen.io/msandfor" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/codepen.svg" alt="msandfor" height="30" width="30" /></a>
<a href="https://dev.to/msandfor" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/dev-dot-to.svg" alt="msandfor" height="30" width="30" /></a>
<a href="https://twitter.com/msandfor" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="msandfor" height="30" width="30" /></a>
<a href="https://linkedin.com/in/michellesandford" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="michellesandford" height="30" width="30" /></a>
<a href="https://instagram.com/techgirlwa" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="techgirlwa" height="30" width="30" /></a>
<a href="https://www.youtube.com/c/MichelleSandford" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/youtube.svg" alt="MichelleSandford" height="30" width="30" /></a>
</p>

** FYI: Update - I passed this exam first time, score was 840 (pass mark 700) **

<p><img align="center" src="https://github.com/msandfor/AI-100/blob/main/assets/stream-analytics-e2e-pipeline.png" alt="ASA Pipeline"></p>
<p align="center"></p>

# AI-100
A Repository created to help people prepare for the Microsoft AI-100 Exam. Details are correct for December 2020, as I prepare for an exam in January 2021 - I make no promises for the lifecycle of this repository at this time. 

Also, I'd love it if you've found this Project useful - Could you please click on the :star: for this repository.

> If you have content to add, open an issue and we'll see if it fits


## Table of Contents
* [Exam Rubric/Scoring Guide](#exam-rubric)
* [Learning Paths](#learning-paths)
* [Analyze solution requirements (25-30%)](#analyze-solution-requirements)
* [Design AI Solutions (40-45%)](#design-ai-solutions)
* [Implement and monitor AI solutions (25-30%)](#implemen-and-monitor-AI-solutions)


# Resources

## Exam Rubric / Scoring Guide

[Microsoft Certified: Azure AI Engineer Associate –Skills Measured](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3VEHf)


## Learning Paths
| Resource | Topic | Step |   
|------|--------|------------------|
| [Evaluate text with Azure Cognitive Language Services](https://docs.microsoft.com/en-us/learn/paths/evaluate-text-with-language-services/) | Learn how to use Cognitive Language Services to analyze text, determine intent, detect adult themes, and process natural language input | Step | 
| [Process and Translate Speech with Azure Cognitive Speech Services](https://docs.microsoft.com/en-us/learn/paths/process-translate-speech-azure-cognitive-speech-services/) | Learn how to implement the Speech services found in Azure Cognitive Services by performing speech-to-text transcription, synthesizing text input to speech, performing speech translation, and implementing speaker recognition in your AI infused applications | Step |  
| [Create Intelligent Bots with the Azure Bot Service](https://docs.microsoft.com/en-us/learn/paths/create-bots-with-the-azure-bot-service/) | Allowing customers to interact with computer applications in a conversational way using text, graphics, or speech, can be realized using Bots. It may be a simple question and answer dialog, or a sophisticated bot that allows people to interact with services in an intelligent manner using pattern matching, state tracking and artificial intelligence techniques well integrated with existing business services. Learn how to build a chat bot and add intelligence to the Bot by integrating QnA Maker and LUIS | Step |   
| [Process and classify images with the Azure cognitive vision services](https://docs.microsoft.com/en-us/learn/paths/process-classify-images-with-azure-cognitive-vision-services/) | Learn how to implement computer vision by exploring how to process faces in images and video, detect objects, categorize images, extract insights with video indexer service, and implement custom vision solutions | Step | 


## Analyze solution requirements (25-30%)
[My Notes on Analyze](https://github.com/msandfor/AI-100/blob/main/Analyze.md)

| Resource | Topic | Step |   
|------|--------|------------------|
| [Manage storage account access keys](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-keys-manage?tabs=azure-portal) | Map security requirements to tools, technologies, and processes | An access key provides admin access to an azure storage account |  
| [What is Azure role-based access control (Azure RBAC)?](https://docs.microsoft.com/en-us/azure/role-based-access-control/overview) | Map security requirements to tools, technologies, and processes | RBAC allows you to manage who has access to Azure resources and what permissions they have on those resources. You cannot use RBAC to provide fine-grained access to Azure tables |
| [Grant limited access to Azure Storage resources using shared access signatures (SAS)](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview) | Map security requirements to tools, technologies, and processes | Grant limited access to Azure Storage resources using Shared Access Signatures (SAS). A SAS is a URL with a token that specifies the allowed permissions |
| [Welcome to Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction) | Select the software, services, and storage required to support a solution | Step |   
| [What is Azure Databricks?](https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks) | Select the software, services, and storage required to support a solution | Step |   
| [What is Azure Data Lake Storage Gen1?](https://docs.microsoft.com/en-us/azure/data-lake-store/data-lake-store-overview) | Select the software, services, and storage required to support a solution | Step |   
| [Log Analytics tutorial](https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/log-analytics-tutorial) | Select the software, services, and storage required to support a solution | Step |   
| [What are Azure Cognitive Services?](https://docs.microsoft.com/en-us/azure/cognitive-services/what-are-cognitive-services) | Recommend Azure Cognitive Services APIs to meet business requirements | Bing Video Search API returns a list of videos that match text search criteria. Bing Visual Search API allows you to upload an image and return info about that image. Text analytics API allows you to extract key phrases from text and detect the language. Content Moderator API allows you to create a list of explicit terms to be matched against user-generated content and returns response specifying matched terms. Computer Vision API analyses images for a persons face, logo, object etc. Personaliser chooses the next video to play based on what the users watches and skips. User experience based on behaviour |   
| [What is Azure Media Services Video Indexer?](https://docs.microsoft.com/en-us/azure/media-services/video-indexer/video-indexer-overview) |  Recommend Azure Cognitive Services APIs to meet business requirements | VI API extracts insights from a video. Identifies 1M celebs. |   
| [Choosing a big data storage technology in Azure](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/data-storage) | Recommend Azure Cognitive Services APIs to meet business requirements | Cosmos DB with Table API allows you to store data a key-attribute pairs. Cosmos DB with Gremlin useful for graph-based data. Data Lake temporarily store data of any size and type. Databricks - spark based solution processes data in batches or real-time streams |   
| [Quickstart: Create your first data science experiment in Machine Learning Studio (classic)](https://docs.microsoft.com/en-us/azure/machine-learning/classic/create-experiment) | Select the software, services, and storage required to support a solution | An ML experiment allows you to add source data as input to data science models |  
| [What is the Bot Framework SDK?](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0) | Select the software, services, and storage required to support a solution | Step |   
| [Create a bot with Azure Bot Service](https://docs.microsoft.com/en-us/azure/bot-service/abs-quickstart?view=azure-bot-service-4.0) | Select the software, services, and storage required to support a solution | Intelligent bots automatically respond to user input. Use dialogs without human intervention |  
| [What is Computer Vision?](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/overview) | Select the software, services, and storage required to support a solution | Computer Vision allows you to process images and return insightful information - object, brand, face or adult content - without having to write code |   
| [What is Azure Service Bus?](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview) | Select the software, services, and storage required to support a solution | This is a cloud based messaging broker. It cannot ingest data from devices |  
| [Overview of Azure Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-overview) | Select the software, services, and storage required to support a solution | Cloud-based distributed platform that allows you to run workloads in parallel across thousands of VMs |  
| [Connecting IoT Devices to Azure: IoT Hub and Event Hubs](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-compare-event-hubs) | Select the software, services, and storage required to support a solution | IoT Hub is a bog data stream ingestion service that can process large amounts of data in parallel it supports per device provisioning and bi-directional comms. |  
| [Welcome to Azure Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-introduction) | Select the software, services, and storage required to support a solution | Stream Analytics is a real-time analytics and event processing solution that ingests data from multiple AZURE sources simultaneously npt from devices |  
| [Azure Event Hubs — A big data streaming platform and event ingestion service](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-about) | Select the software, services, and storage required to support a solution | Step |   
| [What is Azure IoT Hub?](https://docs.microsoft.com/en-us/azure/iot-hub/about-iot-hub) | Select the software, services, and storage required to support a solution | Step |  
| [What is Azure Machine Learning?](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml) | Select the software, services, and storage required to support a solutionc | An ML experiment allows you to add source data as input to data science models and make predictions |
| [Secure access to a key vault](https://docs.microsoft.com/en-us/azure/key-vault/general/secure-your-key-vault) | Map security requirements to tools, technologies, and processes | AKV allows you to securely store secrets which can be passwords or API keys. |   
| [Symmetric Keys](https://docs.microsoft.com/en-us/windows/win32/seccrypto/symmetric-keys) | Map security requirements to tools, technologies, and processes | Step |   
| [Asymmetric Keys](https://docs.microsoft.com/en-us/windows/win32/seccrypto/public-private-key-pairs) | Map security requirements to tools, technologies, and processes | Step |   
| [Manage secrets in your server apps with Azure Key Vault](https://docs.microsoft.com/en-us/learn/modules/manage-secrets-with-azure-key-vault/) | Map security requirements to tools, technologies, and processes | Step |   
| [Safe storage of app secrets in development in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-3.0&tabs=windows) | Map security requirements to tools, technologies, and processes | You should not embed the key within the applications code. If the code is compromised, so is the key. |  
| [Azure Key Vault basic concepts](https://docs.microsoft.com/en-us/azure/key-vault/general/basic-concepts) | Map security requirements to tools, technologies, and processes | You should not use a shared key to encrypt the API key on the VM. If the key is compromised so is the VM. You should not use a private key to encrypt the API key on the VM, this allows the corresponding public key to decrypt it. |  
| [Azure built-in roles](https://docs.microsoft.com/en-us/azure/role-based-access-control/built-in-roles) | Map security requirements to tools, technologies, and processes | Cognitive Services Contributer Role allows user to create and manage keys. CSU role allows user to list and read keys but not create. Security reader and Admin are for ASC not CS. |  
| [Authenticate requests to Azure Cognitive Services](https://docs.microsoft.com/en-us/azure/cognitive-services/authentication?tabs=powershell) | Map security requirements to tools, technologies, and processes | CSU role allows a user to list and read API keys. When you create a CS account, two API keys are generated, only 1 is needed to make calls to the APIs. To further secure the keys you can add them as secrets in the Azure Key Vault and allow the developer to retrieve keys from vault, he should not store them in the application. |  
| [Compliance in Azure Bot Service](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-compliance?view=azure-bot-service-4.0) | Map security requirements to tools, technologies, and processes | Step |  
| [Microsoft’s GDPR Commitments to Customers of our Generally Available Enterprise Software Products](https://docs.microsoft.com/en-us/legal/gdpr) | Map security requirements to tools, technologies, and processes | Step |  
| [Overview of the Face API](https://docs.microsoft.com/en-us/learn/modules/identify-faces-with-computer-vision/2-overview-of-the-face-api) | Recommend Azure Cognitive Services APIs to meet business requirements | Step |   
| [Introduction to the core Azure Storage services](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction) | Select the software, services, and storage required to support a solution | Step |  
| [What is Apache Hadoop in Azure HDInsight?](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction) | Select the software, services, and storage required to support a solution | Step |   

## Design AI Solutions (40-45%)
[My Notes on Design](https://github.com/msandfor/AI-100/blob/main/design.md)

| Resource | Topic | Step |   
|------|--------|------------------|
| [Connect a bot to channels](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [What is Azure Virtual Network?](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview) | Design solutions that implement the Microsoft Bot Framework | Step |  
| [What are Azure Cognitive Services?](https://docs.microsoft.com/en-us/azure/cognitive-services/what-are-cognitive-services) | Design solutions that implement the Microsoft Bot Framework | Step |  
| [Connect a bot to Web Chat](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-webchat?view=azure-bot-service-4.0) | Design solutions that implement the Microsoft Bot Framework | Step |  
| [Connect a bot to Direct Line](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-directline?view=azure-bot-service-4.0) | Design solutions that implement the Microsoft Bot Framework | Step |  
| [Virtual Machine series](https://azure.microsoft.com/en-in/pricing/details/virtual-machines/series/) | Design the compute infrastructure to support a solution | A = Entry Level, D = Databases, F = Gaming, N = GPU eNabled for deep LearNing |  
| [Use GPUs for compute-intensive workloads on Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/gpu-cluster) | Design the compute infrastructure to support a solution | Step | 
| [Deploy a deep learning model for inference with GPU](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-inferencing-gpus) | Design the compute infrastructure to support a solution | Step |   
| [Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetesh) | Design the compute infrastructure to support a solution | Step |   
| [Deploy models with Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-and-where?tabs=azcli) | Design the compute infrastructure to support a solution | Step |   
| [Connecting IoT Devices to Azure: IoT Hub and Event Hubs](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-compare-event-hubs) | Design solutions that include one or more pipelines | Step |   
| [Introduction to the core Azure Storage services](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction) | Design the compute infrastructure to support a solution | Azure Table Storage allows you to store structured data as key-attribute pairs. Data Lake does not store structured data it stores big data workloads. Azure queue storage stores messages. Azure Blob storage is for files not structured data |   
| [What is Azure Data Lake Storage Gen1?](https://docs.microsoft.com/en-us/azure/data-lake-store/data-lake-store-overview) | Design solutions that include one or more pipelines | This is an Apache Hadoop file system that allows data in it's native format. It supports data of any type and size. |   
| [What is Power BI?](https://docs.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview) | Design solutions that include one or more pipelines | Step |   
| [What is Azure IoT Hub?](https://docs.microsoft.com/en-us/azure/iot-hub/about-iot-hub) | Design solutions that include one or more pipelines | Step |   
| [Log Analytics tutorial](https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/log-analytics-tutorial) | Design solutions that include one or more pipelines | Step |   
| [What is Azure Databricks?](https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks) | Design solutions that include one or more pipelines | Step |   
| [Outputs from Azure Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-define-outputs) | Design solutions that include one or more pipelines | Step |   
| [What is Azure Data Factory?](https://docs.microsoft.com/en-us/azure/data-factory/introduction) | Design solutions that include one or more pipelines | Step |   
| [What is the Text Analytics API?](https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/overview) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [What is Personalizer?](https://docs.microsoft.com/en-us/azure/cognitive-services/personalizer/what-is-personalizer) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [What is Language Understanding (LUIS)?](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/what-is-luis) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [Integration runtime in Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/concepts-integration-runtime) | Design solutions that include one or more pipelines | Step |   
| [Run background tasks with WebJobs in Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/webjobs-create) | Design solutions that include one or more pipelines | Step |   
| [What is Azure Logic Apps?](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview) | Design solutions that include one or more pipelines | Step |   
| [What is Computer Vision?](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/overview) | Design solutions that uses Cognitive Services | Step |   
| [What is Azure Content Moderator?](https://docs.microsoft.com/en-us/azure/cognitive-services/content-moderator/overview) | Design solutions that uses Cognitive Services | Step |   
| [Quickstart: Build a classifier with the Custom Vision website](https://docs.microsoft.com/en-us/azure/cognitive-services/Custom-Vision-Service/getting-started-build-a-classifier) | Design solutions that uses Cognitive Services | Step |   
| [Understand inputs for Azure Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-add-inputs) | Design the compute infrastructure to support a solution | Step |   
| [Azure Stream Analytics solution patterns](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-solution-patterns) | Design the compute infrastructure to support a solution | Step |   
| [Welcome to Azure Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-introduction) | Design the compute infrastructure to support a solution | Step |   
| [Quickstart: Create a new app in the LUIS portal](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/get-started-portal-build-app) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [Regular expression entity](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/reference-entity-regular-expression?tabs=V2) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [Composite entity](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/reference-entity-composite?tabs=V2) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [List entity](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/reference-entity-list?tabs=V2) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [Simple Entity](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/reference-entity-simple?tabs=V2) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [Extract data with entities](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/luis-concept-entity-types) | Design solutions that implement the Microsoft Bot Framework | Step |   
| [Add entities to extract data](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-how-to-add-entities) | Design solutions that implement the Microsoft Bot Framework | Tutorial - Get exact text matched data from an utterance |   
| [Deploy ML models to field-programmable gate arrays (FPGAs) with Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-fpga-web-service) | Design the compute infrastructure to support a solution | Step |   
| [Authenticate requests to Azure Cognitive Services](https://docs.microsoft.com/en-us/azure/cognitive-services/authentication?tabs=powershell) | Design for data governance, compliance, integrity, and security | Step |   
| [An overview of Azure SQL Database and SQL Managed Instance security capabilities](https://docs.microsoft.com/en-us/azure/azure-sql/database/security-overview) | Design for data governance, compliance, integrity, and security | Step |   
| [Always Encrypted](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine?view=sql-server-ver15) | Design for data governance, compliance, integrity, and security | Step |   
| [Row-Level Security](https://docs.microsoft.com/en-us/sql/relational-databases/security/row-level-security?view=sql-server-ver15) | Design for data governance, compliance, integrity, and security | Step |   
| [Extensible Key Management Using Azure Key Vault (SQL Server)](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/extensible-key-management-using-azure-key-vault-sql-server?view=sql-server-ver15) | Design for data governance, compliance, integrity, and security | Step |   
| [Azure SQL Transparent Data Encryption with customer-managed key](https://docs.microsoft.com/en-us/azure/azure-sql/database/transparent-data-encryption-byok-overview) | Design for data governance, compliance, integrity, and security | Step |   
| [Transparent Data Encryption (TDE)](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/transparent-data-encryption?view=sql-server-ver15) | Design for data governance, compliance, integrity, and security | Step |   

Overview of the Face API - Can detect features - eyes closed, looking at road etc

## Implement and monitor AI solutions (25-30%)
[My Notes on Implement and Monitor](https://github.com/msandfor/AI-100/blob/main/monitor.md)

| Resource | Topic | Step |   
|------|--------|------------------|
| [Evaluate Model](https://docs.microsoft.com/en-us/azure/machine-learning/studio-module-reference/evaluate-model) | Implement an AI workflow | Calculates the difference between predicted and actual RAE |   
| [Score Model](https://docs.microsoft.com/en-us/azure/machine-learning/studio-module-reference/score-model) | Implement an AI workflow | Makes predictions from a classification or regression model |   
| [Create R Model](https://docs.microsoft.com/en-us/azure/machine-learning/studio-module-reference/create-r-model) | Implement an AI workflow | Requires you to write R scrips |   
| [Train Model](https://docs.microsoft.com/en-us/azure/machine-learning/studio-module-reference/train-model) | Monitor and evaluate the AI environment | Train a classification or regression model |   
| [Monitor and collect data from ML web service endpoints](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-app-insights) | Monitor and evaluate the AI environment | Step |   
| [Enable logging in ML training runs](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-track-experiments) | Monitor and evaluate the AI environment | Step |   
| [Collect data from models in production](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-data-collection) | Monitor and evaluate the AI environment | Step |   
| [Azure Monitor for containers overview](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/container-insights-overview) | Monitor and evaluate the AI environment | Step |   
| [How to use Azure.Search.Documents in a C# .NET Application](https://docs.microsoft.com/en-us/azure/search/search-howto-dotnet-sdk) | Integrate AI services and solution components | Step |   
| [What is QnA Maker?](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/overview/overview) | Integrate AI services and solution components | Step |   
| [QnA Maker documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/QnAMaker/) | Integrate AI services and solution components | Step |   
| [Bot channels registration](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-quickstart-registration?view=azure-bot-service-4.0&viewFallbackFrom=azure-bot-service-3.0) | Integrate AI services and solution components  | Step |   
| [Bot analytics](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-analytics?view=azure-bot-service-4.0) | Monitor and evaluate the AI environment  | Step |   
| [Welcome to Azure Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-introduction) | Monitor and evaluate the AI environment  | Step |   
| [Enable capturing of events streaming through Azure Event Hubs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-capture-enable-through-portal) | Monitor and evaluate the AI environment | Step |   
| [Application Insights keys](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-resources-app-insights-keys?view=azure-bot-service-4.0) | Monitor and evaluate the AI environment | Step |

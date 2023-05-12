# Repositório de amostras de serviços de dados do Azure Health
O repositório de exemplos do Azure Health Data Services é um conjunto de aplicativos de exemplo e código de exemplo fornecido para ajudá-lo a começar a usar o Azure Health Data Services, aprender como usar nossos produtos e acelerar suas implementações.

Este projeto hospeda **amostras** de software livre para Azure Health Data Services. Para saber mais sobre o Azure Health Data Services, consulte a documentação do serviço gerenciado [aqui.](https://learn.microsoft.com/en-us/azure/healthcare-apis/healthcare-apis-overview)

## Exemplos

Este projeto fornece exemplos descrevendo implementações de exemplo de vários casos de uso em estágios de fluxos de trabalho de dados de saúde. A pasta "amostras" contém todos os aplicativos de amostra organizados por caso de uso. As amostras estão listadas aqui:

<!---
### Ingestão de dados nos serviços de dados de saúde

|Exemplo|Descrição|
| --- | --- |
|[Exemplo de pipeline de ingestão de dados HL7v2]() | Aplicativo de amostra que mostra como ingerir dados HL7v2 no servidor FHIR, incluindo conversão e validação. |

### Análise e aprendizado de máquina
|Exemplo|Descrição|
| --- | --- |
| FHIR Delta Lake com Databricks | Exemplo de ponta a ponta mostrando dados do serviço FHIR nos níveis Databricks Delta Lake Bronze, Silver e Gold |
| Painel do PowerBI usando pipelines do Analytics | Amostra mostrando como consultar dados FHIR no formato de arquivo Parquet (no Azure Data LAke) e tabelas SQL sem servidor para calcular medidas de qualidade digital e visualizar dados de medida estratificados no PowerBI.|

### Outras integrações
|Exemplo|Descrição|
| --- | --- |
| Formato FHIR para HL7v2 para ingestão de volta em um EHR (em breve)| Sample to convert FHIR data to HL7v2 format suitable for ingestion into an EHR. |

--->

### ingestão de dados

|Exemplo|Descrição|
| --- | --- |
| [Migrate data from one Azure API for FHIR server to another API for FHIR server](samples/fhir-to-fhir/api-for-fhir-to-api-for-fhir) | Aplicativo de exemplo para copiar/migrar dados de uma API do Azure para servidor FHIR para outra API do Azure para servidor FHIR. |


### Exemplos de transações
|Exemplo|Descrição|
| --- | --- |
| [Sample Postman queries](samples/sample-postman-queries) | Learn how to interact with FHIR data using Postman with this starter Postman collection of common Postman queries used to query FHIR server, including FHIR searches, creating, reading, updating, and deleting requests for FHIR resources, and other operations.|

### Analytics and machine learning
|Sample|Description|
| --- | --- |
| [Visualize Digital Quality Measures in PowerBI leveraging FHIR parquet data in Data Lake](samples/analytics-visualization) | Sample demonstrates how to calculate example quality measures from FHIR data by querying flattened FHIR parquet file data in Synapse Analytics and visualizing the results in Power BI.|
| [Integrate Azure Health Data Services FHIR data with Delta Lake on Azure Databricks](samples/azuredatabricks-deltalake/) | Learn how to use Azure Databricks with Azure Health Data Services. Sample demonstrates how to automatically connect data from the FHIR Service into analytics platforms on Azure Databricks Delta Lake using the Analytics Connector. |

### Patient and population services (g)(10) (including SMART on FHIR) sample
|Sample|Description|
| --- | --- |
| [Patient and Population Services (g)(10) (including SMART on FHIR) sample](https://github.com/Azure-Samples/azure-health-data-services-samples/tree/main/samples/Patient%20and%20Population%20Services%20G10) | Sample utilizing [Azure Health Data Services](https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/smart-on-fhir) to demonstrate to health organizations with the steps to meet the [§170.315(g)(10) Standardized API for patient and population services criterion](https://www.healthit.gov/test-method/standardized-api-patient-and-population-services#ccg).|

### DICOM service 
|Sample|Description|
| --- | --- |
| [DICOM service demo environment](/samples/dicom-demo-env/) | This sample provisions a full end-to-end demo environment of a simplifed on-prem radiology network in an Azure resource group.  Instructions are provided for configuring and using the DICOM router and ZFP viewer included in the environment. |



NOTE: These code samples are simplified scenarios showing how you can use Azure Health Data Services. These samples should be used for testing purposes only with sample data. 

## Resources
- [Azure Health Data Services documentation](https://learn.microsoft.com/en-us/azure/healthcare-apis/healthcare-apis-overview)


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Disclaimers

The Azure Health Data Services Samples Repo is an open-source project. It is not a managed service, and it is not part of Microsoft Azure Health Data Services. The sample apps and sample code provided in this repo are used as examples only. You bear sole responsibility for compliance with local law and for any data you use when using these samples. Please review the information and licensing terms on this GitHub website before using the Azure Health Data Services Samples repo. 

The Azure Health Data Services Samples Github repo is intended only for use in transferring and formatting data. It is not intended for use as a medical device or to perform any analysis or any medical function and the performance of the software for such purposes has not been established. You bear sole responsibility for any use of this software, including incorporation into any product intended for a medical purpose. 

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.


FHIR® is the registered trademark of HL7 and is used with the permission of HL7. 

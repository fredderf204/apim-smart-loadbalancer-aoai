# Introduction

This repo is designed to implement a smart load balancer for OpenAI endpoints and Azure API. The load balancer is designed to distribute the requests to the endpoints based on the response time of the endpoints. The load balancer is designed to be used with Azure API Management.

Please find the original article [here](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/smart-load-balancing-for-openai-endpoints-and-azure-api/ba-p/3991616).

![Diagram](./images/diagram.png)

This terraform code deploys the following resources:

- Azure API Management
- 3 x Azure Open AI
- Application Insights

**1. Online Boutique**, https://github.com/GoogleCloudPlatform/microservices-demo

| Service | Build, Deploy | Observability |
| ------------------------- | ---------------- | ---------------- |
|                     | Azure Kubernetes (Done ✅) | |
|                     | AWS Kubernetes | |
|                     | GCP Kubernetes | |
| Serverless                    |  | |
| 1. emailservice (Python) | | |
| 2. productcatalogservice (Go) | | |
| 3. recommendationservice (Python) | | |
| 4. shippingservice (Go) | | |
| 5. checkoutservice (Go) | | |
| 6. paymentservice (Node.js) | | |
| 7. currencyservice (Node.js) | | |
| 8. cartservice (C#) | [<img src="https://storage.googleapis.com/cloudrun/button.svg" alt="Run on Google Cloud" height="30">][run_cartservice] | |
| 9. frontend (Go) | [<img src="https://storage.googleapis.com/cloudrun/button.svg" alt="Run on Google Cloud" height="30">][run_frontend] | |
| 10. adservice (Java) | | |

[run_frontend]: https://deploy.cloud.run/?git_repo=https://github.com/GoogleCloudPlatform/microservices-demo&dir=src/frontend
[run_cartservice]: https://deploy.cloud.run/?git_repo=https://github.com/GoogleCloudPlatform/microservices-demo&dir=src/cartservice


**Azure Kubernetes**
1. az login
2. az group create --name \<microservices-demo\> -l \<westus\>
3. az acr create --name \<artifacts\> --resource-group \<microservices-demo\> --sku basic
4. az acr login --name \<artifacts\>
5. az aks create --resource-group \<microservices-demo\> --name \<microservices-demo-aks\> --node-count 3 --attach-acr \<artifacts\> --enable-addons monitoring --generate-ssh-keys
6. az aks install-cli
7. az aks get-credentials --resource-group \<microservices-demo\> --name \<microservices-demo-aks\>
8. skaffold run --default-repo=\<artifacts\>.azurecr.io

**AWS Kubernetes**

</>

**GCP Kubernetes**

</>

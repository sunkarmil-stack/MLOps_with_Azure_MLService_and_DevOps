---
page_type: sample
languages:
- python
products:
- azure
- azure-machine-learning-service
- azure-devops
description: "Code which demonstrates how to set up and operationalize an MLOps flow leveraging Azure Machine Learning and Azure DevOps."
---

# MLOps with Azure ML

CI: [![Build Status](https://aidemos.visualstudio.com/MLOps/_apis/build/status/Model-Train-Register-CI?branchName=master)](https://aidemos.visualstudio.com/MLOps/_build/latest?definitionId=160&branchName=master)

CD: [![Build Status](https://aidemos.visualstudio.com/MLOps/_apis/build/status/microsoft.MLOpsPython-CD?branchName=master)](https://aidemos.visualstudio.com/MLOps/_build/latest?definitionId=161&branchName=master)

MLOps will help you to understand how to build a Continuous Integration and Continuous Delivery pipeline for an ML/AI project. We will be using the Azure DevOps Project for build and release/deployment pipelines along with Azure ML services for model retraining pipeline, model management and operationalization.

![ML lifecycle](/docs/images/ml-lifecycle.png)

This template contains code and pipeline definitions for a machine learning project that demonstrates how to automate an end to end ML/AI workflow.

## Architecture and Features

Architecture Reference: [Machine learning operationalization (MLOps) for Python models using Azure Machine Learning](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/mlops-python)

This reference architecture shows how to implement continuous integration (CI), continuous delivery (CD), and retraining pipeline for an AI application using Azure DevOps and [Azure Machine Learning](/azure/machine-learning/service/overview-what-is-azure-ml). The solution is built on the scikit-learn diabetes dataset but can be easily adapted for any AI scenario and other popular build systems such as Jenkins and Travis.

The build pipelines include DevOps tasks for data sanity tests, unit tests, model training on different compute targets, model version management, model evaluation/model selection, model deployment as realtime web service, staged deployment to QA/prod and integration testing.

## Prerequisite

- Active Azure subscription
- At least contributor access to Azure subscription

## Getting Started

To deploy this solution in your subscription, follow the manual instructions in the [getting started](docs/getting_started.md) doc. Then optionally follow the guide for [integrating your own code](docs/custom_model.md) with this repository template.

### Repo Details

You can find the details of the code and scripts in the repository [here](/docs/code_description.md)

### References

- [Azure Machine Learning (Azure ML) Service Workspace](https://docs.microsoft.com/en-us/azure/machine-learning/service/overview-what-is-azure-ml)
- [Azure ML CLI](https://docs.microsoft.com/en-us/azure/machine-learning/service/reference-azure-machine-learning-cli)
- [Azure ML Samples](https://docs.microsoft.com/en-us/azure/machine-learning/service/samples-notebooks)
- [Azure ML Python SDK Quickstart](https://docs.microsoft.com/en-us/azure/machine-learning/service/quickstart-create-workspace-with-python)
- [Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/?view=vsts)

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit <https://cla.microsoft.com.>

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


免责声明：
1.本资源仅供学习和交流使用，不保证其准确性、完整性、及时性或适用性。
2.本资源仅包含一般信息，不构成专业建议。在使用本资源时，请务必自行研究并谨慎决策。
3.我已尽力确保本资源的正确性和合法性，但不对其准确性、完整性和及时性做出保证。
4.本资源不应用于商业用途。
5.在使用本资源的过程中，用户应自行承担所有风险和责任，并遵守相关法律法规。
6.对于因使用本资源而产生的任何损失或损害，我概不负责。
请确保在使用本资源时仔细阅读并遵守以上免责声明。如果您有任何疑问或需要进一步帮助，请联系我。

资源最后修改时间：2025-09-05 17:18:48
1954016435956400
4486250f-f43b-4e42-999d-1def3c206f65
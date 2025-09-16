# **AI Software Template GitOps**

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template execution. The associated source component is available for reference in the **Overview** tab as described in the following image.

![Overview Tab](./images/overview-dependency.png)

# **Deployed Resources**

A deployment with the following characteristics was made based on input from the AI Software Template.

## **Model & Model Server**

A [llama.cpp]( https://github.com/redhat-ai-dev/developer-images/tree/main/model-servers/llamacpp_python/0.3.8) model server was deployed to serve the [ibm-granite/granite-3.1-8b-instruct](https://huggingface.co/ibm-granite/granite-3.1-8b-instruct) model.

!!! info

    This model server is available on port 8001!

# **Application**

The AI Software Template that was executed comes with a sample application. This application will be built from https://github.com/redhat-appstudio-mjf/chatbot-test-sep16-1, stored in [quay.io/maysunfaisal/chatbot-test-sep16-1](https://quay.io/maysunfaisal/chatbot-test-sep16-1) and deployed through ArgoCD. 

This sample application is accessible through port 8501.
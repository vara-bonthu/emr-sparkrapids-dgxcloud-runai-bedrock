# 🚀 emr-sparkrapids-dgxcloud-runai-bedrock

🚧 Status: Work in Progress – This project is currently under development and not yet ready for user testing.

## Overview
This project demonstrates a comprehensive workflow that integrates GPU-accelerated data processing, large language model (LLM) fine-tuning using NVIDIA DGX Cloud with Run:ai, and deployment of a custom LLM model for inference using Amazon Bedrock. The workflow encompasses the following steps:

- 1️⃣ 📊 **Data Processing with Spark RAPIDS on Amazon EMR**: Process raw data from Amazon S3 using GPU acceleration, then store structured data back to S3 in Parquet format.
- 2️⃣ 🤖 **LLM Fine-Tuning on NVIDIA DGX Cloud with Run:ai**: Use processed data to fine-tune an LLM, then save the model weights to S3.
- 3️⃣ 🚀 **Model Deployment on Amazon Bedrock**: Load fine-tuned model weights from S3 and deploy for inference on Amazon Bedrock.
- 4️⃣ 🧪 **Inference Testing**: Send test prompts to the Bedrock-hosted model and verify results.

### 🔧 Prerequisites
1. **AWS Account:** Access to Amazon EMR, S3, and Bedrock services.
2. **NVIDIA DGX Cloud Subscription:** Access to DGX Cloud resources.
3. **Run:ai Platform:** Set up and configured on DGX Cloud.
5. **Spark RAPIDS Plugin:** Installed on your EMR on EKS cluster.

### ⚡ Workflow Details
1. Data Processing with Spark RAPIDS on Amazon EMR
2. LLM Fine-Tuning on NVIDIA DGX Cloud with Run:ai
3. Custom Model Deployment on Amazon Bedrock

## 🎯 Conclusion
This project seamlessly integrates GPU-accelerated data processing, LLM fine-tuning, and scalable model deployment. By leveraging Amazon EMR, NVIDIA DGX Cloud with Run:ai, and Amazon Bedrock, this workflow simplifies custom AI model development for real-world applications.

📚 For more details, refer to:
🔗 [Spark RAPIDS Documentation](https://docs.nvidia.com/spark-rapids/index.html)
🔗 [NVIDIA DGX Cloud](https://www.nvidia.com/en-us/data-center/dgx-cloud/?ncid=pa-srch-goog-108186-DGX-Brand-prsp&_bt=731829895137&_bk=nvidia%20dgx&_bm=b&_bn=g&_bg=174488073597&gad_source=1&gclid=Cj0KCQiA8fW9BhC8ARIsACwHqYo4BjMMTlTq_hDkX_10Novb-Ou8Ho4euOfTmcZdqjhfyabIwhNqWEMaAqJrEALw_wcB)
🔗 [Run:ai Documentation](https://docs.run.ai/v2.20/home/overview/)
🔗 [Amazon Bedrock](https://aws.amazon.com/bedrock/)

🚀 Stay tuned for updates as this project evolves! 🚧

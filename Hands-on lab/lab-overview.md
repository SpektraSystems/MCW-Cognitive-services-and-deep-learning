# Cognitive services and deep learning hands-on lab step-by-step

## Abstract and learning objectives

In this hands-on lab, you will implement a solution which combines both pre-built artificial intelligence (AI) in the form of various Cognitive Services, with custom AI in the form of services built and deployed with Azure Machine Learning service. In the lab you will be working with unstructured text and image data and learning how to build analytics pipelines for various problems such as text summarization, text classification, image detection, OCR, and sentiment analysis. You will learn how to build and train a deep neural net for text classification.  You will also learn how to deploy multiple kinds of predictive services using Azure Machine Learning and learn to integrate with the Computer Vision API and the Text Analytics API from Cognitive Services.

At the end of this hands-on lab, you will be better able to present solutions leveraging Azure Machine Learning service, Azure Machine Learning Compute instance and Cognitive Services.

## Overview

In this workshop, you will help Contoso Ltd. build a proof of concept that shows how they can build a solution that amplifies the claims processing capabilities of their agents.

## Solution architecture

The high-level architecture of the solution is illustrated in the diagram. The lab is performed within the context of a notebook running within Machine Learning compute instance. Various notebooks are built to test the integration with the Cognitive Services listed, to train custom ML services, and to integrate the results in a simple user interface that shows the result of processing the claim with all of the AI services involved.

![The High-level architectural solution begins with a Claim, which us submitted for processing using a notebook in Azure Databricks. This notebook coordinates the calls to Computer Vision, Text Analytics, and Containerized Services, which includes a Classification Service and a Summary Service that both processes claim text.](media/image2.jpg 'High-level architectural solution')

Now, click on the **Next** from lower right corner of your lab guide page to Begin the lab.

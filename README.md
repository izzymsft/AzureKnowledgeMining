# Knowledge Mining on Microsoft Azure
This is a curated set of resources that provide links to knowledge-mining related content on Azure.

## What is Knowledge Mining?
Knowledge mining can be described as the process of identifying, extracting and processing potentially useful, valid pieces of information or patterns in massive datasets. Most of the time knowledge mining leverages machine learning techniques or artificial intelligence products to aid in the process of extracting useful data out of raw datasets.

## Resources and Products
In this document, we are going to discuss the various Azure resources and products that are available at your disposal for knowledge mining.

### Azure Cognitive Search

AI enrichment is a capability of[ Azure Cognitive Search](https://docs.microsoft.com/en-us/azure/search/cognitive-search-concept-intro) indexing used to extract text from images, blobs, and other unstructured data sources - enriching the content to make it more searchable in an index or knowledge store. Extraction and enrichment are implemented through cognitive skills attached to an indexing pipeline which leverage the Computer Vision and Text Analysis APIs to provide the following capabilities:

- **Natural language processing** skills include entity recognition, language detection, key phrase extraction, text manipulation, and sentiment detection. With these skills, unstructured text can assume new forms, mapped as searchable and filterable fields in an index.

- **Image processing** skills include Optical Character Recognition (OCR) and identification of visual features, such as facial detection, image interpretation, image recognition (famous people and landmarks) or attributes like colors or image orientation. You can create text-representations of image content, searchable using all the query capabilities of Azure Cognitive Search.

### Knowledge Stores in Azure Cognitive Search
Another feature of Azure Cognitive Search is [Knowledge Store](https://docs.microsoft.com/en-us/azure/search/knowledge-store-concept-intro). It persists output from an AI enrichment pipeline for later analysis or other downstream processing. An enriched document is a pipeline's output, created from content that has been extracted, structured, and analyzed using AI processes

### Form Recognizer
Form Recognizer applies advanced machine learning to accurately extract text, key/value pairs, and tables from documents. It uses pre-built and unsupervised learning components to understand the layout and relationships between fields and entries in your documents, to pull information in an organized manner. It can accurately extract text, key/value pairs, and tables from documents, forms, and receipts, without manual labeling by document type or intensive coding or maintenance.

This is the [quick link](https://docs.microsoft.com/en-us/azure/cognitive-services/form-recognizer/?branch=release-build-cogserv-forms-recognizer) on how to get started

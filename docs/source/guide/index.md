---
title: Get started with Label Studio
short: Get started
type: guide
order: 100
meta_title: Get Started with Label Studio
meta_description: Get started with Label Studio by creating projects to label and annotate data for machine learning and data science models.
---

## What is Label Studio?

Label Studio is an open source data labeling tool for labeling and exploring multiple types of data. You can perform different types of labeling with many data formats. 

You can also integrate Label Studio with machine learning models to supply predictions for labels (pre-labels), or perform continuous active learning. See [Set up machine learning with your labeling process](ml.html). 

Label Studio is also available in Enterprise and Cloud editions with additional features. See [Label Studio features](label_studio_compare.html) for more.

## Labeling workflow with Label Studio

Start and finish a labeling project with Label Studio by following these steps:

1. [Install Label Studio](install.html).
2. [Start Label Studio](start.html).
2. [Create accounts for Label Studio](signup.html). Create an account to manage and set up labeling projects.
3. <i class='ent'></i> [Restrict access to the project](manage_users.html). Set up role-based access control. Only available in Label Studio Enterprise Edition.
4. [Set up the labeling project](setup_project.html). Define the type of labeling to perform on the dataset and configure project settings.
5. [Set up the labeling interface](setup.html). Add the labels that you want annotators to apply and customize the labeling interface. 
6. [Import data as labeling tasks](tasks.html).
7. [Label and annotate the data](labeling.html). 
8. <i class='ent'></i> [Review the annotated tasks](quality.html). Only available in Label Studio Enterprise Edition.
9. [Export the labeled data or the annotations](export.html).


## Quick start

1. Install Label Studio:
```bash
pip install label-studio
```
2. Start Label Studio
```bash
label-studio start
```
3. Open the Label Studio UI at http://localhost:8080. 
4. Sign up with an email address and password that you create.
5. Click **Create** to create a project and start labeling data.
6. Name the project, and if you want, type a description and select a color.
7. Click **Data Import** and upload the data files that you want to use. If you want to use data from a local directory, cloud storage bucket, or database, skip this step for now.
8. Click **Labeling Setup** and choose a template and customize the label names for your use case. 
9. Click **Save** to save your project. 

You're ready to start [labeling and annotating your data](labeling.html)!

## Label Studio terminology

When you upload data to Label Studio, each item in the dataset becomes a labeling task. The following table defines the terms that appear throughout Label Studio.

**Annotation**
Annotation is the process of labeling data in various formats such as video, images, or text, so that machines can understand it. The output of a labeling task which was previously called **Completions**. 

**Artificial Intelligence (AI)**
AI is the intelligence demonstrated by machines, as opposed to the natural intelligence displayed by animals including humans.  It refers to the simulation of human intelligence in machines that are programmed to think like humans and mimic their actions.

**Audio classification**
Audio classification or sound classification can be referred to as the process of analyzing audio recordings. This amazing technique has multiple applications in the field of AI and data science such as chatbots, automated voice translators, virtual assistants, music genre identification, and text to speech applications.

**Audio labeling**
Audio labeling or speech labeling is a standard annotation technique that concerns separating sounds and labeling with specific metadata.

**Audio tagging**
Audio tagging is a task to predict the tags of audio clips. This includes music tagging, acoustic scene classification, audio event classification, and so on.

**Audio transcription**
Audio transcription transforms any video or audio file into an entire experience for your audience. It is available in a written format of any verbal communication.

**Automatic Speech Recognition (ASR)**
ASR refers to the problem of getting a program to automatically transcribe spoken language (speech-to-text).

**Bounding box object detection**
A bounding box describes the spatial location of an object. It is rectangular, which is determined by the "x" and "y" coordinates of the upper-left corner of the rectangle and such coordinates of the lower-right corner.

**Consolidated Receipt Dataset for Post-OCR Parsing (CORD)**
COResets and Data Subset slection is an efficient and scalable library for making machine learning time, energy, cost, and compute efficient built on top of pytorch. It uses a subset of training data for model training and incorporates various state-of-the-art data selection strategies to select the proper representative data subset from massive datasets. 

**Data annotation**
Data annotation is the categorization and labeling of data for AI applications. It helps machines to learn the certain patterns and correlate the results, and the use the data sets to recognize the similar patterns in future to predict the results.

**Data labeling**
Data labeling is the process of identifying raw data (images, text files, videos, and so on) and adding one or more meaningful and informative labels to provide context so that a machine learning model can learn from it.

**Data parsing**
Data parsing is a method of converting data from one format to another format. For example, converting from HTML to JSON.

**Dialog processing**
Dialog processing or interactive document creation is the complementary method to batch processing and background processing. It is defined by the active user who creates all or part of the document in the system editor.

**Docker**
Docker is a software platform that allows you to build, test, and deploy applications quickly.

**Document classification**
Document classification is the act of labeling or tagging documents using categories, depending on their content.

**Dataset**
A dataset (or data set) is a collection of data comprised of individual items, or labeling tasks that you import into Label Studio.

**Emotion recognition**
Emotion recognition is the process of identifying human emotions.

**Entity recognition**
Entity recognition is a new technology that can enable investigators and document review managers to get to the pertinent data faster.

**Human labeling**
Human labeling enables you to label images in your training dataset at scale.

**Image classification**
Image classification is the process of categorizing and labeling groups of pixels or vectors within an image based on specific rules.

**Image labeling**
Image labeling is the process of identifying and marking various details in an image. It is useful when automating the process of generating metadata or making recommendations to users based on details in their images.

**Image segmentation**
Image segmentation is the process of assigning a label to every pixel in an image such that pixels with the same label share certain characteristics.

**Image tagging**
Image tagging is the process of labeling images based on figures within a certain picture. It enables the classification of visuals through the use of tags and labels.

**Inventory tracking**
Inventory tracking system allows you to label exact products by given brand names illustrated by relevant sample photo.

**Label**
A label is a key-value pair, stored as a string. You can specify multiple labels for an object, but each key must be unique within an object.

**Label in machine learning**
In machine learning, a label is added by human annotators to explain a piece of data to the computer. This process is known as data annotation and is necessary to show the human understanding of the real world to the machines. Data labeling tools and providers of annotation services are an integral part of a modern AI project.

**Label studio**
Label Studio is an open source data labeling tool for labeling and exploring multiple types of data.

**Label studio enterprise**
Label Studio Enterprise is a data labeling platform that enables you to build ground truth datasets, with the focus on quality, security, and team collaboration. The only end-to-end solution for managing internal data labeling projects.

**Lightweight Directory Access Protocol (LDAP)**
LDAP is a mature, flexible, and well-supported standards-based mechanism for interacting with directory servers. It is often used for authentication and storing information about users, groups, and applications, but an LDAP directory server is a fairly general-purpose data store and can be used in a wide variety of applications.

**Machine learning**
Machine learning is a branch of AI and computer science which focuses on the use of data and algorithms to imitate the way that humans learn, gradually improving its accuracy.

**Machine Learning Model Operationalization Management (MLOps)**
MLOps is a set of practices that aims to deploy and maintain machine learning models in production reliably and efficiently.

**Model**
A model in machine learning is the output of a machine learning algorithm run on data. A model represents what was learned by a machine learning algorithm.

**Modeling**
The process of modeling means training a machine learning algorithm to predict the labels from the features, tuning it for the business need, and validating it on holdout data.

**Named entity recognition (NER)**
NER is the process of identifying and classifying named entities presented in a text document.

**Natural language processing (NLP) labeling**
Data labeling is the process of adding labels to raw data to give context or meaning to the data. The labeled data is then used to train the NLP models to make predictions or understand or generate speech.

**Object detection**
Object detection is the task of detecting instances of objects of a certain class within an image.

**Object detection dataset**
Object detection relates to computer vision and image processing that deals with detecting instances of semantic objects of a certain class (such as humans, buildings, or cars) in digital images and videos.

**Optical Character Recognition (OCR)**
Optical character recognition (OCR) is a technology that analyzes the text of a page and turns the letters into code that may be used to process information.

**Outliner**
Outliner is the place where you can see all the details about annotation, regions, and labeling history. The Outliner and Details panel are both collapsible and detachable, so you can arrange them the way you want.

**Persistent storage**
Persistent storage is any data storage device that retains data after power to that device is shut off. It is also sometimes referred to as nonvolatile storage.

**PostgreSQL**
PostgreSQL, commonly pronounced “Post-GRE” is an open source database that has a strong reputation for its reliability, flexibility, and support of open technical standards.

**Predictions** 
Prediction in machine learning refers to an information output that comes from running an algorithm on data to forecast the likelihood of a certain outcome.

**Pre-annotations** 
Predicted annotations in Label Studio format, either in a file or from a machine learning backend. See [import pre-annotations](predictions.html).

**Region**
The portion of the task identified for labeling. For images, an example region is a bounding box. For text, an example region is a span of text. Often has a label assigned to it. 

**Relation** 
A defined relationship between two labeled regions. 

**Result** 
A label applied to a specific region as stored in an annotation or prediction. See [Label Studio JSON format of annotated tasks](export.html#Label-Studio-JSON-format-of-annotated-tasks). |

**Role-based Access Control (RBAC)**
Role-based access control (RBAC), also known as role-based security, is an access control method that assigns permissions to end-users based on their role within your organization.

**Sentiment analysis**
Sentiment analysis (also known as opinion mining or emotion AI) is the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information.

**Security Assertion Markup Language (SAML)**
SAML is an open standard for exchanging authentication and authorization data between parties, in particular, between an identity provider and a service provider.

**Semantic labeling**
Semantic labeling, or semantic segmentation, involves assigning class labels to pixels. It models the predicate-argument structure of a sentence and is often described as answering "Who did what to whom"? For example, the task involves assigning at each pixel a label that is most consistent with local features at that pixel and with labels estimated at pixels in its context, based on consistency models learned from training data.

**Server-side Request Forgery (SSRF)**
SSRF is a web security vulnerability that allows an attacker to induce the server-side application to make requests to an unintended location.

**Single Sign-on (SSO)**
SSO is a technology which combines several application login screens into one.

**SOCKS proxy**
SOCKS is an internet protocol that exchanges network packets between a client and server through a proxy server. 

**SQLite or PostgreSQL databases**
SQLite is a self-contained, file-based, and fully open-source RDBMS known for its portability, reliability, and strong performance even in low-memory environments.

**Synthetic data**
Synthetic data is annotated information that computer simulations or algorithms generate as an alternative to real-world data.

**Tags**
Configuration options to customize the labeling interface. See [more about tags](/tags). |

**Task**
A distinct item from a dataset that is ready to be labeled, pre-annotated, or has already been annotated. For example: a sentence of text, an image, or a video clip. 

**Taxonomy**
Taxonomy is the practice and science of categorization or classification.

**Templates**
Example of labeling configurations that you can use to specify the type of labeling to perform with your dataset. See [all available templates](/templates) |

**Text classification**
Text classification also known as text tagging or text categorization is the process of categorizing text into organized groups. By using NLP, text classifiers can automatically analyze text and then assign a set of pre-defined tags or categories based on its content.

**Time series classification**
Time series classification uses supervised machine learning to analyze multiple labeled classes of time series data and then predict or classify the class that a new data set belongs to. This is important in many environments where the analysis of sensor data or financial data might need to be analyzed to support a business decision.

**Time series data labeling**
Time series data, which is also said to as time-stamped data, is a sequence of data points tabulated in an order of time. Select and label patterns in time series visualizations and other interactive diagrams with a single click.

**Time series segmentation**
Time series segmentation is a method of time-series analysis in which an input time-series is divided into a sequence of discrete segments in order to reveal the underlying properties of its source.

**Time series**
Time series data, also referred to as time-stamped data, is a sequence of data points indexed in time order.

**Transport Layer Security (TLS)/Secure Sockets Layer (SSL)**
TLS and SSL are cryptographic protocols that authenticate server-to-device data transfers.

**Video**
Video is an electronic medium for the recording, copying, playback, broadcasting, and display of moving visual media.

**Video data labeling**
Data labeling is the process of identifying raw data (images, text files, videos, and so on.) and adding one or more meaningful and informative labels to provide context so that a machine learning model can learn from it. For example, labels might indicate whether a photo contains a bird or car, which words were uttered in an audio recording, or if an x-ray contains a tumor. Data labeling is required for a variety of use cases including computer vision, natural language processing, and speech recognition.

**Video tagging**
Video tagging is used to index and catalog videos based on content. It also Identifies a location in a video for future reference.

**Visual genome**
Visual genome is a dataset, a knowledge base, an ongoing effort to connect structured image concepts to language.

**Webhook**
A webhook in web development is a method of augmenting or altering the behavior of a web page or web application with custom callbacks.


## Components and architecture
You can use any of the Label Studio components in your own tools, or customize them to suit your needs. Before customizing Label Studio extensively, you might want to review Label Studio Enterprise Edition to see if it already contains the relevant functionality you want to build. See [Label Studio Features](label_studio_compare.html) for more.

The component parts of Label Studio are available as modular extensible packages that you can integrate into your existing machine learning processes and tools. 

| Module | Technology | Description |
| --- | --- | --- | 
| [Label Studio Backend](https://github.com/heartexlabs/label-studio/) | Python and [Django](https://www.djangoproject.com/) | Use to perform data labeling. | 
| [Label Studio Frontend](https://github.com/heartexlabs/label-studio-frontend) | JavaScript web app using [React](https://reactjs.org/) and [MST](https://github.com/mobxjs/mobx-state-tree) | Perform data labeling in a user interface. |
| [Data Manager](https://github.com/heartexlabs/dm2) | JavaScript web app using [React](https://reactjs.org/) | Manage data and tasks for labeling. |
| [Machine Learning Backends](https://github.com/heartexlabs/label-studio-ml-backend) | Python | Predict data labels at various parts of the labeling process. |

<br>
<div style="margin:auto; text-align:center;"><img src="/images/ls-modules-scheme.png" style="opacity: 0.8"/></div>
<!--update to include data manager--> 

## Information collected by Label Studio

Label Studio collects anonymous usage statistics about the number of page visits and data types being used in labeling configurations that you set up. No sensitive information is included in the information we collect. The information we collect helps us improve the experience of labeling data in Label Studio and helps us plan future data types and labeling configurations to support. 



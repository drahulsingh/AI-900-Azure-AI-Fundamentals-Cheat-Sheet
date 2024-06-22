# AI-900 Azure AI Fundamentals Cheat Sheet

## Exam Topics Overview

### 1. Describe Artificial Intelligence Workloads and Considerations (15–20%)

#### Identify Features of Common AI Workloads
AI workloads refer to tasks and processes that involve the application of artificial intelligence techniques. Common AI workloads include:
- **Machine Learning**: Training models on data to make predictions or classify data.  
  - *Azure Tool*: [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)
- **Computer Vision**: Analyzing visual data to identify objects, faces, or scenes.
  - *Azure Tool*: [Azure Computer Vision](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/)
- **Natural Language Processing (NLP)**: Understanding and generating human language.
  - *Azure Tool*: [Azure Cognitive Services for Language](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/)
- **Generative AI**: Creating new content, such as images or text, using AI models.
  - *Azure Tool*: [Azure OpenAI Service](https://azure.microsoft.com/en-us/services/openai-service/)

#### Identify Features of Content Moderation and Personalization Workloads
- **Content Moderation**: AI models that automatically detect and filter inappropriate content.
  - *Azure Tool*: [Azure Content Moderator](https://azure.microsoft.com/en-us/services/cognitive-services/content-moderator/)
- **Personalization**: Tailoring content and recommendations to individual users based on their preferences and behavior.
  - *Azure Tool*: [Azure Personalizer](https://azure.microsoft.com/en-us/services/cognitive-services/personalizer/)

#### Identify Computer Vision Workloads
Computer vision involves interpreting and processing visual data. Workloads include:
- **Image Classification**: Assigning labels to images.
- **Object Detection**: Identifying and locating objects within an image.
- **Optical Character Recognition (OCR)**: Converting images of text into machine-readable text.
- **Facial Detection and Analysis**: Identifying and analyzing human faces in images or videos.
  - *Azure Tool*: [Azure Computer Vision](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/), [Azure Face](https://azure.microsoft.com/en-us/services/cognitive-services/face/)

#### Identify Natural Language Processing Workloads
NLP deals with the interaction between computers and human language. Common workloads include:
- **Key Phrase Extraction**: Identifying important phrases in text.
- **Entity Recognition**: Detecting and classifying entities such as names, dates, and locations in text.
- **Sentiment Analysis**: Determining the sentiment or emotion expressed in text.
- **Language Modeling**: Predicting the next word or phrase in a sequence.
- **Speech Recognition and Synthesis**: Converting speech to text and vice versa.
- **Translation**: Translating text or speech from one language to another.
  - *Azure Tool*: [Azure Cognitive Services for Language](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/), [Azure Speech](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/), [Azure Translator](https://azure.microsoft.com/en-us/services/cognitive-services/translator/)

#### Identify Knowledge Mining Workloads
Knowledge mining involves extracting useful information from large datasets, often using AI and machine learning techniques.
  - *Azure Tool*: [Azure Cognitive Search](https://azure.microsoft.com/en-us/services/search/)

#### Identify Document Intelligence Workloads
Document intelligence includes extracting, processing, and understanding information from documents, such as forms and invoices.
  - *Azure Tool*: [Azure Form Recognizer](https://azure.microsoft.com/en-us/services/form-recognizer/)

#### Identify Features of Generative AI Workloads
Generative AI involves creating new content using AI models, such as:
- **Text Generation**: Creating human-like text based on input prompts.
- **Image Generation**: Creating images from descriptions or other inputs.
  - *Azure Tool*: [Azure OpenAI Service](https://azure.microsoft.com/en-us/services/openai-service/)

#### Identify Guiding Principles for Responsible AI
Responsible AI principles ensure that AI is used ethically and safely. Key considerations include:
- **Fairness**: Avoiding bias in AI solutions.
- **Reliability and Safety**: Ensuring AI solutions work reliably and do not cause harm.
- **Privacy and Security**: Protecting user data and ensuring secure AI systems.
- **Inclusiveness**: Making AI accessible to all users.
- **Transparency**: Being open about how AI systems work and make decisions.
- **Accountability**: Ensuring there is accountability for AI-driven decisions and actions.
  - *Azure Resource*: [Microsoft Responsible AI](https://www.microsoft.com/en-us/ai/responsible-ai)

### 2. Describe Fundamental Principles of Machine Learning on Azure (20–25%)

#### Identify Common Machine Learning Techniques
Machine learning techniques include:
- **Regression**: Predicting continuous values.
- **Classification**: Assigning labels to data points.
- **Clustering**: Grouping similar data points together.
- **Deep Learning**: Using neural networks with many layers for complex tasks.
  - *Azure Tool*: [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)

#### Identify Regression, Classification, and Clustering Machine Learning Scenarios
- **Regression**: Predicting house prices based on features like size and location.
- **Classification**: Email spam detection.
- **Clustering**: Customer segmentation in marketing.

#### Identify Features of Deep Learning Techniques
Deep learning involves neural networks with multiple layers (deep neural networks) to model complex patterns in data, useful for tasks like image and speech recognition.
  - *Azure Tool*: [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)

#### Describe Core Machine Learning Concepts
Core concepts include:
- **Features and Labels**: Features are input variables, and labels are the output we predict.
- **Training and Validation Datasets**: Training data is used to train the model, and validation data is used to evaluate its performance.
  - *Azure Tool*: [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)

#### Describe Azure Machine Learning Capabilities
Azure Machine Learning provides tools and services for:
- **Automated Machine Learning (AutoML)**: Automating the process of training and tuning models.
- **Data and Compute Services**: Managing data and computational resources for machine learning.
- **Model Management and Deployment**: Managing the lifecycle of machine learning models from training to deployment.
  - *Azure Tool*: [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)

### 3. Describe Features of Computer Vision Workloads on Azure (15–20%)

#### Identify Common Types of Computer Vision Solutions
- **Image Classification**: Assigning labels to images.
- **Object Detection**: Identifying and locating multiple objects within an image.
- **Optical Character Recognition (OCR)**: Extracting text from images.
- **Facial Detection and Analysis**: Recognizing and analyzing faces.
  - *Azure Tool*: [Azure Computer Vision](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/), [Azure Face](https://azure.microsoft.com/en-us/services/cognitive-services/face/)

#### Identify Features of Image Classification, Object Detection, Optical Character Recognition, and Facial Detection/Analysis Solutions
- **Image Classification**: Assigning categories to images.
- **Object Detection**: Identifying and locating multiple objects within an image.
- **Optical Character Recognition (OCR)**: Converting images of text into machine-readable text.
- **Facial Detection/Analysis**: Detecting faces and analyzing facial features and expressions.
  - *Azure Tool*: [Azure Computer Vision](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/), [Azure Face](https://azure.microsoft.com/en-us/services/cognitive-services/face/)

#### Describe Azure Tools and Services for Computer Vision Tasks
- **Azure AI Vision Service**: Provides APIs for image analysis, OCR, and more.
  - *Azure Tool*: [Azure Computer Vision](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/)
- **Azure AI Face Service**: Provides facial recognition and analysis capabilities.
  - *Azure Tool*: [Azure Face](https://azure.microsoft.com/en-us/services/cognitive-services/face/)
- **Azure AI Video Indexer**: Analyzes videos to extract insights.
  - *Azure Tool*: [Azure Video Indexer](https://www.videoindexer.ai/)

### 4. Describe Features of Natural Language Processing (NLP) Workloads on Azure (15–20%)

#### Identify Features of Common NLP Workload Scenarios
- **Key Phrase Extraction**: Identifying important phrases in text.
- **Entity Recognition**: Detecting and classifying entities in text.
- **Sentiment Analysis**: Determining the sentiment expressed in text.
- **Language Modeling**: Predicting the next word or phrase.
- **Speech Recognition and Synthesis**: Converting speech to text and vice versa.
- **Translation**: Translating text or speech between languages.
  - *Azure Tool*: [Azure Cognitive Services for Language](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/), [Azure Speech](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/), [Azure Translator](https://azure.microsoft.com/en-us/services/cognitive-services/translator/)

#### Identify Features and Uses for Key Phrase Extraction, Entity Recognition, Sentiment Analysis, Language Modeling, Speech Recognition and Synthesis, and Translation
- **Key Phrase Extraction**: Summarizing the main points in a text.
- **Entity Recognition**: Identifying entities such as names and dates.
- **Sentiment Analysis**: Measuring sentiment in customer feedback.
- **Language Modeling**: Autocompleting sentences.
- **Speech Recognition and Synthesis**: Voice assistants and transcription services.
- **Translation**: Real-time translation services.
  - *Azure Tool*: [Azure Cognitive Services for Language](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/), [Azure Speech](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/), [Azure Translator](https://azure.microsoft.com/en-us/services/cognitive-services/translator/)

#### Describe Azure Tools and Services for NLP Workloads
- **Azure AI Language Service**: Provides NLP capabilities like text analytics and language understanding.
  - *Azure Tool*: [Azure Cognitive Services for Language](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/)
- **Azure AI Speech Service**: Offers speech-to-text, text-to-speech, and translation services.
  - *Azure Tool*: [Azure Speech](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/)
- **Azure AI Translator Service**: Translates text and speech between languages.
  - *Azure Tool*: [Azure Translator](https://azure.microsoft.com/en-us/services/cognitive-services/translator/)

### 5. Describe Features of Generative AI Workloads on Azure (15–20%)

#### Identify Features of Generative AI Solutions and Models
Generative AI models can create new content, such as text, images, and code. They include:
- **GPT Models**: Generate human-like text.
- **DALL-E Models**: Create images from textual descriptions.
  - *Azure Tool*: [Azure OpenAI Service](https://azure.microsoft.com/en-us/services/openai-service/)

#### Identify Common Scenarios for Generative AI
- **Content Creation**: Writing articles or generating creative content.
- **Image Creation**: Generating images for art and design.
- **Code Generation**: Assisting in programming by generating code snippets.
  - *Azure Tool*: [Azure OpenAI Service](https://azure.microsoft.com/en-us/services/openai-service/)

#### Identify Responsible AI Considerations for Generative AI
- **Ethical Use**: Ensuring AI-generated content is used ethically.
- **Bias Mitigation**: Addressing biases in generated content.
- **Transparency**: Clearly indicating when content is AI-generated.
  - *Azure Resource*: [Microsoft Responsible AI](https://www.microsoft.com/en-us/ai/responsible-ai)

#### Describe Capabilities of Azure OpenAI Service
- **Natural Language Generation**: Generating text based on prompts.
- **Code Generation**: Assisting developers by generating code.
- **Image Generation**: Creating images from text descriptions.
  - *Azure Tool*: [Azure OpenAI Service](https://azure.microsoft.com/en-us/services/openai-service/)

## Conclusion
This cheat sheet provides an overview of the key topics for the AI-900 exam. Use the provided links and resources to deepen your understanding and prepare effectively.

Good luck with your exam!

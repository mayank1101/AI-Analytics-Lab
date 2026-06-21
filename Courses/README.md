# Courses and Certifications

This directory is a personal archive of course notes, labs, assignments, capstone projects, certificates, and reference material focused on machine learning, deep learning, generative AI, computer vision, NLP, data engineering, and Python development.

> The material reflects the course environment in which it was completed. Some notebooks use older library APIs, hosted datasets, cloud services, or API credentials and may not run unchanged in a current environment.

## Directory overview

| Directory | Contents |
| --- | --- |
| [`Coursera/`](Coursera/) | Four DeepLearning.AI programs covering TensorFlow, custom models, NLP, and generative AI. Includes weekly notebooks, assignments, quizzes, datasets, and model artifacts. |
| [`DeepLearning.AI/`](DeepLearning.AI/) | Six short courses on prompt engineering, the ChatGPT API, LangChain, fine-tuning, and LLM pretraining. |
| [`udacity/`](udacity/) | Deep Learning and Computer Vision Nanodegrees with eight substantial projects, exported reports, trained weights, and completion certificates. |
| [`datacamp/`](datacamp/) | Course notes and certificates for Python, PyTorch, image processing, MLOps, SQL, NoSQL, Dask, testing, packaging, Git, and shell tools. |
| [`datascience_Cheat_Sheets/`](datascience_Cheat_Sheets/) | Quick references for Python, NumPy, pandas, SciPy, Matplotlib, scikit-learn, PyTorch, conda, and Git. |
| [`others/`](others/) | Additional workshop material. |

The archive currently contains about 718 files (approximately 1.1 GB), including 142 Jupyter notebooks and 169 PDFs. Large datasets, checkpoints, generated output, and exported HTML/PDF versions are retained where they formed part of the original coursework.

## Course catalog

### Coursera

- [TensorFlow Developer Professional Certificate](Coursera/DeepLearning.AI-TensorFlow-Developer-Professional-Certificate/)
  - Introduction to TensorFlow for AI, ML, and deep learning
  - Convolutional neural networks
  - Natural language processing
  - Sequences, time series, and prediction
- [TensorFlow Advanced Techniques — Course 1](Coursera/DeepLearning.AI-TensorFlow-Advance-Techniques-Specialization/): custom models, layers, loss functions, functional models, Siamese networks, and gradient tapes.
- [Natural Language Processing with Classification and Vector Spaces](Coursera/DeepLearning.AI-Natural-Language-Processing-with-Classification-and-Vector-Spaces/): sentiment analysis, Naive Bayes, vector spaces, locality-sensitive hashing, and machine translation.
- [Generative AI with Large Language Models](Coursera/DeepLearning.AI-Generative-AI-with-Large-Language-Models/): transformer foundations, instruction fine-tuning, PEFT/LoRA, evaluation, reinforcement learning from feedback, and application patterns.

### DeepLearning.AI short courses

- [ChatGPT Prompt Engineering for Developers](DeepLearning.AI/DeepLearning.AI-ChatGPT-Prompt-Engineering-for-Developers/)
- [Building Systems with the ChatGPT API](DeepLearning.AI/DeepLearning.AI-Building-Systems-with-the-ChatGPT-API/)
- [LangChain for LLM Application Development](DeepLearning.AI/DeepLearning.AI-LangChain-for-LLM-Application-Development/)
- [LangChain: Chat with Your Data](DeepLearning.AI/DeepLearning.AI-LangChain-Chat-with-Your-Data/)
- [Finetuning Large Language Models](DeepLearning.AI/DeepLearning.AI-Finetuning-Large-Language-Models/)
- [Pretraining LLMs](DeepLearning.AI/DeepLearning.AI-Pretraining-LLMs/)

### Udacity Nanodegrees

#### Deep Learning

1. [Predicting Bike Sharing Patterns](udacity/Udacity-Deep-Learning-Nano-Degree-Program/Project-1%20Bike%20Sharing/) — a neural network implemented with NumPy.
2. [Dog Breed Classification](udacity/Udacity-Deep-Learning-Nano-Degree-Program/Project-2%20Dog%20Breed%20Classification/) — CNNs, transfer learning, face detection, and breed prediction.
3. [TV Script Generation](udacity/Udacity-Deep-Learning-Nano-Degree-Program/Project-3%20TV%20Script%20Generation/) — recurrent neural network text generation.
4. [Face Generation](udacity/Udacity-Deep-Learning-Nano-Degree-Program/Project-4%20Face%20Generation/) — a DCGAN trained to generate faces.
5. [Deploying a Sentiment Analysis Model](udacity/Udacity-Deep-Learning-Nano-Degree-Program/Project-5%20Deploying%20Sentiment%20Analysis%20Model/) — PyTorch inference deployed through Amazon SageMaker with a small web client.

#### Computer Vision

1. [Facial Keypoint Detection](udacity/Udacity-Computer-Vision-Nano-Degree-Program/Project-1%20Facial%20Key%20Point%20Detection/) — data augmentation, CNN regression, Haar cascades, and face filters.
2. [Automatic Image Captioning](udacity/Udacity-Computer-Vision-Nano-Degree-Program/Project-2%20Automatic%20Image%20Captioning/) — a CNN encoder/RNN decoder trained with MS COCO data.
3. [Object Tracking and Localization](udacity/Udacity-Computer-Vision-Nano-Degree-Program/Project-3%20%20Object%20Tracking%20and%20Localization/) — robot sensing, constraints, and graph SLAM.

### DataCamp

- [Python Programmer Career Track](datacamp/Python%20Programmer%20Career%20Track/): Python fundamentals, pandas, functions, performance, dates, regex, scraping, shell, conda, Git, software engineering, packaging, unit testing, and OOP.
- [Deep Learning with PyTorch](datacamp/Deep%20Learning%20with%20PyTorch/): introductory and intermediate deep learning plus text applications.
- [Image Processing with Python Track](datacamp/Image%20Processing%20With%20Python%20Track/): general image processing, biomedical images, and Keras.
- [MLOps](datacamp/MLOps/): Docker and MLflow.
- [SQL](datacamp/SQL/) and [NoSQL databases](datacamp/NoSql-Databases/): joins, intermediate SQL, NoSQL concepts, and MongoDB with Python.
- [Parallel Programming with Dask](datacamp/Parallel%20Programming%20With%20Dask%20in%20Python/).

Most DataCamp directories contain chapter PDFs rather than executable source code.

## Running the notebooks

There is no single environment for the entire archive. Treat each course or project as an independent workspace.

1. Open a terminal in the relevant course directory.
2. Create an isolated virtual environment.
3. Inspect the notebook imports and any local `requirements.txt` before installing dependencies.
4. Start JupyterLab or Jupyter Notebook and run the material in its original order.

Common dependencies include Jupyter, NumPy, pandas, Matplotlib, scikit-learn, TensorFlow, PyTorch, torchvision, OpenCV, NLTK, Transformers, Datasets, LangChain, and OpenAI client libraries. Some notebooks additionally require:

- API keys loaded from environment variables or a local `.env` file;
- external downloads such as MS COCO, dog images, or TensorFlow datasets;
- Google Colab, Amazon SageMaker, or another course-specific hosted runtime;
- versions of TensorFlow, PyTorch, LangChain, or the OpenAI SDK contemporary with the course.

Do not commit credentials. Review notebook cells before execution, especially cells that download data, invoke paid APIs, or create cloud resources.

## Certificates

### DeepLearning.AI

- [Pretraining LLMs](https://learn.deeplearning.ai/accomplishments/604fd916-7f61-472e-b0a4-e563a37e75e9)
- [LangChain: Chat with Your Data](https://learn.deeplearning.ai/accomplishments/be0b7f8c-b46d-4a3d-8079-a83031c5ad40)
- [LangChain for LLM Application Development](https://learn.deeplearning.ai/accomplishments/971fc017-be28-48d2-a819-bd6e736b1422)
- [Finetuning Large Language Models](https://learn.deeplearning.ai/accomplishments/afbb8ed4-b0ee-4b1b-9a22-dc8ff6bfce8a)
- [Building Systems with the ChatGPT API](https://learn.deeplearning.ai/accomplishments/8400191e-b3e6-470d-990d-287c69d67a34)
- [ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/accomplishments/84dcd38d-b215-47aa-9327-592b04a6fbc3)

### Udacity

- [Deep Learning Nanodegree](https://graduation.udacity.com/confirm/P5RJJDVZ)
- [Computer Vision Nanodegree](https://graduation.udacity.com/confirm/XC3QK2NS)

Local certificate PDFs are also stored in their respective Nanodegree directories.

### Coursera

- [Generative AI with Large Language Models](https://www.coursera.org/account/accomplishments/verify/DJSFSGQL797Z)
- [TensorFlow Developer Professional Certificate](https://www.coursera.org/account/accomplishments/professional-cert/KJ4HV8UG2MDZ)
- [Natural Language Processing with Classification and Vector Spaces](https://www.coursera.org/account/accomplishments/verify/L7VKYVGWZYDE)
- [Introduction to Intel Distribution of OpenVINO Toolkit](https://www.coursera.org/account/accomplishments/verify/62DB9HFLBR96)

### DataCamp

- [Introduction to MLflow](https://www.datacamp.com/completed/statement-of-accomplishment/course/b2dbab2ddaefb6d748177c262b0ff21e48944e1c)
- [Introduction to Docker](https://www.datacamp.com/completed/statement-of-accomplishment/course/6f38e7914f8fedb657bcb840e66804b7f2a82c57)
- [Deep Learning for Text with PyTorch](https://www.datacamp.com/completed/statement-of-accomplishment/course/d506cb72ea084015676a9fd168e8c46703c6e238)
- [Intermediate Deep Learning with PyTorch](https://www.datacamp.com/statement-of-accomplishment/course/30a7578b58d919985250b63c98f0aa52f718ccda)
- [Introduction to Deep Learning with PyTorch](https://www.datacamp.com/statement-of-accomplishment/course/0de8125a7d33c0e94bd531b9c43ba732811690da)
- [Image Processing with Python](https://www.datacamp.com/statement-of-accomplishment/track/612a10bce51aaba65c886838ac3b601559f20564)
- [Biomedical Image Analysis in Python](https://www.datacamp.com/statement-of-accomplishment/course/12335bc319798d1b02b55028156ee61afad273ed)
- [Image Processing with Keras in Python](https://www.datacamp.com/statement-of-accomplishment/course/2578f4cdfe65e71112118113a31bdad1e6024f62)
- [Python Programmer Career Track](https://www.datacamp.com/statement-of-accomplishment/track/541cc7ab0cc98d1e643f8906976bea5e552262e9)
- [Developing Python Packages](https://www.datacamp.com/statement-of-accomplishment/course/08438e0f1c1ff50e6f0aa71091acf598879bd0b2)
- [Parallel Computing with Dask](https://www.datacamp.com/statement-of-accomplishment/course/3de6d6228ae138accf0d306c58223934aeb6415c)
- [Web Scraping in Python](https://www.datacamp.com/statement-of-accomplishment/course/9f5e6c1adf14922b4cb3af743286a250d462cf96)
- [Python Fundamentals](https://www.datacamp.com/statement-of-accomplishment/track/c81234c201006259b80f8e2ab7a2280be3af63e1)
- [Python Data Science Toolbox, Part 1](https://www.datacamp.com/statement-of-accomplishment/course/9d126e69bf1cfed1b0a5ba63359da8f58b08927c)
- [Python Data Science Toolbox, Part 2](https://www.datacamp.com/statement-of-accomplishment/course/bef354ba9fe3458e81713550c3f2687a34a81f62)
- [Introduction to Shell](https://www.datacamp.com/statement-of-accomplishment/course/4edc0d8b5e621d610dd39995c845208ccc1e0966)
- [Introduction to Git](https://www.datacamp.com/statement-of-accomplishment/course/cf1ab0b09db1b0254314c8abf353540a57df5a42)
- [Joining Data in SQL](https://www.datacamp.com/completed/statement-of-accomplishment/course/2c73b64a16e0c70d833e756fcae99c296045c846)
- [Intermediate SQL](https://www.datacamp.com/completed/statement-of-accomplishment/course/b0a356d5af81687384b52cdcff895d488f37c76a)
- [NoSQL Concepts](https://www.datacamp.com/statement-of-accomplishment/course/1d43c4c0cc2517aaf9e803ec88d5ad3c65eba7e3)
- [Introduction to MongoDB in Python](https://www.datacamp.com/statement-of-accomplishment/course/e4e9588237e4335a41e29bfc348103c1e010cf5e)

### Other

- [Blockchain](https://www.guvi.in/verify-certificate?id=m8168pV8n3qC190d51)
- [Finance Workshop 2020–21, IIM Tiruchirappalli](others/Finance%20Workshop%202020-21.pdf)

## Repository notes

- Notebook outputs and HTML/PDF exports are preserved for reference even when a runtime is unavailable.
- Model files (`.pt`, `.pkl`, `.h5`, and related checkpoints) are course artifacts and are not guaranteed to be portable across framework versions.
- Course content remains subject to the terms and licenses of its original provider; this repository's [`LICENSE`](../LICENSE) applies only where the author has the right to license the material.

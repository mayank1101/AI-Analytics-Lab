# AI & Analytics Lab

A portfolio and learning archive covering artificial intelligence, machine learning, deep learning, computer vision, natural language processing, data analytics, MLOps, and SQL.

The repository combines completed projects with the coursework, assignments, certificates, datasets, and reference material that supported them. It is organized as an archive of independent notebooks and projects rather than a single installable application.

## Repository map

| Directory | Description |
| --- | --- |
| [`Projects/`](Projects/) | Applied portfolio work: 10 Udacity projects, 10 DataCamp case studies, and a 9-module SQL learning track. See the [project catalog](Projects/README.md). |
| [`Courses/`](Courses/) | Course notebooks, assignments, certificates, and reference material from Coursera, DeepLearning.AI, Udacity, and DataCamp. See the [course catalog](Courses/README.md). |

```text
Mayank-AI-Lab/
├── Courses/
│   ├── Coursera/
│   ├── DeepLearning.AI/
│   ├── datacamp/
│   ├── datascience_Cheat_Sheets/
│   ├── others/
│   └── udacity/
├── Projects/
│   ├── DataCampProjects/
│   ├── NamasteSQL/
│   └── UdacityProjects/
├── LICENSE
└── README.md
```

## Featured work

| Project | Area | Highlights |
| --- | --- | --- |
| [Automatic Image Captioning](Projects/UdacityProjects/Project%20-%20Automatic%20Image%20Captioning/) | Computer vision and NLP | CNN encoder, RNN decoder, MS COCO data, training and inference notebooks, saved checkpoints |
| [Pneumonia Detection from Chest X-Rays](Projects/UdacityProjects/Project%20-%20Pneumonia%20Detection%20from%20Chest%20X-Rays/) | Medical imaging | DICOM exploration, Keras classification, threshold evaluation, inference pipeline, FDA-style report |
| [Facial Keypoint Detection](Projects/UdacityProjects/Project%20-%20Facial%20Key%20Point%20Detection/) | Computer vision | PyTorch CNN regression, image augmentation, Haar cascades, end-to-end face processing |
| [Deploying a Sentiment Analysis Model](Projects/UdacityProjects/Project-%20Deploying%20Sentiment%20Analysis%20Model/) | NLP and deployment | PyTorch LSTM, SageMaker training and serving code, inference handlers, web client |
| [Object Tracking and Localization](Projects/UdacityProjects/Project%20-%20Object%20Tracking%20and%20Localization/) | Robotics | Robot motion and sensing, landmark constraints, Graph SLAM |
| [Credit Card Transactions Analysis](Projects/NamasteSQL/all_projects/) | SQL analytics | Business-oriented queries using aggregation, ranking, window functions, and cumulative metrics |

Additional work includes neural style transfer, dog breed classification, TV script generation, bike-sharing demand prediction, sentiment classification, public dataset analysis, and a structured collection of advanced SQL exercises.

## Technical coverage

- **Languages:** Python and SQL
- **Data analysis:** pandas, NumPy, SciPy, Matplotlib, seaborn, scikit-learn, and Dask
- **Deep learning:** PyTorch, torchvision, TensorFlow, and Keras
- **Computer vision:** OpenCV, CNNs, transfer learning, image captioning, keypoint detection, medical imaging, and style transfer
- **NLP and generative AI:** RNNs, LSTMs, Transformers, Hugging Face libraries, LangChain, fine-tuning, and prompt engineering
- **Deployment and MLOps:** Amazon SageMaker, Docker, MLflow, model serving, and simple web interfaces
- **Databases:** joins, CTEs, window functions, stored procedures, functions, indexes, SQL analytics, MongoDB, and NoSQL concepts

## Using the repository

Clone the repository and open the project or course directory you want to explore:

```bash
git clone https://github.com/mayank1101/Mayank-AI-Analytics-Lab.git
cd Mayank-AI-Analytics-Lab
```

Most work is notebook-first. There is no repository-wide dependency file because the material spans multiple course generations and framework versions. For executable notebooks:

1. Treat each project or course as an independent environment.
2. Create a virtual environment in that directory.
3. Inspect notebook imports and any local `requirements.txt` before installing packages.
4. Run notebooks in their numbered or documented order.

Some notebooks depend on external datasets, pretrained weights, API credentials, Google Colab, or Amazon SageMaker. Older work may require library versions contemporary with the original course. Review cells before execution, particularly those that download data, invoke paid APIs, or create cloud resources.

## Archive notes

- The repository includes notebooks, source code, SQL scripts, local datasets, exported reports, trained checkpoints, and generated output.
- HTML and PDF exports are retained so results remain viewable when the original runtime is unavailable.
- Large model artifacts are educational outputs and are not guaranteed to be portable across current framework versions.
- Never add API keys, cloud credentials, or populated `.env` files to source control.

## License

Original code in this repository is available under the [MIT License](LICENSE). Course material, datasets, certificates, and third-party assets remain subject to the terms and licenses of their respective owners.

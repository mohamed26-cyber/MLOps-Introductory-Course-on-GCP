# MLOps introductory course on Google Cloud Platform (GCP)

This course is being taught at as part of [Master Year 2 Data Science Supaero](https://supaerodatascience.github.io/index.html)


<img src="https://www.isae-supaero.fr/wp-content/uploads/2025/03/logo.svg" width="180">


This course is designed to be held during 5 classes lasting 3 hours each. This course will span over 15 hours.

## A bit of context

MLOps is a rapidly evolving field that combines machine learning and software engineering to streamline the deployment, monitoring, and maintenance of machine learning models in production. As machine learning systems become increasingly complex, the need for robust workflows and efficient collaboration between data scientists and engineers grows. This class will focus on the tools and practices that enable teams to develop and deploy machine learning models at scale. The goal is to equip students with the skills necessary to manage the full lifecycle of machine learning models, from experimentation to deployment and monitoring, using industry-standard tools and platforms.

## Course syllabus

The course covers the basics of MLOps, applied on Google Cloud Platform (GCP).

### Lecture slides

- What is MLOps ?
- Mlflow framework
- FlowML on Vertex AI (GCP)
- Deploy a model behing an endpoint on GCP. Batch and streaming inference
- ML pipelines on GCP 
- Deploy a RAG (Retrieval-Augmented Generation) chatbot on Vertex AI

### Classes

The notebooks for the labs can be found in the `labs` folder of
this Git repository.

**Class #1**
- What is MLOps ?
- Start MLOps with Mlflow framework
- Mlflow lab on local computers

**Class #2**
- Introducing GCP AI services (Vertex AI)
- Focus on FlowML services on GCP
- FlowML lab

**Class #3**
- Deploy a model behind a Vertex AI endpoint
- Batch and streaming inference
- Scaling
- A/B testing

**Class #4**
- Deploy a model behind a Vertex AI endpoint
- Batch and streaming inference
- Scaling

**Class #5**
- What is a RAG ?
- Implementing a RAG on Vertex AI

## Installation

### Prerequisites

- **Python >= 3.10.x**
- Git
- GCP Account with credits

### Step 1: Clone the repository

```bash
git clone https://github.com/jdiamant/MLOps-Introductory-Course-on-GCP.git
cd MLOps-Introductory-Course-on-GCP
```

### Step 2: Installation (For Lab 1)

Navigate to the lab folder and create a virtual environment:

```bash
# Windows - Try these commands in order until one works:
cd labs/1_mlflow

# Option 1: Using Python Launcher
py -3.10 -m venv venv

# Option 2: Direct python command
python -m venv venv

# Option 3: Full path (adjust path to your Python installation)
C:\Python310\python.exe -m venv venv

# Activate
venv\Scripts\activate

# Verify Python Version
python --version  # Should show Python 3.10.x

# Install Dependencies
pip install -r requirements.txt

# macOS/Linux
cd labs/1_mlflow
python3.10 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Evaluation

Hands-on implementation on notebooks that will be assessed by the teacher.
  
## Acknowledgments

This lecture was built by Headmind Partners AI and being taught by Jean Diamant.

We thank the teachers of Supaero for their confidence, especially Emmanuel Rachelson and Dennis Wilson.

## License

All the code in this repository belongs to [HeadMind Partners AI](https://www.headmind.com/en/)

<img src="https://user-images.githubusercontent.com/63151412/167391313-4683cc69-2bf6-4597-b767-5c18e2bbbfa0.png" width="180">
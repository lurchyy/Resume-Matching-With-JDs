# Requirements:
Install requirements via:
```bash
pip install -r requirements.txt
```

# Kaggle Dataset(Required for Task 1 And Task 3):
https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset

# Task 1:
task1.ipynb is used to parse and extract relevant information from resumes. I have also added functionality to save the extracted information(skills, education, experience and resume category) in a CSV file.


# HuggingFace Dataset(Required For Task 2 and Task 3):
https://huggingface.co/datasets/jacob-hugging-face/job-descriptions/viewer/default/train?row=0

# Task 2:
tsk2.ipynb extracts skills from the HuggingFace dataset. I've made use of the Datasets library to do so. The extracted data is cleaned and stored in another CSV.

# Task 3:
The actual matching happens in 3.ipynb. I've made use of SkLearn's Cosine Similarity to match **skills required from the output CSV of Task 2** with **skills that the candidate has**, extracted from
**task1.ipynb**.

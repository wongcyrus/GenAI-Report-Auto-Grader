# GenAI-Report-Auto-Grader
Using GenAI to grade word assignment report.


## Using Vertex AI Gemini Pro

### GCP application Login 
```
gcloud auth application-default login
gcloud config set project XXXXX
gcloud auth application-default set-quota-project XXXXX
```

### Enable Google Cloud API
```
gcloud services enable speech.googleapis.com
gcloud services enable aiplatform.googleapis.com
```
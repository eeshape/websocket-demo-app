
pip install -r backend/requirements.txt 



cd frontend
vi scripot.js

const PROXY_URL = "ws://localhost:8080";
const PROJECT_ID = "qwiklabs-gcp-02-6aaa058f026e";


python -m http.server

python backend/main.py

http://localhost:8000/


gcloud auth print-access-token

gcloud init
gcloud auth application-default login      

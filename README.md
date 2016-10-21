# enCORE
EECS 338 Practicum in A.I.

# Setup

1. Download Google Cloud SDK (https://cloud.google.com/sdk/downloads) and put the folder in the same dir as the other files.
2. Run `$ gcloud auth activate-service-account --key-file=DualEncore-86da983e6c43.json`
3. Run `$ export GOOGLE_APPLICATION_CREDENTIALS=DualEncore-86da983e6c43.json`


# Run from Terminal

1. You can get an authentication token with $ gcloud auth print-access-token
2. Run a curl command such as
  `$ curl -s -k -H "Content-Type: application/json" \
    -H "Authorization: Bearer AUTH-TOKEN" \
    https://language.googleapis.com/v1beta1/documents:analyzeEntities \
    -d @entity-request.json`
    
  You can replace the entity-request.json with a different enitity analysis request
    
    
# Run from Python File

You can run programs from python files, such as
  `$ python sentiment-analysis.py reviews/bladerunner-pos.txt`
  
  
More at: https://cloud.google.com/natural-language/docs/getting-started

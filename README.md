# enCORE
EECS 338 Practicum in A.I.

1. Download Google Cloud SDK and put the folder in the same directory as the other files.
2. Run $ gcloud auth activate-service-account --key-file=DualEncore-86da983e6c43.json
3. Run $ export GOOGLE_APPLICATION_CREDENTIALS=DualEncore-86da983e6c43.json
4. Then you can run programs from python files, such as:
  $ python sentiment-analysis.py reviews/bladerunner-pos.txt
  
More at: https://cloud.google.com/natural-language/docs/getting-started

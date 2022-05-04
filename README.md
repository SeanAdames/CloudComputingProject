# CloudComputingProject
Group Project covering Google Dataflow and Google Big Query 

In this repository there are two test Java functions and the main Java lineCount function used to create our data, these functions are merely for reference as they were plugged in to Google Cloud Terminal and executed from there.

Project Video Submission Link: https://drive.google.com/drive/folders/1J596Fjr2qEkI7WR1pLcxc1a0G233ykyX?usp=sharing

Google Dataflow Link: https://console.cloud.google.com/dataflow/jobs/us-central1/2022-05-04_10_43_51-4484581473226600916?project=cloudcomputingdataflow
**This contains the data pipeline chart via Google Dataflow

Google Cloud Storage Link: https://console.cloud.google.com/storage/browser/_details/dataflow-cloudcomputingdataflow/linecount-00000-of-00001;tab=live_object?project=cloudcomputingdataflow
**This contains the data after it is piped through with Google Dataflow

Verification that Google Dataflow successfully uploaded our data passed in from our Java script: https://storage.cloud.google.com/dataflow-cloudcomputingdataflow/linecount-00000-of-00001?_ga=2.228040859.-720083893.1649035167&_gac=1.258673528.1649045030.CjwKCAjwi6WSBhA-EiwA6Niok6GATVCoGJBljVJ8VtvwJfeyLIj5qKI0BZwgwkA3wEPyMWkrgm4RLhoC4RIQAvD_BwE

**NOTE!! The link above will take users to a webpage containing an output stored in our Google Cloud Storage. The output should read 5525, indicating that our Java function has worked correctly, piped the output through Google Dataflow and successfully stored it in our Cloud Storage. The Google Cloud project will be deleted on June 15 as not overuse data on service.

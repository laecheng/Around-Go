# Around

- This is Google Cloud Computing and React based application. The project has 3 tier, The presentation tier is implemented using ReactJS, for the logic tier, the Go service is running on the Google App Engine to handle the request from clients. For the data tier,  Go service will store the image to Google Cloud Storage, Store the location information to Elastic Search, and will also forward the data to a BigTable. Also I create a pipeline using DataFlow to dump the data from BigTable to BigQuery to do the analysis.

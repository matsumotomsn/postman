# Open Source POSTman collection for GBDX

A set of example HTTP requests for use with POSTman for hitting the GBDX APIs.

* Authorization (get Oauth2 token)
* Catalog
* Workflow
* Material Sets
* Ordering
* S3 Credential Service
* Browse Image Thumbnail Service

# Setup

1.  Get postman:  http://getpostman.com
2.  Import environment variables (Click "manage environments" and import GBDX.postman_environment)
3.  Set your username, password, & api key in the environment variables.
4.  Import the Postman Collection (Click "Import", find the file GBDX.json.postman_collection)

# Operation

1.  First get your user bearer token.  Execute the "Get Bearer Token" request in the Auth folder.
2.  When your token comes back in the response, set the "token" environment variable with the value of your token.
3.  Play with other requests :)

This is the starter project for the photo timelime application.

A Couple Reminders
-------------------

* Make sure to name your project uniquely and set the PROJECT_ID in the shell you are using
`export PROJECT_ID=name`

* Create a Cloud Storage bucket for the application
`gsutil mb gs://${PROJECT_ID}`
`export CLOUD_STORAGE_BUCKET=${PROJECT_ID}`

* Create a services account key (https://console.cloud.google.com/apis/credentials/serviceaccountkey)
`export GOOGLE_APPLICATION_CREDENTIALS=[path]`

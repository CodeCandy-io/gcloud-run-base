# Configure gcloud service account

Be sure your service account have this roles

- Cloud function service agent
- project editor

See more: https://cloud.google.com/functions/docs/concepts/iam

## Workflow config

- GCP_SA_KEY

  This key should be created, encoded as a Base64 string and stored as a github secret.

```
cat my-key.json | base64
```

- GCP_PROJECT_ID

Your Google cloud project id

- APP_NAME

  Your app name (create docker image)

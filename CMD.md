## Commands

- https://cloud.google.com/endpoints/docs/openapi/get-started-app-engine-dotnet

```
gcloud components update
gcloud auth login
gcloud config set project vertical-idea-214212

gcloud app create --project vertical-idea-214212 --region=asia-south1

gcloud endpoints services deploy openapi.yaml

```

```
gcloud beta app deploy publish/app.yaml
gcloud app logs tail -s default
```
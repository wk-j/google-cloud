## Commands

- https://cloud.google.com/endpoints/docs/openapi/get-started-app-engine-dotnet

```bash
gcloud components update
gcloud auth login
gcloud config set project vertical-idea-214212

gcloud app create --project vertical-idea-214212 --region=asia-south1

gcloud endpoints services deploy openapi.yaml

```

```bash
d-cake publish
gcloud beta app deploy publish/app.yaml
y
gcloud app logs tail -s default
```

```bash
gcloud beta sql connect central-logger-214910:asia-southeast1:central-logger -u postgres
gcloud beta sql connect --project central-logger-214910 central-logger -u postgres

gcloud beta compute instances list

brew install libpq
```
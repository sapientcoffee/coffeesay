# TL;DR
A terminal like demo app that uses the best Linux CLI command `cowsay` that will eventually be converted to `coffeesay` when time permits. 

Just a little bit of fun

# Deploy

You can deploy to Google Cloud Artifact Registry using buildpacks with something like;

```
gcloud builds submit --pack image=europe-docker.pkg.dev/cymbal-coffee-sandbox/coffeesay
```
And then deploy that container image to Cloud Run.
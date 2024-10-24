# Hello, there!. Let's deploy to Cloud Run Functions

1. Build Docker by dockerfile
 ```bash
docker build -t gcr.io/[PROJECT_ID]/[SERVICE_NAME] .
```
2. Create image for docker
```bash
 docker push gcr.io/[PROJECT_ID]/[SERVICE_NAME]
```
3. Deploy it!
```bash
   gcloud run deploy [SERVICE_NAME] \
    --image gcr.io/[PROJECT_ID]/[SERVICE_NAME] \
    --platform managed \
    --region [REGION] \
    --allow-unauthenticated
```

 # Wait for a few seconds/minutes and you will get a link that you have to copy to the Front-end section


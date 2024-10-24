# Hello, there!. Let's deploy back-end part with Cloud Run Functions 🚀🚀

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

# Front-End 
![image](https://github.com/user-attachments/assets/19843b0c-70f8-4347-b160-f8f97dad8822)

# Below is the final result of the Machine Learning project with deployment using Google Cloud, everything goes well!
![image](https://github.com/user-attachments/assets/b8d5a13c-69ac-40e7-85fb-b9990a7da128)

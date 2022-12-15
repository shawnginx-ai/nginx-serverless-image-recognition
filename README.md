# nginx-serverless-image-recognition

NGINX Serverless AI: Image Recognition Service (Web Crawler &amp; Image Analysis)

![](./docs/img/nginx-serverless-ai-img-recognition-crawler-analysis.png)

## Serverless Crawler Service

![](./docs/img/serverless-crawler-service.png)

## Serverless Analysis Service

Connect Amazon Rekognition Service with downloaded image files.

> Note: Amazon Rekognition makes it easy to add image and video analysis to your applications. 

![](./docs/img/serverless-analysis-service.png)

## Serverless UI Service
- `/urls`: Get all URLs that are submitted for the analysis.
- `/images`: Get all images that are analyzed for the specific URL.
- `/urls/analysis`: submit URL for analysis.

![](./docs/img/serverless-ui-service.png)

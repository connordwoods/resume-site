Connor Woods (author)

Resume website project utilizing multiple cloud technologies

This site is built using various AWS technologies as a demonstration of knowledge. It is a simple HTML page (with CSS/JS) hosted in an S3 bucket and delivered via CloudFront from edge locations nearest the user. A custom domain is assigned to the distribution by attaching a TLS certification and configuring Route 53 DNS routing.

This site is version controlled in GitHub while being continuously integrated and deployed through Actions and SAM templates to automate infrastructure deployment. It is also serverless, using a REST API Gateway to invoke Lambda functions for operations such as DynamoDB queries.
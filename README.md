# Resume

This repository hosts the data for my resume which is hosted at [http://andrew.sprou.se](http://andrew.sprou.se).
Whenever there is a push to this repo a SNS webhook fires which triggers a Lambda function that renders my resume and pushes it to S3 where it is hosted. Check out the actual website/Lambda code [here](https://github.com/asprouse/resume-website).

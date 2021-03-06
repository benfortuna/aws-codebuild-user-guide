# AWS CodeBuild Use Case\-Based Samples<a name="use-case-based-samples"></a>

You can use these use case\-based samples to experiment with AWS CodeBuild:


****  

| Name | Description | 
| --- | --- | 
| [Amazon ECR Sample](sample-ecr.md) | Uses a Docker image in an Amazon ECR repository to use Apache Maven to produce a single JAR file\. | 
| [Docker Sample](sample-docker.md) | Uses a build image provided by AWS CodeBuild with Docker support to produce a Docker image with Apache Maven\. Pushes the Docker image to a repository in Amazon ECR\. You can also adapt this sample to push the Docker image to Docker Hub\. | 
| [GitHub Enterprise Sample](sample-github-enterprise.md) | Uses AWS CodeBuild with GitHub Enterprise as the source repository, with certificates installed and webhooks enabled, to rebuild the source code every time a code change is pushed to the repository\. | 
| [GitHub Pull Request Sample](sample-github-pull-request.md) | Uses AWS CodeBuild with GitHub as the source repository, and webhooks enabled, to rebuild the source code every time a code change is pushed to the repository\. | 
| [Use AWS Config with AWS CodeBuild Sample](how-to-integrate-config.md) | Shows how to set up AWS Config\. Lists which AWS CodeBuild resources are tracked and describes how to look up AWS CodeBuild projects in AWS Config\. | 
| [Build Badges Sample](sample-build-badges.md) | Shows how to set up AWS CodeBuild with build badges\. | 
| [Build Notifications Sample](sample-build-notifications.md) | Uses Apache Maven to produce a single JAR file\. Sends a build notification to subscribers of an Amazon SNS topic\. | 
| [Docker in Custom Image Sample](sample-docker-custom-image.md) | Uses a custom Docker image to produce a Docker image\. | 
| [AWS CodeDeploy Sample](sample-codedeploy.md) | Uses Apache Maven to produce a single JAR file\. Uses AWS CodeDeploy to deploy the JAR file to an Amazon Linux instance\. You can also use AWS CodePipeline to build and deploy the sample\. | 
| [AWS Lambda Sample](sample-lambda.md) | Uses AWS CodeBuild along with Lambda, AWS CloudFormation, and AWS CodePipeline to build and deploy a serverless application that follows the AWS Serverless Application Model \(AWS SAM\) standard\. | 
| [Elastic Beanstalk Sample](sample-elastic-beanstalk.md) | Uses Apache Maven to produce a single WAR file\. Uses Elastic Beanstalk to deploy the WAR file to an Elastic Beanstalk instance\. | 
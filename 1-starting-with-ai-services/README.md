# Starting with AI Services for Content Moderation

In this module you will learn about different APIs in Amazon AI services including Amazon Rekognition, Amazon Textract and Amazon Comprehend that can be used for content moderation and compliance.

## Create an Instance to run Jupyter Notebook for Prototyping

In this step we will create a SageMaker Notebook instance using a CloudFormation template so we can use Jupyter Notebook to prototype.

***SageMaker or Jupyter Notebook is not required to use AI Service such as Amazon Rekognition, but we will use Jupyter as IDE for quick prototyping and to learn various APIs.***

1. Click on the button below to launch the CloudFormation template.

Region| Launch
------|-----
US East (N. Virginia) | [![Create SageMaker Instance](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/images/cloudformation-launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?stackName=content-moderation&templateURL=https://aws-workshops-us-east-1.s3.amazonaws.com/content-moderation/deployment/cf-sage-maker.yaml)


2. Check the checkbox for "I acknowledge that AWS CloudFormation might create IAM resources with custom names" and click Create.

3. You should now see the screen with status CREATE_IN_PROGRESS.

4. Refresh list of stacks to see current status of the stack. It will take about 5 minutes to deploy. Once it is complete you should see a status of CREATE_COMPLETE.


## Open Jupyter Instance

1. After CloudFormation template is complete, click on the Outputs tab and click on the link for NotebookInstanceName. This will take you to your newly created Sagemaker Notebook instance.

2. From your SageMaker Notebook instance click on the Open Jupyter button.

3. You will now be redirected to the Jupyter UI.

4. Click on the New button and choose Terminal.

5. In the terminal type:
```
cd SageMaker
git clone https://github.com/darwaishx/content-moderation.git
```

6. Go back to Jupyter home screen by clicking on the Jupyter logo on the top left and refresh to see the folder `content-moderation`.

7. Click on the `content-moderation` folder, then `1-starting-with-ai-services` and then `notebooks`.

8. Open each of the Notebooks in order, and follow the directions in the Notebook to run each cell and review its output.

## Completion
You have successfully used Amazon Rekognition to detect unsafe content in images and videos. In the next module, [Custom Comprehend model to detect unsafe content ](../2-custom-comprehend), you will learn how to use Amazon Comprehend custom entities to detect unsafe text at scale in images and videos.

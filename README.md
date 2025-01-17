# Visual Ad Creation of Octank Dog Food using Amazon Titan Image Generator v2

Amazon Titan Image Generator

<img width="783" alt="Screenshot 2025-01-17 at 11 12 49" src="https://github.com/user-attachments/assets/ca442dfd-1194-4f1e-bccf-0c55e7618393" />


# Activity Guide: Creating a Visual Ad for Octank Dog Food Using Amazon Titan Image Generator V2

1. Introduction

- Objective: Utilize Amazon Titan Image Generator V2 to design a visually compelling advertisement for Octank Dog Food, leveraging text-to-image generation, outpainting, and color-guided generation.
Scenario: Create a dynamic ad using AI-driven tools, integrating creative design and advanced AI models.

2. Set Up SageMaker Studio (Amazon SageMaker)

- Launch SageMaker Studio:
Open the AWS Management Console, navigate to SageMaker Studio, and set up a domain with Jupyter Notebook access.
- Configure Resources:
Use an ml.t3.medium instance for development.

3. Enable Amazon Titan Image Generator V2 (Amazon Bedrock)

- Verify Deployment:
Ensure the amazon.titan-image-generator-v2 foundation model is enabled in the same region as SageMaker Studio.
- Attach IAM Roles:
Grant Bedrock access to SageMaker Studio via IAM policies.

4. Install Dependencies and Set Up Environment (Jupyter Notebook)

- Prepare Jupyter Notebook:
Load the prewritten code for setting up the environment, provided in the activity repository.
- Install Required Libraries:
Run setup cells to install dependencies such as Boto3 and Matplotlib.
- Validate Environment:
Confirm that libraries and the Bedrock API client are correctly configured.

5. Generate Images with Titan Image Generator V2 (Amazon Bedrock, Jupyter Notebook)

- Input Text Prompts:
Example:
Create an image of a golden retriever enjoying Octank Dog Food, in a bright outdoor park setting.
- Run Image Generation:
Execute code to send prompts to Titan Image Generator V2 and retrieve image outputs.
- Outpainting:
Use outpainting techniques to expand the canvas and add elements around the core image.
- Apply Color Guidance:
Specify a color palette (e.g., #FFD700, #228B22) for branding consistency.

6. Test and Save Outputs (Jupyter Notebook, Amazon S3)

- Review and Evaluate:
Check generated images for alignment with the prompt.
- Save Results to S3:
Store generated images in a dedicated S3 bucket for further use.
- Generate Variations:
Experiment with different prompts and settings to create multiple ad versions.

7. Clean Up Resources

- Delete Jupyter Space:
Go to the SageMaker Studio tab, stop the running space, and delete it from the Actions column.
- Remove S3 Bucket:
Empty and delete the bucket used for storing outputs.
- Delete Domain:
Navigate to Domain Settings in SageMaker Studio and delete the domain.

8. Troubleshooting

- Issue: Model Invocation Fails:
Confirm the foundation model is deployed and IAM roles are properly configured.
- Issue: Slow Processing:
Switch to a higher-capacity instance like ml.p3.2xlarge for faster results.

9. Summary

Successfully utilized Amazon Titan Image Generator V2 to design a visually appealing advertisement.
Integrated text-to-image generation, outpainting, and branding techniques for a dynamic ad creation workflow.

Note: The code used in this activity guide will be made available in the repository.

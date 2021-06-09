# Cloud-Computing-Project
This repo holds the files from my final group project for QTM 350 (Cloud Computing) at Emory University. In this class, we learned how to use fundamental AWS Compute, Storage and ML resources, including working with Amazon EC2 instances, Amazon S3 buckets, Sagemaker notebook instances and more. The major role I played in this collaborative project was designing and writing the [blog post](https://github.com/nikivasan/Cloud-Computing-Project/blob/b28fe9eed2bdb4bcf014d0f5032965e2418b6d6c/350ProjectBlog3%20.ipynb) that encapuslated our work. Our project was determine if there are any hidden variables that may disrupt the efficacy of a given AWS ML service. This is a summary of our project: 

For our project, we will be using Amazon Polly and Transcribe to go from text input to voice output, and then back from voice input to text output. 
Our idea was brought upon as some words (or names!) have weird pronunciations or spellings that might impact how they are said by Polly or heard by Transcribe. 
Through Polly, we will be using the different voice IDs in Polly to see if the accent plays a role in the accuracy of the transcriber and explore the variable of the origin of words. We suspect that those hidden variables might have a significant impact on the accuracy of the algorithms. 

Our vision is to run a regression controlling for voice ID within Polly and then measure how much of the accuracy of the transcriber is explained by the accent, and how much explained by other unobserved factors. In this repo, we will have all of the code, documentation, and files that we used to complete or task above, so that a user reading this repo will know how to follow along and apply relevant examples that interest them. Additionally, We will map out how to create a bucket in AWS S3, and then from there how we used S3 to transform and interpret the data. Lastly, we will have an overview of the architecture like the one in the blog post.



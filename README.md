# Job Coach Question Answering

Job Coach Question Answering is an open-source AI tool designed to assist new hires in quickly accessing essential details about their jobs, including location, contact information, and available resources. Users can inquire about any job-related queries, and the model promptly generates accurate responses. By leveraging this solution, significant time can be saved at job sites for both new hires and supervisors, as redundant questions can be efficiently addressed by the model.

## Background
Getting a new job is exciting! However, navigating new job sites can be overwhelming, as new hires must familiarize themselves with various responsibilities, locations, supervisors, resources, and contact information, among other things. To assist in a smooth transition for new hires, the initial version of Job Coach Question Answering was developed during DSSG 2022. This AI-powered model enables new hires to obtain immediate answers to almost any question without the need to contact a supervisor or endure delays in response.

This year, our primary objective is to enhance the model even further. Previously, users were required to upload documents, and the model itself was hosted on AWS, requiring heavy infrastructure. Our aim is to make the model easily accessible to both developers and users by providing predefined prompts. Additionally, we acknowledge that the previous model occasionally generated hallucinated answers, plausible yet incorrect answers, and we are committed to addressing this issue with greater care. Our goal is to improve the model based on the challenges we have identified.


## Features

- Generative AI and LangChain integration to process PDFs and create quizzes and answer keys
- No programming background is required for usage
- Runs on Google Colab, with no additional installations needed

## Getting Started

This section provides a step-by-step guide to setting up and using Job Coach QA. We aim to make the setup process as straightforward as possible to make this tool accessible.

### Requirements
To use Job Coach QA, you will need:
- Internet connection
- A web browser

### Instructions

#### Step 1: Access ChatGPT Interface
Open your web browser and navigate to the following link: 
https://chat.openai.com/share/ef7e7528-81d3-4df2-a418-7912472afee3.
This will take you to the ChatGPT interface designed to assist you as a job coach. Click "Continue this conversation" at the bottom.

![step1](https://github.com/vanderbilt-data-science/job-coach-qa/assets/111295624/315a438e-49cc-45d5-a04b-a3db9ef200c6)


#### Step 2: Upload Employee Handbook
Once the ChatGPT interface loads, you will be prompted to upload your employee handbook. Locate the digital copy of your employee handbook on your device and copy and paste it into the interface. This will allow the model to summarize important information from the handbook.

![step2](https://github.com/vanderbilt-data-science/job-coach-qa/assets/111295624/8cb2a9fc-7cad-48ae-8cc0-74583c68ec71)

#### Step 3: Start a Conversation
Start a conversation with the model by asking any questions or seeking information about the job. To do this, type your question or prompt in the text box provided. For example, you can ask about the dress code policy or the office working hours. Be as specific as possible to get the most accurate response. After entering your question or prompt, press the 'Enter' key on your keyboard or click on the 'Submit' button within the interface to submit your query

![step3](https://github.com/vanderbilt-data-science/job-coach-qa/assets/111295624/0fecd18c-9cff-4efb-83e9-e74b81a7bcce)

#### Step 4: Review the Response
Review the response generated by the model. If the response does not answer your query satisfactorily, consider rephrasing your prompt to make it clearer, or try asking the question in a different way!

![step4](https://github.com/vanderbilt-data-science/job-coach-qa/assets/111295624/e033996c-85f6-4c92-b688-32cbe5431ab9)

In this case, the answer to the question was not included in the employee handbook. Let's ask another question!

#### Step 5: Continue the Conversation
Continue the conversation with the model by asking additional questions or seeking clarification as needed. Use the same process of entering prompts, submitting them, and reviewing the responses.

![step5](https://github.com/vanderbilt-data-science/job-coach-qa/assets/111295624/f89768a5-3bec-4b3c-8814-c38e7fba2dc4)

It seems like the model gives us a good answer. Yeah!!!

Here are some prompt templates you can use directly (feel free to change if you like): To be added

Remember, if you have any issues or need further clarification, you can always reach out to us. We're here to help!

## Contributing

To contribute to the project, please fork the repository and submit a pull request. Our community is supportive, and we provide training and classes if you're new to any of the frameworks used in the project. Everyone is welcome to contribute, as we believe participating in data science and AI projects is an excellent way to learn.

## Community Guidelines

We aim to create a welcoming and inclusive community where everyone can feel comfortable and valued, regardless of skill level, background, ability, or identity. To ensure a positive atmosphere, please adhere to our code of conduct and community guidelines.

## Meetings

- Sprint Planning: Mondays at 9 am
- Backlog Grooming: Wednesdays at 10 am
- Retrospective: Fridays at 9 am
- Demos: Fridays at 3 pm

## Additional Resources

- LangChain documentation
- Introduction to transformers and generative AI on our [YouTube channel](https://www.youtube.com/channel/UC8C2_3L5gR9qLmL7rmb2BdQ)
- AI Summer and AI Winter sessions (free and open to all)

## Reporting Issues

If you encounter a bug, please submit an issue and label it with "Bug." To escalate the issue, email [datascience@vanderbilt.edu](mailto:datascience@vanderbilt.edu).

## Contact Information

- Organization: Data Science Institute at Vanderbilt University
- Program: Data Science for Social Good
- Main Email: [datascience@vanderbilt.edu](mailto:datascience@vanderbilt.edu)
- Staff Lead: [staff_lead@vanderbilt.edu](mailto:staff_lead@vanderbilt.edu)

Remember to replace "Staff lead and email" with the actual name and email address of the staff lead.


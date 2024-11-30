# Human Interactions with AI-generated Code Suggestions

We developed a Flask-based web application that dynamically provides students with suggestions based on their code, test case results, and instructors' solutions using GPT-4. By engineering prompts that utilize the 
Socratic method, the application offers suggestions and guiding questions without revealing the underlying solutions. 
To evaluate the effectiveness of the application in aiding students' coding, we conducted a between-participants (n=10) factorial study, incorporating descriptive and inferential insights through ANCOVA analysis.

Please take a look at our [paper](https://drive.google.com/file/d/1rJbfZg8Q0PaftnKT80rN8SKRxHQ4uhEM/view) for more details!

# Authors

Anirudh Sundara Rajan (asundararaj2@wisc.edu) \
Karthik Suresh (ksuresh6@wisc.edu) \
Justin Kiefel (jkiefel@wisc.edu)


# AI Code Helper

In our work, we build a system that leverages the opportunities provided by AI systems for programming while eliminating some of the pitfalls. Our system provides the learner with real-time suggestions based on (1) The Programming question they are solving, 
(2) The code they have typed thus far, (3) The compilation or runtime error message (if any), (4) Logical error messages generated by running test cases (if any) and (5) The Instructors canonical solution. 
The system takes all of this information along with a system prompt that we formulate to provide suggestions that try to guide the learner toward the instructor's solution. 

Our model also incorporates Socratic Learning principles through our system prompt to enhance learning outcomes. 
This constitutes guiding learners towards the solution and not outright showing them the solution. 
Learners are, therefore, encouraged to derive the solutions on their own.

The students code in a jupyter notebook (not shown in the below image) and seek help from the AI code Helper based on their code up until that point on an interface we designed with the help of Flask, HTML, Javascript and OpenAI's API. Below is a screen a student may see if they are trying to seek help for a particular question:

<img width="1433" alt="LLM_code_helper" src="https://github.com/karths8/CS839-HCI-project/assets/47289950/d4cd11b7-fbff-4cb1-9d70-f532e70d6fe9">
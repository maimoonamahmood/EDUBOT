# EDUBOT
## Step-by-Step Guide on How to Use the EDUBOT:
### 1.	Academic Query Interaction: "You:" General input field for asking questions to the chatbot.
 ![image](https://github.com/user-attachments/assets/7cc838ff-3d6d-40ec-b604-cc2c95647ed1)

•	Captures general academic questions for the chatbot.

### 2.	Academic Performance Evaluation:
 ![image](https://github.com/user-attachments/assets/66ce1de1-f9b8-4453-899c-e9ae64ee4fd4)

"Enter the total number of exams: "

•	Number of exams the student is planning to attend overall.
 
![image](https://github.com/user-attachments/assets/9e54a383-03b3-4c54-bee8-0273f70936a7)

"Enter the number of exams attended: "

•	Exams already completed by the student.
 
![image](https://github.com/user-attachments/assets/de41f4e4-e83d-4694-8188-07aaffcf3cdb)

"Enter the number of subjects: "

•	Number of subjects the student is currently studying.
 
![image](https://github.com/user-attachments/assets/fccbc8d3-fc8c-4918-95c3-3facd1a3fb91)

"Enter the name of subject {i+1}: "

•	Prompts the user to enter the name of each subject.
    ![image](https://github.com/user-attachments/assets/a0f0a84f-ba5c-47f3-9806-e080582b50a9)
    ![image](https://github.com/user-attachments/assets/b21bbca6-b715-4a35-8f32-74fd22f072ae)

…etc up to {i+1} iterations, where :		
for i in range(num_subjects):
    subject = input(f"Enter the name of subject {i+1}: ")


"Enter marks obtained in {subject}: "

•	Accepts marks for each subject in each attended exam.
     ![image](https://github.com/user-attachments/assets/f4298371-35e7-428d-bd49-7e1f5920d356)
![image](https://github.com/user-attachments/assets/97ff93ac-5aff-40e4-9a0c-e8e434e34e0e)

For example: {subject}=python, java & Student attended 2 Exams.
![image](https://github.com/user-attachments/assets/0bed064e-f07b-41fc-a40f-89dcf4a1facf)

 
### 3.	Study Planning:
"How many hours do you study per day? "

•	Total study time available daily.

 ![image](https://github.com/user-attachments/assets/a53642fa-4d46-4077-86d4-52e69517ad64)

"Enter your target percentage: "

•	The student’s academic target (e.g., 85%).
 ![image](https://github.com/user-attachments/assets/224846f1-3e17-4c6d-a2d3-351e6153c911)

### 4.	Exam Planning:

“Enter the date of your upcoming exam (YYYY-MM-DD):”

•	Used for generating customized study suggestions based on time left.
 ![image](https://github.com/user-attachments/assets/c89a9d54-1526-48c9-86a9-38affe49784c)

### 5.	Navigation / Continuation Prompts:
"Do you have any more questions? (yes/no): "

•	User chooses to continue chatting or move to evaluation.
 ![image](https://github.com/user-attachments/assets/40904bc4-119b-46ec-9743-242569e840f4)

"Do you need help evaluating your performance? (yes/no): "

•	Checks if the user wants to enter marks for analysis.
 ![image](https://github.com/user-attachments/assets/89ed5c25-9497-42ef-a3b0-ed33e0f92da9)

"Any more queries? (yes/no): "

•	After academic evaluation, confirms further interaction.
 ![image](https://github.com/user-attachments/assets/2806c2b2-3fef-4755-b8d3-427f33a10d4f)

"Do you need guidance for future? (yes/no): "

•	Triggers the career guidance module.
 ![image](https://github.com/user-attachments/assets/1851f747-fecb-4720-8cc6-2279c5446dae)

### 6.	Career Guidance:
"Enter your country: "

•	Geographic input for region-specific career roadmap.
 ![image](https://github.com/user-attachments/assets/c3c112fe-734c-4564-95ac-15f631022518)

"What are you currently pursuing? (e.g., schooling, degree, etc.): "

•	Education status (e.g., “B.Tech in Computer Science”)
"Provide more details (e.g., subjects, field of study, standard, etc.): "
![image](https://github.com/user-attachments/assets/4c7cd099-4467-42ce-8f7c-2bf57e04fc9a)

•	Specific information about academic background.
"What are your career interests ? : "
![image](https://github.com/user-attachments/assets/66c7d34e-d3ac-4fcc-a729-08ee81f26207)

•	The user’s aspirational domain (e.g., “Defence”).
 
![image](https://github.com/user-attachments/assets/91132094-a02b-4c79-b180-898a82a1d920)



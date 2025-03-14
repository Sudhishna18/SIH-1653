# Smart India Hackathon Workshop
# Date: 13/03/2025
## Register Number: 212224040336
## Name: P.SUDHISHNA
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

The idea for the **Web-based Selector-Applicant Simulation Software** is to create an intelligent and automated interview platform that helps evaluate candidates for various roles in an objective and unbiased manner. The system would simulate a real-life boardroom experience for both experts (interviewers) and candidates, ensuring that the right talent is identified by matching candidates' expertise with relevant questions and evaluating their responses based on criteria such as relevance, depth, and clarity.

1. **Question-Expertise Matching**:
   - The software will intelligently match the type and level of questions to the candidate's expertise. Questions can range from ice-breakers to highly specialized technical or managerial questions based on the candidate’s profile and the position for which they are being interviewed.

2. **Automated Evaluation of Responses**:
   - By using Natural Language Processing (NLP) algorithms, the system will evaluate the relevance and quality of the candidate's responses. It will analyze whether the answer is relevant to the question, how deeply it addresses the topic, and its clarity and coherence.
   
3. **Real-Time Scoring and Feedback**:
   - The system will generate real-time scores for both the questions and the answers. Experts can also provide additional feedback, while the system provides a comprehensive analysis of the candidate’s performance, helping experts make informed decisions.

4. **Learning from Previous Interviews**:
   - The system will continuously improve over time by analyzing historical interview data. Machine learning models can be used to adjust the question selection and scoring models, improving the interview process based on past results and feedback.

5. **User-Friendly Interface**:
   - Both experts and candidates will have intuitive interfaces. The expert dashboard will allow interviewers to select questions, review answers, and provide feedback, while candidates will have an easy-to-navigate interface to answer questions and review their performance after the interview.

6. **Comprehensive Reporting**:
   - After each interview, the system will generate a detailed report that includes the candidate’s overall performance, strengths, weaknesses, and suggestions for improvement, along with an overall suitability score based on the candidate's knowledge and response quality.

By integrating **question-response relevance matching**, **automated scoring**, and **real-time feedback**, this system will revolutionize the recruitment and interview process, offering a fair and efficient way to assess candidates while reducing human biases.


## Proposed Solution / Architecture Diagram

![WhatsApp Image 2025-03-14 at 08 53 06_67fa9895](https://github.com/user-attachments/assets/95e6ef93-594d-4494-a071-647f63ef0d8f)

## Use Cases
![WhatsApp Image 2025-03-14 at 08 55 14_f7c2de09](https://github.com/user-attachments/assets/50bb7f6a-c744-4c36-b925-ddf354dd2a3d)



## Technology Stack

1. Frontend (User Interface)

Frameworks/Libraries:

React.js or Angular – For building responsive, dynamic, and user-friendly interfaces.

Redux – For state management, ensuring consistent data across components.

Bootstrap or Material-UI – For pre-designed UI components to enhance design efficiency.


Technologies:

HTML5 – For structuring the web content.

CSS3 – For styling and creating a modern, visually appealing interface.

JavaScript (ES6+) – For adding interactivity to the UI.
------
2. Backend (Server-Side Development)

Frameworks:

Node.js with Express.js – For handling server-side logic, API development, and routing.

Python with Flask/Django – For integrating AI/ML models and handling backend operations.


Key Functionalities:

Authentication and authorization.

Handling user roles (experts, candidates, admins).

API development for frontend-backend communication.

Real-time data processing for scoring and feedback.

3. Database

Relational Database:

PostgreSQL or MySQL – For storing structured data like user profiles, interview history, and question banks.


NoSQL Database (if scalability is required):

MongoDB – For storing dynamic data, such as real-time interview metrics.


4. Artificial Intelligence/Machine Learning

NLP Libraries:

spaCy or NLTK – For processing candidate responses and analyzing relevance.

Transformers (Hugging Face) – For advanced natural language understanding.


Machine Learning Frameworks:

Scikit-learn – For building scoring algorithms.

TensorFlow or PyTorch – For developing custom AI models to enhance evaluation processes.


5. Real-Time Communication

WebSockets (Socket.io) – For real-time data exchange between interviewers and candidates.

WebRTC – For enabling live video interviews, if required.


6. Cloud Services & Hosting

AWS / Google Cloud / Microsoft Azure – For scalable hosting, storage, and machine learning services.

S3 (AWS) – For storing large files, like interview recordings.

Lambda (AWS) – For serverless backend functions.


7. DevOps & Deployment

Docker – For containerization, ensuring consistency across environments.

Kubernetes – For orchestrating containers in production.

CI/CD Tools:

Jenkins / GitHub Actions – For continuous integration and deployment.


8. Security Measures

OAuth 2.0 / JWT – For secure user authentication and authorization.

SSL/TLS Encryption – For secure data transmission.

Role-Based Access Control (RBAC) – To ensure data privacy and control.


9. Analytics and Reporting

Power BI or Tableau – For generating visual reports and dashboards.

Custom Python Scripts – For detailed data analysis.


10. Testing Tools

Jest – For frontend unit testing.

Mocha/Chai – For backend testing.

Selenium – For automated UI testing.


## Dependencies

i)Frontend (React.js)

react, react-dom – Core libraries for UI.

react-router-dom – For routing.

axios – For API requests.

redux, react-redux – For state management.

bootstrap or @mui/material – For UI components.



ii)Backend (Node.js with Express.js)

express – Server framework.

cors, helmet – For security.

jsonwebtoken, bcryptjs – For authentication.

mongoose or pg – For database integration (MongoDB/PostgreSQL).

socket.io – For real-time communication.




iii)AI/ML (Python)

numpy, pandas – For data processing.

scikit-learn – For machine learning.

spacy, transformers – For NLP tasks.




iv)DevOps & Deployment

docker, nginx – For containerization and hosting.

aws-sdk – For integrating AWS services.




v)Testing

jest, cypress – For frontend testing.

mocha, chai – For backend testing.




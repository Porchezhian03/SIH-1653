# Smart India Hackathon Workshop
# Date: 06/03/2025
## Register Number: 212224040235
## Name: PORCHEZHIAN E
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Simulated Board Room Experience:

Virtual Reality (VR) Integration: Utilize VR to create an immersive board room environment where candidates and interviewers can interact as if they were in the same room.

Avatars for Experts: Create realistic avatars for interviewers to enhance the experience.

Structured Interview Process:

Ice-Breaking Questions: Start with AI-generated personalized ice-breaking questions to help candidates relax.

Techno-Managerial Questions: Segregate questions based on the candidate’s expertise and role (e.g., technical, managerial, hybrid).

Follow-Up Questions: Use AI to generate follow-up questions based on the candidate's responses, ensuring deeper assessment of their knowledge and skills.

Automated Scoring and Evaluation:

Relevance Scoring for Questions: AI algorithms evaluate the relevance of each question posed by interviewers based on the candidate’s expertise.

Relevance Scoring for Responses: AI evaluates the relevance of the candidate’s responses to the questions asked.

Overall Candidate Score: The system computes an overall score reflecting the candidate's subject knowledge, problem-solving abilities, and suitability for the role.

Expert Contributions:

Expert Review: Allow experts to review and rate the AI-generated questions for quality and relevance before the interview.

Human-AI Collaboration: Experts can intervene and provide additional questions or feedback during the interview process.

Question Bank Management:

Extensive Question Bank: Maintain a large, categorized repository of questions.

Continuous Learning: Use machine learning to improve the question set based on feedback and outcomes from previous interviews.

Real-Time Feedback:

Candidate Feedback: Provide immediate feedback to candidates on their performance, highlighting areas of strength and improvement.

Expert Feedback: Allow experts to receive real-time insights and analytics on candidate responses.

Interview Analytics:

Detailed Performance Reports: Generate comprehensive reports on candidate performance, including scores and feedback.

Pattern Analysis: Identify common strengths and weaknesses across candidates to refine the interviewing process.

Candidate Experience:

Feedback Loop: Offer candidates the opportunity to rate their interview experience and provide feedback.

Training and Preparation: Provide resources and simulated interviews to help candidates prepare.


## Proposed Solution / Architecture Diagram
![Screenshot 2025-03-06 205810](https://github.com/user-attachments/assets/6c9e0149-12fd-44c2-ab48-d9e079383f86)


## Use Cases
![image](https://github.com/user-attachments/assets/f09e52e6-a8ff-4ac5-8e25-08c07d8d3d0c)


## Technology Stack
Frontend:
TypeScript: To add type safety and improve code quality for React.jsor Angular.

Material-UI or Bootstrap: For pre-built UI components to speed up development.

Tailwind CSS: For utility-first CSS to make styling more efficient.

Backend:
GraphQL: For more efficient data querying and reduced over-fetching compared to REST APIs.

Redis: For caching and improving application performance.

RabbitMQ or Kafka: For handling asynchronous tasks and message brokering.

Database:
Elasticsearch: For advanced search capabilities and analytics.

Redis: For in-memory data storage to accelerate data retrieval.

AI/ML:
OpenCV: For computer vision tasks if integrating video analysis.

Jupyter Notebooks: For data exploration and model development.

Real-Time Communication:
Twilio: For adding SMS or voice communication capabilities.

TokBox (OpenTok): For enhanced video conferencing features.

Cloud Services:
AWS Lambda: For serverless functions to handle specific tasks without provisioning servers.

Azure Cognitive Services: For additional AI/ML services like speech recognition.

DevOps and Monitoring:
Prometheus: For monitoring application performance metrics.

Grafana: For visualizing metrics and creating dashboards.

Terraform: For infrastructure as code to manage and provision resources.

Version Control:
Branching Strategies (Git Flow): For managing code changes and releases.

Security:
Helmet.js: For securing Express.jsapps by setting various HTTP headers.

Rate Limiting: To protect against DDoS attacks.

Regular Security Audits: To identify and fix vulnerabilities.

Development Tools:
VS Code: As a powerful code editor with extensions to improve development efficiency.

ESLint and Prettier: For maintaining code quality and consistent formatting.

Postman: For API testing and debugging.

## Dependencies
Frontend Dependencies:
Next.js: For server-side rendering and improving SEO.

Vue.js: As an alternative to React.jsor Angular for building the user interface.

Chart.jsor D3.js: For creating interactive charts and visualizations.

Backend Dependencies:
ASP.NET Core: For a robust and scalable backend framework, especially if the team has .NET expertise.

Spring Boot: For building Java-based backends with a focus on rapid development and integration.

Firebase Functions: For serverless backend logic.

Database Dependencies:
Cassandra: For handling large-scale data and ensuring high availability.

Neo4j: For graph-based database needs, useful for complex relationships.

InfluxDB: For time-series data, useful in monitoring and logging.

AI/ML Dependencies:
Google Cloud AI: For leveraging Google's pre-trained AI models and tools.

Microsoft Azure Machine Learning: For end-to-end machine learning model development and deployment.

Amazon SageMaker: For building, training, and deploying ML models at scale.

Real-Time Communication Dependencies:
Pusher: For real-time notifications and updates.

Firebase Realtime Database: For real-time data synchronization.

Cloud Services Dependencies:
Cloudflare: For content delivery network (CDN) services and DDoS protection.

Heroku: For quick deployment and easy scaling of applications.

DevOps and Monitoring Dependencies:
Ansible: For automation of server setup and configuration management.

New Relic: For application performance monitoring and management.

Sentry: For real-time error tracking and monitoring.

Security Dependencies:
Auth0: For flexible and easy-to-integrate authentication solutions.

OWASP ZAP: For automated security testing of web applications.

Let’s Encrypt: For free SSL/TLS certificates.

Development Tools Dependencies:
Figma: For collaborative design and prototyping.

Webpack: For module bundling and build automation.

Babel: For JavaScript transpiling.

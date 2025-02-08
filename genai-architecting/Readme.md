## Purpose

To design and implement an AI-powered language-learning platform that prioritizes data privacy, cost efficiency, and scalability for 300 active students within Nagasaki. The solution will incorporate open-source models and localized infrastructure to minimize dependencies on third-party managed services.

## High-Level Business Summary (Conceptual)
The company aims to enhance its language-learning platform with a proprietary AI solution. The system will focus on enabling students to engage in study activities such as word grouping and sentence construction while addressing concerns over data privacy, cost control, and copyright compliance. By investing in dedicated hardware and leveraging open-source AI models, the company seeks to establish full ownership of the infrastructure.

## Function Requirements
### 1. AI Model Integration:

#### - Implement an open-source Large Language Model (LLM) for sentence construction and study activities.
#### - Ensure the model is capable of operating on locally hosted hardware.

### 2.Hardware and Infrastructure:

#### - Procure and set up an AI PC/server with a budget of $10,000–$15,000.
#### - Configure the system to serve 300 students effectively, considering the citywide location of users in Nagasaki.

## 3.Data Management:

#### - Build and maintain a database with 2,000 words and associated learning materials.
#### - Ensure all materials are sourced legally to avoid copyright violations.

### 4.Guardrails:

#### - Implement input/output validation to maintain the accuracy and relevance of AI-generated responses.
#### - Develop mechanisms to track and manage student activities for personalized learning.

### 5.Connectivity:

#### - Provide stable internet connectivity to ensure seamless interaction between the local server and students.

## Assumptions
### 1.The selected open-source LLMs (e.g., IBM Granite) will perform adequately within the constraints of the proposed hardware.
### 2.A single AI PC/server setup in the company’s office will provide sufficient computational power and bandwidth to handle requests from 300 students.
### 3.All copyrighted learning materials will be purchased and stored securely in the company’s database.

## Requirements

### 1.Business Requirements:

#### - Protect student data by maintaining full ownership of the AI infrastructure.
#### - Minimize operational costs by avoiding third-party managed services.

### 2.Functional Requirements:

#### -Support interactive language-learning activities, including sentence construction and vocabulary sessions.
#### -Provide real-time feedback to students through an AI-driven interface.

### 3.Technical Requirements:

#### -Hardware with specifications to support AI model inference at scale (e.g., high-end GPUs, sufficient RAM, and storage).
#### -An internet connection with enough bandwidth for smooth operations.

### 4.Compliance Requirements:

#### -Use traceable and legally compliant training data to mitigate risks associated with copyright infringement.


## Constraints
### Budget:
#### -The hardware investment is limited to $10,000–$15,000.

### Scalability:
#### -The initial infrastructure must cater to 300 students, with limited scalability for future growth.

### Legal and Ethical Concerns:
#### -Only open-source LLMs with clear training data origins (e.g., IBM Granite) are permissible.
#### -All materials used for training and database storage must be legally acquired.

### Infrastructure:
#### -The solution will rely on a single on-premises server, restricting redundancy and fault tolerance.

## Data Strategy
### Develop a centralized database containing all learning materials and AI-related metadata.
### Securely store copyrighted content, ensuring compliance with licensing agreements.
### Periodically review and update the database to include new, legally sourced materials.
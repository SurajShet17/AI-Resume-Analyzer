
# ARTIFICIAL INTELLIGENCE ENHANCED RESUME ANALYZER

## Objective:
The AI Resume Analyzer project is a web-based application developed using Streamlit, a Python library for creating interactive web applications with minimal code. The project is designed to assist users in analyzing their resumes and providing intelligent recommendations for skills and courses based on the content of their resumes. Additionally, the project includes an admin section for system administrators to view and analyze user data stored in a MySQL database.

## Key Features:

#### Resume Parsing:
Users can upload their resumes in PDF format.
The project utilizes the pyresparser library to extract information from the resumes, including name, email, contact details, and skills.

#### Resume Analysis and Recommendations:
Basic information from the parsed resume is displayed, such as the user's name, email, and contact details.
The system categorizes users into experience levels (Fresher, Intermediate, Experienced) based on the number of pages in the resume.
Skills identified from the resume are displayed, and additional skills and related courses are recommended based on the identified skills.

#### Resume Writing Score:
The system evaluates the resume based on the presence of specific sections (Objective, Declaration, Hobbies, Achievements, Projects).
Users receive a resume writing score, and recommendations are provided to improve the resume.

#### Bonus Videos:
Users are presented with randomly selected bonus videos on resume writing tips and interview preparation.

#### Admin Section:
The admin section requires authentication and allows system administrators to view user data stored in a MySQL database.
Admins can visualize data through pie charts representing predicted fields and user experience levels.

#### Database Interaction:
The project uses a MySQL database to store user data, including details extracted from resumes and system-generated recommendations.
SQL queries are employed to create the database, tables, and retrieve data for admin visualization.

#### Deployment:
The project is intended for deployment on AWS (Amazon Web Services) using an EC2 instance.


## Project Flow:

#### User Uploads Resume:
Users upload their resumes through the web interface.
Resume Parsing and Analysis:

The uploaded resumes are parsed using the pyresparser library.
Basic information, skills, and experience level are extracted and displayed.

#### Recommendations:
Based on the identified skills, the system recommends additional skills and related courses in specific domains (Data Science, Web Development, Android/iOS App Development, UI/UX).

#### Resume Writing Tips:
The system provides users with a resume writing score and tips for improving their resumes.

#### Admin Section:
System administrators can log in to the admin section, view user data, and visualize trends through pie charts.

#### Database Storage:
User data, including resume details, recommendations, and scores, is stored in a MySQL database.
Technologies Used:
Streamlit: For building the web application.
pandas: For data manipulation and analysis.
MySQL: For database storage.
pyresparser: For parsing resume PDFs and extracting information.
pafy: For fetching video titles from YouTube links.
plotly: For creating interactive data visualizations.

This project provides a comprehensive solution for users to enhance their resumes and improve their chances in the job market by incorporating relevant skills and courses based on the content of their resumes. The admin section offers insights into user trends and system performance.


## Requirements

- Python 3.x
- All libraries contained in requirements.txt file

## Installation

1. Clone this repository to your local machine.
2. Install all the required Python packages (present in requirements.txt file) by running the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository.
2. Authenticate your MySQL username, password and database name in this part of the code.
`connection = pymysql.connect(host='localhost',user='root',password='******',db='**')`

2. After installing all the dependencies in requirements.txt file,
run App (1).py file to launch the instance on local host.

```bash
python run App (1).py
```
3. Make sure to change the content and location our your choice.


## Contact

For any issues or questions, please contact surajshet5555@gmail.com.

---

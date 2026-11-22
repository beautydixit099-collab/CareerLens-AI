# CareerLens AI -- Job Market & Skill Gap Analyzer

CareerLens AI is a web-based career guidance application designed to
help students and job seekers understand industry requirements, identify
skill gaps, explore suitable job roles, and create personalized learning
roadmaps.

The application analyzes job descriptions, compares required skills with
a user's existing skills, calculates skill-match percentages, and tracks
progress towards career readiness.

## 🎯 Objectives

-   Extract required and preferred skills from job descriptions.
-   Compare existing skills with industry requirements.
-   Identify missing and additional skills.
-   Generate prioritized learning roadmaps.
-   Recommend suitable entry-level job roles.
-   Track learning goals and job readiness.
-   Provide secure user authentication and persistent data storage.

## ✨ Key Features

### 1. User Authentication

-   User registration and login.
-   Individual user profiles.
-   Database-backed user information.

### 2. Dashboard

-   Skill-match percentage.
-   Visual skill comparison charts.
-   Recommended career roles.
-   Skills categorized by type.

### 3. Job Market Explorer

-   Explore available entry-level job roles.
-   Understand skills required for different careers.

### 4. Job Description Analyzer

-   Paste job descriptions or upload TXT, PDF, and DOCX files.
-   Extract required and preferred skills.
-   Identify experience levels.
-   Categorize extracted skills.

### 5. Skill Gap Analyzer

-   **Matching skills:** Skills the user already possesses.
-   **Missing skills:** Skills required but not yet acquired.
-   **Additional skills:** Skills beyond job requirements.
-   Calculate skill-match percentage.

### 6. Personalized Learning Roadmap

-   Identify missing skills.
-   Prioritize skills based on demand, level, and prerequisites.
-   Organize learning into Beginner, Intermediate, and Job-Ready levels.
-   Provide learning resources.
-   Add roadmap skills to learning goals.

### 7. Career Recommendations

-   Recommend suitable entry-level job roles based on existing skills.
-   Display role-match comparisons.

### 8. Student Progress Tracker

-   Track completed and remaining skills.
-   Update learning goal status.
-   Add learning notes and activities.
-   Calculate job readiness and overall learning progress.

## 🛠️ Technology Stack

  Technology   Purpose
  ------------ --------------------------------------------
  Python       Core application logic and processing
  Streamlit    Interactive web application interface
  MySQL        Relational database and persistent storage
  SQL          Database queries and operations

## 🏗️ System Architecture

The application follows this workflow:

1.  **User Interface:** Streamlit pages, forms, and charts.
2.  **Application Logic:** Python sessions, routing, and validation.
3.  **Processing & Analysis:** Skill extraction, skill-gap analysis, and
    roadmap rules.
4.  **Database:** MySQL stores users, roles, skills, resources, and
    learning goals.
5.  **Results & Visualization:** Displays percentages, charts,
    recommendations, and roadmaps.

## 🔄 Application Workflow

1.  User Registration and Login
2.  Profile Creation and Existing Skills
3.  Job Description Analysis
4.  Skill Extraction
5.  Skill Gap Analysis
6.  Personalized Learning Roadmap
7.  Career Recommendations
8.  Progress Tracking

## 📊 Implementation & Testing

CareerLens AI has been implemented as a working prototype.

-   16 out of 16 functional test cases passed.
-   MySQL database connectivity established.
-   Data persistence after application restart verified.
-   16 job roles seeded.
-   39 learning resources seeded.

## 🚀 Installation and Setup

### Prerequisites

-   Python installed on your system.
-   MySQL Server.
-   pip package manager.
-   Git.

### Step 1: Clone the Repository

``` bash
git clone <your-repository-url>
```

### Step 2: Open the Project Folder

``` bash
cd CareerLens-AI
```

### Step 3: Install Dependencies

If a `requirements.txt` file is available:

``` bash
pip install -r requirements.txt
```

### Step 4: Configure MySQL

-   Start your MySQL server.
-   Create the required database.
-   Configure database connection credentials in the application.
-   Run the project's database initialization scripts, if provided.

### Step 5: Run the Application

``` bash
streamlit run app.py
```

Replace `app.py` with the actual Streamlit entry-point filename if it is
different.

## 🔮 Future Scope

The following features are planned for future development:

-   Live job-market API integration.
-   Advanced NLP for job-description analysis.
-   Machine-learning-based recommendations.
-   Career guidance chatbot.
-   Resume analysis.
-   Advanced job-readiness assessment.

## ⚠️ Important Note

The current learning roadmap uses transparent rule-based logic rather
than an AI/ML prediction model. Advanced AI/ML recommendations are part
of the proposed future development.

## 🎓 Project Information

-   **Project Name:** CareerLens AI -- Job Market & Skill Gap Analyzer
-   **Project Type:** Data Science Innovative Project
-   **Department:** Computer Science & Engineering
-   **University:** Shri Ramswaroop Memorial University (SRMU)
-   **Presented By:** Prachi Gupta and Team

## ❤️ Acknowledgement

We sincerely thank our faculty members and Shri Ramswaroop Memorial
University for their guidance and support throughout the development of
this project.

------------------------------------------------------------------------

**CareerLens AI -- Analyze Skills. Identify Gaps. Build Your Career.**

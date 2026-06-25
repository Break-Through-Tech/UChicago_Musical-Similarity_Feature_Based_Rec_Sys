---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---

## 📋 BTT Internal Evaluation Notes

| Check                     | Status | Notes                                                                                                    |
|---------------------------|--------|----------------------------------------------------------------------------------------------------------|
| Python Compatibility       | 🟢  | The tech stack is heavily centered around Python and widely adopted Python libraries for machine learning and data analysis (e.g., scikit-learn, NetworkX). |
| Data Readiness             | 🟢  | Data is under 1GB and in a user-friendly format (CSV/TSV), allowing students to jump directly into analysis without extensive cleaning. |
| Resource Check             | 🟢  | All required tools are accessible on the Google Colab free tier, minimizing barriers to access for students. |

**Student Fit Score:** 7/10  
**Technical Depth Score:** 8/10  
**Overall Recommendation:** REVISE

**Advisor Feedback Draft:**
Strength: The project encompasses a rich data source and allows students to explore both machine learning and interpretability in a music context. Actionable Adjustments: 1) Ensure that students are well-equipped to understand the metrics for evaluation—clarity on precision and clustering metrics is critical. 2) Provide deeper theoretical insights into graph analysis—consider a preparatory module or resource for students. Call to Action: Please ensure the project documentation clearly outlines relevant resources and project milestones for student success.


---

# Understanding Musical Similarity: Building a Feature-Based Recommendation System with Graph-Based Interpretability

**Company / Org:** University of Chicago  
**Challenge Advisor:** Nathan Rickert, naterick12@gmail.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About the University of Chicago

The University of Chicago is a prestigious institution known for its rigorous academic programs and innovative research. We focus on interdisciplinary collaborations, particularly in fields like data science, music information retrieval, and AI applications.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use audio feature data from 12M Spotify songs (e.g., danceability, energy, tempo, valence, acousticness, etc.) and machine learning techniques such as feature engineering, K-Nearest Neighbors, logistic regression, decision trees, clustering, and model evaluation methods to build and evaluate a music similarity and recommendation system that predicts and ranks similar songs based on audio characteristics. This will help a music streaming company (like Spotify) address the challenge of improving music discovery and understanding how song characteristics influence perceived similarity in recommendation systems.

### Success Criteria
Recommendation quality: Precision@K (e.g., K=5 or 10), Genre consistency, Artist diversity. Model performance: Comparison across KNN vs LR vs tree-based models, Feature importance interpretability. Structural insight: Whether graph structure improves interpretability of recommendations and whether clusters align with known musical groupings.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month       | Milestone                     | Key Activities                                                       |
|-------------|-------------------------------|---------------------------------------------------------------------|
| **September** | Data Understanding              | Explore dataset, handle missing values, document findings             |
| **October**   | Model Development             | Train baseline model, experiment with approaches, iterate           |
| **November**  | Evaluation & Presentation     | Finalize model, prepare presentation, document results              |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** Audio feature data from Spotify  
**Format:** CSV/TSV  
**Size:** under 1gb  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- Audio feature data from 12M Spotify songs including danceability, energy, tempo, valence, acousticness, etc. The dataset contains numerical/quantitative, categorical, text, and time series data in CSV/TSV format.
- [Any known limitations or preprocessing needed]
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification  

**Recommended Libraries:**
- Feature engineering
- K-Nearest Neighbors
- Logistic regression
- Decision trees
- Clustering (KMeans, DBSCAN)
- Model evaluation
- NetworkX (graph-based data analysis)
- PCA
- UMAP
- Google Colab.

**Evaluation Metrics:**
- Precision/Recall, F1 Score

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Link to an article or blog post about the problem domain]
- [Link to an industry report or case study]

**Technical Tutorials:**
- [Link to a free tutorial on the ML technique(s) involved]
- [Link to documentation for a key library or tool]

**Code Examples:**
- [Link to a relevant GitHub repo]
- [Link to a sample implementation or starter code]

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).

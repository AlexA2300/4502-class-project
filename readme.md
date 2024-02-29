# Part 1: Outline

- **Title:** Career Navigation with LinkedIn Job Posting Insights

- **Team Members:** Alex Archer

- **Description:**
    My project aims to help you navigate your chosen career path by uncovering valuable insights from the LinkedIn job market. By discovering industry hotspots, popular job titles by industry, and trending skills I intend to help you plan for success.

- **Questions to Answer:**
    - In what regions are jobs in specific industries booming?
    - What are the most popular jobs within that industry by region?
    - Which skills are in high demand within that industry?

- **Prior Work:**
    - Salience and Market-aware Skill Extraction for Job Targeting: https://core.ac.uk/works/86159256

- **Data Set:**
    - **Title:** “1.3 M Linkedin Jobs & Skills (2024)”
    - **URL:** https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024?select=linkedin_job_postings.csv
    - **Status:** Downloaded locally on my machine

- **Proposed Work:**

    - Data Cleaning:
        - Remove job listings with incomplete information or haven’t successfully extracted summaries or skills.
        - Validate a sample of job postings to manually ensure the integrity of the data, disregarding inaccurate entries.

    - Data Processing:
        - Extract and categorize job titles into broad industry categories and create a ‘industry’ column.
        - Link job postings to their corresponding skills lists

    - Analysis:
        - Utilize time-series analysis to visualize 2024 job market trends
        - Apply clustering techniques (potentialy k-means) to group group similar job titles and skills within industries to identify skill demand patterns

- **Tools:**
    - Python
    - Numpy
    - Pandas
    - Matplotlib
    - Seaborn

- **Evaluation:**
    - Comparison to other job market analysis tools.
    - Success will be measured by the clarity, accuracy, and utility of the discovered insights such as accurately identifying skilly demand by industry.

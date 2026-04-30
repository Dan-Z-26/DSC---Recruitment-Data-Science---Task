# DSC - Recruitment Data Science Task

###  Project Overview
This project involves collecting and cleaning an Instagram dataset to identify high-performing micro-influencers. The goal was to process raw data, perform exploratory data analysis (EDA), and rank influencers using a custom scoring logic to find the top 5 candidates.

### 🎥 Video Demonstration
Check out the video :
[Watch the Project Video on Google Drive] :  https://drive.google.com/file/d/103bLSoB1lfk0eLJZF6xnLscNiE4vQkf0/view?usp=sharing

---

###  Technical Stack
* **Environment:** Google Colab
* **Language:** Python
* **Libraries:** * **Pandas & Numpy:** Data manipulation and cleaning
* **Matplotlib & Seaborn:** Data visualization and insights

###  Key Insights & Data Processing
* **Data Cleaning:** Successfully handled missing values and removed duplicate entries to ensure dataset integrity.
* **Exploratory Analysis:** Generated visualizations to understand distribution patterns across the influencer base.
* **Ranking Logic:** Developed a weighted scoring system to objectively rank influencers.

###  Scoring Formula
To determine the final rankings, I used the following weighted formula:

$$\text{Final Score} = (\text{Activity Score} \times 0.5) + (\text{Reach Score} \times 0.3) + (\text{Consistency Score} \times 0.2)$$

---

### 🚀 How to Run the Code
To reproduce the analysis and view the results in Google Colab:

1. Open the `DSC_Task.ipynb` file in **Google Colab**.
2. Click on the **Files** icon (folder icon) in the left-hand sidebar.
3. Upload the dataset file: `final_influencer_hunt_dirty.csv`.
4. Run the cells in order (or go to **Runtime > Run all**).

> **Note:** Please do not rename the dataset file. The script is configured to load `final_influencer_hunt_dirty.csv` specifically to ensure the cleaning and scoring logic execute correctly.

---
### Results
The top 5 micro-influencers were identified 

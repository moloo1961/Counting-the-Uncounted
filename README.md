# 📊 Counting the ~~Uncounted~~

### A GBV Visibility Index Across Kenya's 44 Counties (2021–2022)

---

## 🌍 Overview

Counting the Uncounted is a python capstone project that measures the gap between:
  - women's lived experiences of GBV
  - and what official systems actually capture

Using:
- KDHS 2022 county-level violence data
- NCRC 2021 crime reporting data

the project calculates a **GBV Visibility Score**
for 44 counties in Kenya.

A higher score means:
> more violence is happening than official systems are seeing.

---

## 🚨 Why This Matters

Every year in Kenya, thousands of women experience violence
without ever entering official statistics.

This creates:
- invisible victims
- distorted policy decisions
- underfunded interventions
- misleading crime reporting systems

This project attempts to quantify that invisibility.

---

## 📌 Key Features

- Interactive Streamlit dashboard
- County-level GBV visibility ranking
- Data filtering and search
- County spotlight analysis
- Comparative visualization
- Policy-oriented data storytelling

---

## 🛠 Tech Stack

- Python
- requests
- Streamlit
- Matplotlib
- JSON
- Openyxl

---

## Who Needs This

- A program officer at an NGO deciding where to open a safe house.  
- A county gender desk officer making the case for more resources.  
- A donor allocating funding across regions.  

    - All of them are currently working with incomplete information.  
    - This project is a step toward closing that gap.

▶️ Running the Project Locally
1. Clone the Repository

git clone https://github.com/moloo1961/Counting-the-Uncounted.git
cd Counting-the-Uncounted

2. Create Virtual Environment
python -m venv venv 

Activate:
a.
venv\Scripts\activate 

b.
source venv/bin/activate

3. Install Requirements
pip install -r requirements.txt

4. Run Streamlit App
streamlit run app.py

## 📂 Project Structure
bash
Counting-the-Uncounted/
├── Data/
│   ├── GBV-Kenya-Analysis/
│   │   └── GBV-Kenya-Analysis.ipynb
│   └── Outputs/
│       └── visibility_scores.json
├── notebooks/
├── assets/
├── counting_the_uncounted.py
├── requirements.txt
└── README.md


🎯 Future Improvements

County heatmaps
Time-series comparisons
Survivor reporting pathways
Integration with census indicators
Machine learning risk clustering


🤝 Contributing

Contributions, ideas, and collaborations are welcome.

If you'd like to improve the project:

Fork the repository
Create a feature branch
Commit changes
Open a pull request


👩🏾‍💻 Author

Madlene Achieng Oloo

Development Studies • Gender Data • Information Management • Data Storytelling

GitHub: https://github.com/moloo1961
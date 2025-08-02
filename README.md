# Improved Source of Drinking Water 💧
**Capstone Project | IBM Cloud + AI Kosh | Sri Venkateswara College of Engineering (CSE)**  
**Author:** Vishal.K.R

---

## 📌 Problem Statement

Access to safe and improved sources of drinking water remains a major challenge in India, particularly in rural and underdeveloped areas. Despite progress under the Sustainable Development Goals (SDGs), disparities in accessibility persist across states and socio-economic groups.

This project leverages data from the 78th Round of the Multiple Indicator Survey (MIS) to analyze access to improved drinking water and related factors such as clean cooking fuel usage and migration patterns. The goal is to uncover actionable insights that support data-driven policy interventions and equitable access to clean water.

---

## ✅ Proposed Solution

We designed an **AI-powered analytics platform** to analyze water accessibility trends across India using MIS data. The platform provides interactive dashboards and predictive analytics to assist in strategic decision-making.

### Key Components:
- **Data Integration:**  
  - MIS dataset from AI Kosh  
  - Supplementary data: cooking fuel usage, migration trends

- **Preprocessing & Feature Engineering:**  
  - Handling missing/inconsistent data  
  - Composite indicators for water access, sanitation, and socio-economic dimensions  
  - Temporal and geographic clustering features

- **Machine Learning Techniques:**  
  - Classification models (Random Forest, Gradient Boosting)  
  - Clustering algorithms (K-Means, DBSCAN)  
  - Correlation analysis between water access and other indicators

- **Deployment on IBM Cloud:**  
  - IBM Watson Studio (model training & notebook execution)  
  - IBM Cloud Object Storage (data storage)  
  - IBM Cloud Functions (serverless analytics)  
  - IBM Cognos Analytics (interactive dashboards)

---

## ⚙️ System Requirements

- IBM Cloud Lite Account  
- Internet access for cloud integration

### Services Used:
- IBM Watson Studio  
- IBM Cloud Object Storage (COS)  
- IBM Cloud Functions

### Libraries:
- `pandas`, `numpy` – Data processing & numerical computations  
- `matplotlib`, `seaborn` – Data visualization  
- `scikit-learn` – ML models & clustering  
- `ibm-watsonx-ai`, `ibm_boto3` – Foundation model integration & cloud storage access

---

## 🧠 Algorithm & Deployment

### Algorithm Summary:
- **GroupBy Aggregation:** Proportion calculations
- **Chi-Square Analysis:** Statistical relationships (e.g., migration vs water access)
- **K-Means Clustering:** Grouping similar regions by access levels (optional)

### Data Input:
- Fields from MIS dataset:  
  - Drinking water source, cooking fuel type, migration details  
  - State, region, income class

### ML Pipeline:
1. Preprocess & clean dataset  
2. Encode categorical data  
3. Normalize using Min-Max scaling  
4. Apply clustering (Elbow Method, Silhouette Score for validation)  
5. Generate predictive insights & visualization

### Deployment:
- All notebooks hosted on IBM Watson Studio  
- Results made accessible via a Flask web app or IBM Cloud Functions  
- Artifacts stored in IBM Cloud Object Storage

---

## 📊 Results

- Dataset used: `nss_items_data.csv`  
- AutoAI selected **Pipeline 4** for best regression results  
- Deployed under the title **"Drinking Water"**  
- Generated predictions and visualization of water access across regions  
- Provided data-driven policy insights via an interactive dashboard

---

## ✅ Conclusion

### Key Findings:
- Detected significant **state-wise disparities** in drinking water access  
- Established **correlations** between clean cooking fuel usage and migration  
- Identified **vulnerable groups** (rural and low-income households) with poor access

### Challenges:
- Incomplete and inconsistent entries in MIS dataset  
- Complex categorical encoding  
- Lack of ground-truth labels for supervised evaluation

### Implementation Success:
- IBM Cloud services ensured smooth development and deployment  
- Open-source tools and APIs enabled efficient data analysis and insight generation

---

## 🚀 Future Scope

- **Expand Data Sources:**  
  Integrate real-time environmental and socioeconomic datasets

- **Pipeline Optimization:**  
  Use Spark or IBM Cloud Pak for Data for scalable processing

- **Advanced Algorithms:**  
  Use ensemble classifiers or transformer-based models for better prediction

- **Regional Scaling:**  
  Extend platform to support multi-state comparison and planning

- **Emerging Technologies:**  
  Explore Edge Computing and Watsonx.ai multimodal models for rural deployment and richer insights

---

## 📚 References

- **AI Kosh Dataset:**  
  [Improved Source of Drinking Water – MIS (78th Round)](https://aikosh.indiaai.gov.in/web/datasets/details/improved_source_of_drinking_water_multiple_indicator_survey_78th_round.html)

- **IBM Cloud Services:**  
  [IBM Cloud](https://cloud.ibm.com) | [IBM Watson Studio](https://dataplatform.cloud.ibm.com)

- **Watsonx.ai Documentation:**  
  [IBM Watsonx SDK Docs](https://ibm.github.io/watsonx-ai)

- **Python Libraries:**  
  [PyPI – pandas, seaborn, scikit-learn, matplotlib, etc.](https://pypi.org)

- **UN SDG 6 (Clean Water & Sanitation):**  
  [UN Goals Portal](https://sdgs.un.org/goals/goal6)

---

## 🏁 License

This project is for academic and research purposes only and follows standard open-source practices.

---

## 🙏 Acknowledgements

- IBM SkillsBuild & Cloud Team  
- AI Kosh and National Sample Survey (NSSO)

---

## 📬 Contact

**Vishal K. R**  
Email: [vshldare@gmail.com](mailto:vshldare@gmail.com)  
GitHub: [github.com/VishalKR-12](https://github.com/VishalKR-12)  
LinkedIn: [linkedin.com/in/vishal-k-r-b762a0371](https://www.linkedin.com/in/vishal-k-r-b762a0371)



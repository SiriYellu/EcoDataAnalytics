# EcoDataAnalytics
Data-driven analysis of long-term climate change effects on bird migration patterns using eBird, NOAA, and MODIS datasets. Includes data integration, spatial and temporal analytics, correlation studies, and predictive modeling with Random Forest and Gradient Boosting in Python.

### Analysis of Climate Change Effects on Bird Migration Patterns Using Long-Term Data  

📍 **Project Website:** [https://sites.google.com/view/ecodataanalytics/home](https://sites.google.com/view/ecodataanalytics/home)  
📥 **Download Full Report:** [Project_Final_Report.docx](https://drive.google.com/file/d/15s0qAczXw3zSQ8saIHcaH0g5JaHDCrQZ/view?usp=sharing)  
📦 **Project Files:** [EcoDataAnalytics.zip](https://github.com/SiriYellu/EcoDataAnalytics/blob/main/EcoDataAnalytics.zip)  

---

## 🌍 Project Overview  
**EcoDataAnalytics** explores the long-term impact of **climate change on bird migration patterns** using data from **eBird**, **NOAA**, and **MODIS**.  
The project integrates multi-source datasets to analyze how temperature, precipitation, and wind speed affect migration timing, spatial routes, and habitat loss.  

This end-to-end data analytics pipeline demonstrates how **machine learning and environmental data** can drive insights for **ecological conservation and climate policy**.

---

##  Executive Summary  
Migratory birds rely on environmental cues like temperature and habitat availability. Shifts in climate disrupt these patterns, affecting biodiversity.  
Our team conducted **temporal, spatial, and predictive modeling** to understand these effects.

- **Milestone 1:** Data Collection & Integration  
- **Milestone 2:** Analytical Modeling & Visualization  
- **Milestone 3:** Predictive Modeling & Dashboard Design  

**Key Highlights:**  
- Processed **decades of real-world data** from eBird, NOAA, and MODIS.  
- Built statistical models using **Linear Regression and Pearson Correlation**.  
- Developed ML models (**Random Forest & Gradient Boosting**) for future migration prediction.  
- Created an **interactive dashboard** for migration trends and climate correlations.

---

## ⚙️ Technical Stack
| Category | Tools & Technologies |
|-----------|----------------------|
| **Programming** | Python (Pandas, NumPy, Scikit-learn, Matplotlib, Plotly, Folium) |
| **Data Sources** | eBird (Bird Sightings), NOAA (Climate Data), MODIS (Land Cover) |
| **Databases** | CSV/Excel, MySQL |
| **Visualization** | Tableau, Plotly Dash |
| **Modeling** | Random Forest, Gradient Boosting, Linear Regression |
| **Collaboration** | Google Drive, GitHub, Google Colab, WhatsApp, Zoom |

---

## 🧩 Project Milestones  

### **Milestone 1: Data Collection and Integration**
- Acquired data from **eBird**, **NOAA GHCN**, and **MODIS**.  
- Cleaned and standardized datasets; removed duplicates and handled missing values.  
- Merged datasets on **date and geographic coordinates** to align temporal and spatial data.  

📸 *Image 1: Data Integration Pipeline*  
<img width="999" height="145" alt="image" src="https://github.com/user-attachments/assets/35f53b66-e2e4-4874-9979-4a3ea224d52e" />
<img width="986" height="237" alt="image" src="https://github.com/user-attachments/assets/8d11be69-419f-4073-84bf-0fd0c486bf67" />
<img width="1014" height="171" alt="image" src="https://github.com/user-attachments/assets/bb3d99a0-140f-437a-a081-9b5b704fc361" />
<img width="1004" height="184" alt="image" src="https://github.com/user-attachments/assets/86138796-eec5-4aec-8e72-e3af9401d69f" />

---

### **Milestone 2: Analytical Modeling**
- Conducted **temporal trend analysis** (Day-of-Year migration timing).  
- Applied **Pearson correlation** between migration timing and climate variables.  
- Visualized results using **heatmaps, scatter plots, violin plots, and histograms**.  
- Discovered moderate correlation between **wind speed** and migration timing (r = -0.21).  

📸 *Temporal Trend Visualization (Migration Timing Over Time)*  
<img width="792" height="372" alt="image" src="https://github.com/user-attachments/assets/3c50eaf2-eec5-4f9a-897d-3bae489c6d71" />
<img width="792" height="373" alt="image" src="https://github.com/user-attachments/assets/88e3422e-79d8-4dcf-8549-e0ed43a03f71" />


📸 * Correlation Heatmap – Climate Variables vs Migration DOY*  
<img width="838" height="543" alt="image" src="https://github.com/user-attachments/assets/d5e68035-1991-4ddf-aa73-0d53242c1335" />

---

### **Milestone 3: Predictive Modeling and Visualization**
- Trained **Random Forest** and **Gradient Boosting** models to predict arrival timing (DOY).  
- Features: Temperature (TMAX, TMIN), Precipitation, Wind Speed, Humidity, Year.  
- **Model Performance:**  
  - Random Forest → MSE = 189.29, MAE = 7.88  
  - Gradient Boosting → MSE = 195.04, MAE = 8.2  
- Developed **interactive dashboards** using Plotly and Folium.  

📸 * Model Performance – Actual vs Predicted DOY* 
<img width="897" height="440" alt="image" src="https://github.com/user-attachments/assets/c3c30df1-98ce-477b-ba21-88499d249b11" />
<img width="902" height="417" alt="image" src="https://github.com/user-attachments/assets/0e93b354-44b5-42d1-8c13-7b21deea55c8" />


📸 * Feature Importance * 
<img width="894" height="418" alt="image" src="https://github.com/user-attachments/assets/ad37d322-c182-49a4-8145-889aee0e2ae0" />
<img width="867" height="432" alt="image" src="https://github.com/user-attachments/assets/22ae4e7a-9c12-44a1-a6fb-25d577faa41d" />


---

## 🌎 Spatial Analysis & Visualization  
- Implemented **DBSCAN clustering** to detect bird migration hotspots.  
- Visualized **habitat degradation zones** using color-coded Folium maps.  
- Identified dense migration hubs in **eastern and western U.S.** regions.  

📸 * Spatial Distribution of Bird Sightings &  Habitat Loss & Migration Hotspot Map*  
<img width="760" height="538" alt="image" src="https://github.com/user-attachments/assets/2d619abb-8f69-448a-8560-063eb6d990cf" />

---

## 📊 Key Findings
- **Temperature** was the most influential factor in migration shifts.  
- **Green Kingfisher** species arrived earlier each year, while **Black-and-White Warbler** delayed migration.  
- **Wind speed** had consistent moderate correlation with migration timing.  
- **Random Forest** model achieved the best interpretability and performance.  


---

## 🧭 Project Planning & Management
- Followed **Agile-inspired sprints** with milestones and weekly check-ins.  
- Used **Gantt charts** to track progress and ensure deliverables.  
- Regular team meetings via **Zoom & WhatsApp** for coordination.  
- GitHub for version control; Google Drive for documentation.  

---



## 📈 Results Summary
| Metric | Random Forest | Gradient Boosting |
|--------|----------------|-------------------|
| MSE | 189.29 | 195.04 |
| MAE | 7.88 | 8.20 |
| R² | 0.005 | 0.004 |
| Top Feature | Temperature (TMAX) | Temperature (TMIN) |



---

## 🧾 Appendix  
- [Project Website](https://sites.google.com/view/ecodataanalytics/home)  
- [Download Full Report](https://drive.google.com/file/d/15s0qAczXw3zSQ8saIHcaH0g5JaHDCrQZ/view?usp=sharing)  
- [Project Files (EcoDataAnalytics.zip)](https://github.com/SiriYellu/EcoDataAnalytics/blob/main/EcoDataAnalytics.zip)  

---

## 💡 Conclusion  
The **EcoDataAnalytics** project demonstrates how data science can contribute to **sustainability and biodiversity research**.  
By combining statistical, spatial, and predictive models, we offer actionable insights for conservation planning and policy-making.  
This work underscores the importance of integrating **climate data, machine learning, and visualization** to understand ecological patterns in a changing world.  

📸 *Final Dashboard Snapshot – Bird Migration Patterns & Climate Trends*  
<img width="762" height="582" alt="image" src="https://github.com/user-attachments/assets/ea6f5d22-43e9-4593-b371-331be58c652d" />

---

## 💬 Acknowledgments  
Special thanks to **Kennesaw State University (CCSE)** for guidance and resources, and to **NOAA, eBird, and MODIS** for providing open-access datasets that made this analysis possible.

## 👥 Our Team  

### 🧑‍💻 **Siri Yellu**  
🎓 *M.S. Computer Science (Data Science Concentration), Kennesaw State University*  
🔗 [LinkedIn](https://www.linkedin.com/in/siri-reddy-yellu/) | [GitHub](https://github.com/SiriYellu)  
![profile_siri](https://github.com/user-attachments/assets/48fd3f0f-98aa-42a4-9f18-728deed28772)


Hi, I’m **Siri Yellu** — a curious mind who loves turning raw data into meaningful stories.  
I’m passionate about using **AI, analytics, and machine learning** to uncover insights that make a real-world impact, from **climate change research** to **finance, healthcare, and beyond**.

---

### 👨‍💻 **Saketh Tatipally**  
🎓 *M.S. Information Technology (AI & Data Analytics Concentration), Kennesaw State University*  
🔗 [LinkedIn](https://www.linkedin.com/in/Tsaketh) | [GitHub](https://github.com/Saketh-Tatipally)  
![WhatsApp Image 2025-10-07 at 15 49 05_263b4841](https://github.com/user-attachments/assets/6db95cdf-0018-4cb8-b6e6-6e6d303702be)



Hi, I’m **Saketh Tatipally** — a passionate **Software Engineer and AI enthusiast** who loves turning ideas into intelligent, data-driven products.  
I thrive on solving real-world problems through **clean code, smart analytics, and automation**.  

I’m currently exploring **full-time opportunities** where I can grow, build, and make an impact.

---

### 👨‍💻 **Gnana Prakash Reddy**  
🎓 *M.S. Information Technology (AI & Data Analytics Concentration), Kennesaw State University*  
🔗 [LinkedIn](https://www.linkedin.com/in/gnana-prakash-reddy-026277208/)  
![WhatsApp Image 2025-10-07 at 16 10 47_b4f00fa6](https://github.com/user-attachments/assets/97dcf417-e89b-4295-88ca-6949c7aaeabf)


Hi, I’m **Gnana Prakash Reddy**, a passionate **data enthusiast** currently pursuing my Master’s in IT at **Kennesaw State University**.  
I’m deeply interested in how **data can uncover insights, tell stories, and guide smarter decisions** across industries.  
I love working with **analytics, predictive modeling, and machine learning**, turning raw data into meaningful outcomes.  
Skilled in **Python, SQL, Power BI, and Scikit-learn**, I aim to grow as a **data-driven problem solver** who blends technical skill with creativity to make real impact.

---

### 👨‍💻 **Akshay Krishna Varma Buddharaju**  
🎓 *M.S. Computer Science (Data Science Concentration), Kennesaw State University*  
![WhatsApp Image 2025-10-07 at 16 11 15_96614635](https://github.com/user-attachments/assets/70fdb1dc-0c21-4e86-9d80-4ec73379de81)
🔗 [LinkedIn](https://www.linkedin.com/in/akshay-krishna-varma-buddharaju/) | [GitHub](https://github.com/AkshayVarmaBud)  

Hi, I’m **Akshay Krishna Varma**, a passionate **Software Engineer and AI enthusiast** currently pursuing my Master’s in Computer Science at **Kennesaw State University**.  
I’m driven by a curiosity to build systems that make technology **smarter, faster, and more human**.  

With experience as a **Software Engineering Intern at Home Depot** and **Graduate Research Assistant**, I enjoy tackling real-world challenges in **AI, machine learning, and scalable software development**.  
I love blending creativity with engineering precision to turn complex problems into elegant, data-driven solutions.

---
> _“Turning environmental data into insight and impact — one dataset at a time.”_ 🌎  
> ✨ *“Individually, we analyze data. Together, we transform it into knowledge.”*  
> — *Team EcoDataAnalytics*
---
---

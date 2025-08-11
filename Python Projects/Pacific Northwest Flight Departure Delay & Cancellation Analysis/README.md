# Pacific Northwest Flight Departure Delay & Cancellation Analysis

**Author:** ISTIAK ALAM  
**Affiliation:** DataCamp Real World Project  

---

## 📌 Project Overview

This project examines flight departure delays and cancellations from Seattle-Tacoma International (SEA) and Portland International (PDX) during the first half of 2022. By analyzing detailed flight data and integrating corresponding weather features, the analysis surfaces the most delay/cancellation-prone routes and the operational and environmental factors affecting reliability. The workflow and results empower data-driven planning for airlines, airports, and travelers in the Pacific Northwest.

---

## 📄 Project Files and Links

- **Project Notebook:** [`notebook.ipynb`](notebook.ipynb)
- **Technical Report:** [`Pacific Northwest Flight Departure Delay & Cancellation Analysis.pdf`](Pacific%20Northwest%20Flight%20Departure%20Delay%20%26%20Cancellation%20Analysis.pdf)
- **DataCamp Project:** [View on DataCamp](https://www.datacamp.com/datalab/w/263fb78e-b69b-48c2-a832-e821e785fabf/edit)
- **DataCamp Portfolio:** [istiak-data-analyst Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 🛠 Methodology

- **Data Loading:** Imported and cleaned primary flight and weather datasets, covering all departures from SEA and PDX January–June 2022.
- **Feature Engineering:** Created a composite route column and calculated mean departure delays and total cancellations by route.
- **Aggregation & Analysis:** Ranked routes by average departure delay and number of cancellations; investigated weather impacts using mean visibility and wind gusts.
- **Visualization:** Created business-ready bar charts and scatterplots to illustrate critical risk points for travelers and operators.

---

## 📊 Key Visualizations

### 1. Project Cover Photo
![Cover](IMG_8801.JPG)

### 2. Mean Departure Delay by Route
![Mean Departure Delay by Route](Mean%20Departure%20Delay%20by%20Route.png)

### 3. Weather Impact (Scatterplot)
![Weather Impact (Scatterplot)](Weather%20Impact%20%28Scatterplot%29.png)

---

## 📈 Results Overview

- **Delay Leaders:** PDX-DSM, PDX-GRR, PDX-FLL, SEA-MIA, and SEA-CLT routes showed the longest mean delays; PDX-DFW and SEA-CLT had elevated cancellation rates.
- **Weather Impact:** Low visibility and high wind gusts were associated with worse departure delays, highlighted in the bubble scatterplot.
- Routes with both large delays and weather risk are top priorities for operational and traveler mitigation.

---

## 🚦 Recommendations for Stakeholders

**For Passengers:**  
- Plan for longer waits on high-risk routes (e.g., PDX-DSM, SEA-MIA) and consider weather patterns when traveling in winter/spring.

**For Airlines:**  
- Use these insights for schedule smoothing, crew/resource planning, and more proactive communications on high-delay corridors.

**For Airport Management:**  
- Optimize resource allocation, scheduling buffers, and ground operations at critical hours or on affected routes.

---

## 📁 Repository Structure


├── Pacific Northwest Flight Departure Delay & Cancellation Analysis.pdf
├── notebook.ipynb
├── IMG_8801.JPG
├── Mean Departure Delay by Route.png
├── Weather Impact (Scatterplot).png
├── README.md
└── data/ # (flight and weather CSVs)
---

## 📝 Conclusion


This analysis demonstrates robust airline/airport data wrangling and business insight, blending extensive Python analytics with clean reporting and stakeholder-focused recommendations.  

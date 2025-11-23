# 📊 Data Analysis & KPI Development - ONEE IT Service Center

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://www.microsoft.com/)


## 🎯 Project Overview

End-of-first-year internship project in **Business Intelligence & Analytics** conducted at the National Office of Electricity and Potable Water (ONEE) - Water Branch.

The main objective was to **optimize IT service management** by analyzing data from the Khadamate platform and creating interactive dashboards to monitor Service Center performance.

### 🔑 Key Highlights
- **6,436** requests analyzed over **519 days**
- **3 interactive dashboards** created with Power BI
- **15+ KPIs** developed for performance tracking
- Improved service **visibility** and **responsiveness**

---

## 📸 Dashboard Previews

### Dashboard 1: Request Overview
![Dashboard Overview](docs/presentation/Dashboard%20Overview.png)

**Key Insights:**
- Average of 17.93 requests per day
- 73.75% service requests vs 26.25% incidents
- Identification of most frequent categories
- Monthly trend analysis with seasonal patterns

**Features:**
- Request distribution by classification
- Request status breakdown (Resolved, Closed, Rejected, In Progress)
- Beneficiary analysis by department
- Time series visualization

---

### Dashboard 2: Service Performance
![Dashboard Performance](docs/presentation/Dashboard%20Performance.png)

**Important Metrics:**
- Average resolution time: 167.90h (actual) / 91.55h (theoretical)
- 57.35% SLA compliance rate
- 103 urgent requests resolved out of 151
- Mean time between failures: 208.65 hours

**Features:**
- Urgent request tracking and resolution
- SLA compliance monitoring
- Monthly ticket closure trends
- Delegated request analysis
- Well-documented request ratio

---

### Dashboard 3: Task Monitoring
![Dashboard Tasks](docs/presentation/Dashboard%20Tasks.png)

**Analysis:**
- 7,597 tasks processed
- Escalation rate: 32.05%
- Average of 21.40 tasks per day
- Identification of key stakeholders

**Features:**
- Top 5 task handlers and intervention groups
- Task distribution by classification
- Monthly task volume trends
- Average tasks per sender
- Task status breakdown

---

## 🛠️ Technologies & Tools

| Technology | Usage |
|------------|-------|
| **Power BI Desktop** | Interactive dashboard creation and data visualization |
| **Power Query** | Data cleaning, transformation, and ETL processes |
| **DAX (Data Analysis Expressions)** | Custom KPI calculations and measures |
| **Figma** | Organizational chart design and mockups |
| **Microsoft Excel** | Preliminary data exploration and analysis |

---

## 📊 Methodology

The project followed the **CRISP-DM** (Cross Industry Standard Process for Data Mining) methodology:
```
1. Business Understanding
   └─> Analyzing Service Center needs and objectives

2. Data Understanding
   └─> Exploring Khadamat and Khadamat-Tasks tables

3. Data Preparation
   └─> Cleaning, transforming, handling missing values
   └─> Standardizing data types and formats

4. Modeling
   └─> Creating KPIs and custom measures
   └─> Designing data relationships

5. Evaluation
   └─> Validating results with stakeholders
   └─> Testing dashboard usability

6. Deployment
   └─> Dashboard production deployment
   └─> User training and documentation
```

---

## 🎯 Developed KPIs

### Request Metrics
- ✅ Total number of requests
- ✅ Average resolution time
- ✅ SLA compliance rate
- ✅ Number of urgent requests
- ✅ Distribution by classification
- ✅ Request status breakdown
- ✅ Monthly/yearly trends

### Task Metrics
- ✅ Total number of tasks
- ✅ Average handling time
- ✅ Escalation rate
- ✅ Average tasks per sender
- ✅ Performance by handler
- ✅ Task classification distribution

### Operational KPIs
- ✅ Mean Time Between Failures (MTBF)
- ✅ Well-documented request count
- ✅ Delegated requests
- ✅ Monthly trends and patterns
- ✅ Department-level analysis

---

## 💡 Problems Solved

### 🔍 Before the Project
- ❌ Lack of performance visibility
- ❌ Difficulty identifying bottlenecks
- ❌ No centralized indicators
- ❌ Manual data processing

### ✅ After the Project
- ✔️ Clear identification of improvement areas
- ✔️ Data-driven decision making
- ✔️ Proactive issue identification

---

## 📈 Key Results & Recommendations

### Main Findings

1. **Recurring Requests**: 29.55% of requests concern password initialization
   - *Impact*: High volume of routine tasks consuming support resources
   
2. **Resolution Times**: Urgent requests resolved in an average of 79.22 hours
   - *Impact*: Room for improvement in critical issue handling
   
3. **SLA Performance**: 57.35% compliance with service level agreements
   - *Impact*: Need for process optimization to improve reliability
   
4. **Workload Patterns**: Activity peaks identified in July-August
   - *Impact*: Seasonal resource planning required

5. **Escalation Analysis**: 32.05% escalation rate
   - *Impact*: First-level support could be strengthened

### Strategic Recommendations

1. 🔄 **Implement Self-Service Solutions**
   - Deploy password reset portal
   - Create knowledge base for common issues
   - *Expected impact*: 20-30% reduction in routine requests

2. ⚡ **Improve Urgent Request Handling**
   - Establish priority queues
   - Implement automated alerts for critical issues
   - *Expected impact*: 30% reduction in urgent request resolution time

3. 📚 **Enhance First-Level Support Training**
   - Reduce escalation rates
   - Improve first-contact resolution
   - *Expected impact*: 15% decrease in escalations

4. 📊 **Establish Automated Alert System**
   - SLA breach warnings
   - Real-time performance monitoring
   - *Expected impact*: Improved SLA compliance to 75%+

5. 🎯 **Optimize Resource Allocation**
   - Adjust staffing based on monthly patterns
   - Balance workload across teams
   - *Expected impact*: Better service during peak periods

---

## 📁 Project Structure
```
ONEE-Service-Center-Analytics/
│
├── 📄 README.md                              # This file
│
├── 📁 docs/                                  # Documentation
│   ├── RAPPORT_STAGE_SALMA_BOUTANFIT.pdf   # Complete internship report (French)
│   └── presentation/                         # Visual assets
│       ├── Dashboard Tasks.png            # Dashboard 3 screenshot
│       ├── Dashboard Overview.png                        # Dashboard 1 screenshot
│       └── Dashboard Performance.png                       # Dashboard 2 screenshot
```

---



## 🎓 Internship Context

- **Institution**: National School of Computer Science and Systems Analysis (ENSIAS)
- **Program**: Business Intelligence & Analytics (1st year)
- **Company**: National Office of Electricity and Potable Water (ONEE) - Water Branch
- **Division**: Information Systems Department (DSI)
- **Period**: July - October 2024
- **Supervisor**: Mr. EL BACHRAOUI Mohammed
- **Jury**: Mr. Omar OUHEJJOU, Mr. Noureddine KERZAZI



## 🔮 Future Enhancements

Potential improvements for the next iteration:

1. **Real-time Data Integration**
   - Live dashboard updates
   - Automated data refresh from Khadamate platform

2. **Predictive Analytics**
   - Forecast request volumes
   - Predict potential SLA breaches

3. **User Satisfaction Metrics**
   - Integrate feedback surveys
   - Net Promoter Score (NPS) tracking

4. **Mobile Dashboard Access**
   - Power BI mobile optimization
   - On-the-go performance monitoring

5. **Advanced Analytics**
   - Root cause analysis
   - Correlation studies between variables

---


## 🙏 Acknowledgments

Special thanks to:

- **ONEE - Water Branch** for the internship opportunity
- **Mr. EL BACHRAOUI Mohammed** for his guidance and mentorship
- **DSI Team** for their collaboration and support
- **Jury Members**: Mr. Omar OUHEJJOU and Mr. Noureddine KERZAZI
- **ENSIAS** for the academic foundation

---


### Structure de dossiers simplifiée :
```
ONEE-Service-Center-Analytics/
│
├── README.md
│
└── docs/
    ├── RAPPORT_STAGE_SALMA_BOUTANFIT.pdf
    └── presentation/
        ├── Dashboard Overview.png
        ├── Dashboard Performance.png
        └── Dashboard Tasks.png
```


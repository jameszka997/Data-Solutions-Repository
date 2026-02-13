# 📊 Power BI Project Timeline Tracker Dashboard

**A comprehensive project timeline management and tracker dashboard to track deadlines, milestones for projects and team members.**




## 🎯 Overview

This Power BI dashboard provides real-time visibility into project progress, tracking deadlines & milestones multiple projects and project owners. The solution transforms scattered project data into actionable insights, enabling stakeholders to make informed decisions and proactively address potential delays.

### **!!! Disclaimer**
As the project was aimed at company owned and specific information, synthetic dummy data was created to show and demonstrate the function of the dashboard tool.



## 🏢 Business Problem

### Context
The team within my organization lacked an easy to view and visible milestone and deadline management method to track 100+ projects assigned to the team across multiple project owners.


### Specific Challenges
- **Lack of Centralized Tracking:** Project information scattered across multiple Excel files and email threads
- **Poor Visibility:** Management had limited real-time insight into project status and potential risks
- **Manual Reporting:** Weekly status reports required significant manual effort and were often outdated
- **Missed Deadlines:** No early warning system for projects at risk of missing critical milestones
- **Resource Allocation:** Difficulty identifying bottlenecks and optimizing team workload



## 💡 Solution Overview

### High-Level Approach
Developed a comprehensive Power BI dashboard that consolidates project data from multiple sources, providing automated tracking, predictive analytics, and interactive visualizations for all stakeholder levels. Timelines are shown and managed by a Gantt visual from ADWISE Roadmap (v3.1.3.0).


### Key Solution Components
- Automating data integration & refresh scheduling
- Data transformation to adapt to the data formatting needs of the visual
- Interactive view and filtering options for users for customizable use (*Project Owner, Time, Project Milestone & Deadlines*)

## 🔧 Project Details

### Data Sources & Structure

Data Source was the datatable within Excel to track project deadlines, specifics and phases, accessed by all members of the team and updated by each team member in an on-going manner.

The table compiles the following information, each within its own ***column***
- Dates for project milestones (e.g.: when partner was contacted, when project meetings are due & scheduled for, etc.)
- Project ID
- Assigned Project Owner


### Data Preparation & Transformation
- **Data Cleaning:** Standardized date formats, removed duplicates, handled missing values
- **Data restructuring:** Restructuring existing project tracker columns to Gantt visual compatible format.
- **Set-up of Dashboard:** Set-up of restructured database into Timeline visual and applicable filters.





### Features
- **Color coding:** Color coded indicators for Milestones to indicate specific dates and phases to indicate due timelines.
- **Dynamic filtering:** Dynamic filtering based on project owner, date range, and project status
- **Real-time data showcase:** Data is refreshed and timelines and dates are automatically updated when data is entered into the source tracker by users.
	

### Visualization Design Decisions
- **Color Coding:** Consistent RAG (Red-Amber-Green) status indicators
- **Layout:** Logical flow from high-level overview to detailed drill-downs
- **Typography:** Clear hierarchy with appropriate font sizes
- **Interactivity:** Cross-filtering between visuals for seamless exploration


## 🎯 Key Skills Demonstrated

- Data cleaning, transformation, restructuring, and quality assurance
- Business requirements analysis and stakeholder communication
- Power BI development including advanced DAX calculations, custom visualizations, interactive dashboard design, and performance optimization
- Data integration with automated refresh setup and error handling
- Dashboard design best practices and solution documentation


## 🛠️ Tools & Technologies

### Primary Tools
- **Power BI Desktop** - Dashboard development
- **Power BI Workspace Service** - Publishing and sharing
- **Excel** - Data preparation and validation
- **Power Query** - Data transformation
- **SharePoint** - Data source and collaboration

### Version Control & Documentation
- **Git** - Version control for .pbix files
- **Markdown** - Documentation and README files


## 🚧 Challenges 

- Data entry inconsistencies and resolution for harmonized and reliable data source
- Correct data source restructuring and investigation to fit data structure requirements of Gantt Visual
- Set-up of Power BI Workspace for team, and onboarding to the use of the project timeline tool
- Testing multiple Gantt chart visual sources for a balanced and simple visual structure




## 🚀 Future Enhancements

### Implementation of DAX Measures & Calculations for better information and alarms
- **Project Health Score:** Assigning multiple criticality levels based on number of days behind deadlines for project phases via `SWITCH()` function
- **Completion Percentage:** Calculating project % completion based on defined phases and milestones
- **Days Remaining Alarm:** Showing number of days remaining per project phase for each project via `DATEDIFF()` function



### Questions or Feedback?
I'm always interested in discussing data analytics, Power BI development, and business intelligence solutions. Feel free to reach out if you have questions about this project or would like to collaborate!

---

⭐ **If you found this project helpful, please consider giving it a star!**

*This project demonstrates practical application of business intelligence tools to solve real-world project management challenges. It showcases end-to-end development from problem identification to solution delivery.*

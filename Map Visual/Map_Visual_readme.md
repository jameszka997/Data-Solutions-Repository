# 📊 Power BI Map Dashboard

**A comprehensive and interactive Azure Map visual to showcase the location of projects and point them on a map as a tracking tool.**


<img width="700" height="388" alt="map_visual_banner" src="https://github.com/user-attachments/assets/b14eee61-5a0a-4f28-ac32-95bb784ea630" />




## 🎯 Overview

This Power BI Map dashboard provides a real-time insight into projects to showcase where they are located on the map, showcase project status, and incorporating interactive filter & slicer options. The tool provides a solution to more easily visually track the location, as well as of projects for an on-going team between multiple project owners.

### **!!! Disclaimer**
As the project was aimed at company owned and specific information, synthetic dummy data was created to show and demonstrate the function of the dashboard.



## 🏢 Business Problem

### Context
The team within my organization works with 100s of on-going projects on a continent scale, without a visible tool to showcase the location of these projects to aid in project planning, as well as showcasing the status of these projects easily. 



### Specific Challenges
- **Lack of Visual Information:** Project location is not visibly showcased, not allowing easy visualization for project planning & organization.
- **Hard to track Project Statuses:** Existing system does not easily showcases and compiles the status of on-going projects.
- **Lack of Optimization tools:** No tool to showcase how close projects could be to each other, even within the same country, to allow better and more efficient resource allocation.



## 💡 Solution Overview

Developed a comprehensive Power BI dashboard that compiles the project data from the source database, and providing interactive filtering approaches to showcase project specifics, location, owner. Azure Map visual was utilized to put the project points on the map based on *Country* & *City* location.


### Key Solution Components
- Setting daily refresh schedule for most up-to-date data on projects
- Selection of most descriptive information to showcase most important information about each project.
- Interactive view and filtering options for users for customizable use (*Project has been allocated, Project has scheduled meeting, Country, Project Status, Project Type, Month, Project Owner, Search Bar*)



## 🔧 Project Details

### Data Sources & Structure

Data Source is excel-based database to track project deadlines, and specifics related to information stored about the project companies, accessed by all members of the team and updated by each team member in an on-going manner.

Data Source combines data from 2 entry manners:
- On-going entry from users about project dates, updates, outcomes.
- General information about project from central database downloaded and refreshed weekly by comparing last week's and current week's information. Primarily used for Project Status updates.




### Data Preparation & Transformation
- Clean-up & reconciliation of errors, missing values, and making uniform data entry format.
- Data columns were chosen and unnecessary columns were removed to make resource usage more efficient.
- Combining *Country* & *City* column information in *Location* information which provides the location information, central to the Map.




### Features
- **Color coding:** Color coded indicators for points on map to visually showcase project status.
- **Dynamic filtering:** Dynamic filtering based on user input and requirement.
- **Real-time data showcase:** Data is refreshed and timelines and dates are automatically daily to provide accurate and up-to-date information.
	


## 🎯 Key Skills Demonstrated

- Power Query for efficient data cleaning, transformation, restructuring, and quality assurance
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
- Correct data source restructuring and investigation to fit data structure requirements
- Set-up of Power BI Workspace for team, and onboarding to the use of the project timeline tool
- Testing multiple Map versions to reconcile any data handling mistakes and visual glitches.




## 🚀 Future Enhancements

### Implementation of Airport location information to showcase nearest airport for better project organisation
- **Airport location:** Interactive toggle on airport location information to aid in finding nearest airport for scheduling travel plans.
- **Reconciling location format differences:** Location formats differ for the project and airport datasources (`location based on country & city vs. location in latitude and longitude coordinates`)
- **Reconciling data source integration:** Two data sources for airport and project data need to be incorporated and connected to each other. Azure Map's limitation is that it only allows one interactive point layer to be showcased on the map, and two datatables cannot be seamlessly highlighted.


### Questions or Feedback?
I'm always interested in discussing data analytics, Power BI development, and business intelligence solutions. Feel free to reach out if you have questions about this project or would like to collaborate!

---

⭐ **If you found this project helpful, please consider giving it a star!**

*This project demonstrates practical application of business intelligence tools to solve real-world project management challenges. It showcases end-to-end development from problem identification to solution delivery.*

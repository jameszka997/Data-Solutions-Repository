


# Data Structuring Supportive document

The current documents aims to give an overview of the data structure used for the Gantt chart (`ADWISE Roadmap v3.1.3.0`) that showcases the project timelines and milestones.


## Structure of the Datatable
| Column name	|Function	|Data Type|
|--|--|--|
|Project Owner |Displays Assigned Project Owner |Text|
|Axis Y	|Shows the projects name	|Text|
|Details	|Short description of each entry which displays what date entry shows on the timeline	|Text|
|Start Date	|Start date of the entry	|Date|
|End Date	|End Date of the entry - > *Same day for 1 day events (Milestones), and more based on defined dates for due dates (currently only 28 days implemented) (Phase)*	|Date|
|Description	|Has the original column names which are utilized prior to pivoting the data	|Text|
|Type	|Sets the type of visual used within the Gantt chart whether it is Milestone (single point) or Phase (longer deadline)	|Text|


### Source dataset
*Due to maintain privacy of the source data, the data structure would be explained in general terms*

- Project Owner column
- Project Name column
- Each date column has a specific name to document the date for project milestones and requirements (e.g.: when project partner wsa notified, project meeting date, etc.)


### Data restructuring
Within Power Query, the above mentioned columns are selected and kept from the source datatable. Date columns represent individual start date entries for the project milestones & phases. After determining which columns would be handled as a *Milestone* or *Phase* date (`to get some phases, some date columns needed to be duplicated as the same date entry also means the project milestone and that milestone being the start date of an associated phase or due timeline`). 

Date columns are selected and using the `pivot table` function within Power Query to change the data structure, this results in one column (*Start Date*) that conserves the date, and the text from the column headers (*Description*). 

Using an if function, *Type* column is created to properly address which date entry is which, as explained previously. Based on this, the *End Date* column would be created. For *Milestones*, the date is the same as the Start Date, for *Phases*, the End Date would be X number of days after the Start Date to properly showcase the defined due date.

Project Name column is renamed to *Axis Y*. *Details* column would be shorter abbreviations for the *Description* entries to be more compact and more visible within the Timeline Dashboard. 


### Explanation for column structure within Gantt chart
ADWISE Roadmap offers free featues which covers the 6 columns within the new data structure (aside from *Project Owner* which is used only for one of the filtering options).

<img width="761" height="207" alt="image" src="https://github.com/user-attachments/assets/a6fd8b35-0aaf-4467-b888-28e45f613eaa" />

The assigned values are entered into the corresponding visual columns within Power BI and the data is visualized.


The following dashboard utilizes the ADWISE Roadmap Gantt chart visual from [ADWISE-visuals](https://www.adwise-visuals.com/).






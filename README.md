Ushahidi Programs Plotr
===========
This is a visualization tool for looking at key deliverables and milestones milestones for Ushahidi programs. You can see the [Plotr visualization here](http://?????) or [add dates and milesontes here](https://docs.google.com/spreadsheets/d/1NXG2znwFFdbyK83wHmN00AEp_t_OMAoRkShicl_y7Wk/edit#gid=0). See below for more information about how to interpret the visualization or enter data.

### About
This is simple sortable chart for viewing and tracking programmatic deliverables and milestones on a timeline. It is primarily for coordination among Ushahidi programs: especially around shared goals such as trainings, volunteer engagement, and product releases. It is useful for a quick global view of what's going on when and how the milestones/expectations/resourcing need to be managed. This was originally developed by Aurelia Moser ([original repo here](https://github.com/auremoser/pirateplotr)) and I've adopted it for programmatic use.  

### How to...
1. Edit data in the Google Spreadsheet [here](https://docs.google.com/spreadsheets/d/1NXG2znwFFdbyK83wHmN00AEp_t_OMAoRkShicl_y7Wk/edit#gid=0). See the key below for what information to enter in which columns. 
2. Spreadsheet will update in the chart on a semi-frequent basis, which depends on google. Usually you can refresh the [Plotr visualization](http://?????) every 5 minutes and it will show your changes.
3. View and Sort the chart! [Plotr visualization here](http://?????)  

![Chart](https://?????) 

### Data
Data csv looks like this:

![data.csv](https://?????)

Headers in the spreadsheet are static, but all values are editable in the data.csv file.

deliverable	| priority	| start_date	| end_date 	| team | type
:---:	| :----: 	| :--------: 	| :------: 	| :----: | :----:
project1 | value1 	| date1 		| date2 	| [DREAMS/Uchaguzi/...] | external
project2 | value2 	| date1 		| date2 	| [DREAMS/Uchaguzi/...] | core

#### key
* **deliverable** is _brief_ description of the deliverable.
* **priority** is an arbitrary weight. This is a placeholder that was originally intended to be replaced by some numerical value that we might want to priotize by, such as cost, price, or resources. We can figure out how to use this... or leave it blank!
* **dates** are the start and end date of a project.
* **team** is the name of the team responsible for the deliverable. I've populated the spreadsheet with a drop-down menu for: Uchaguzi, DREAMS, COMRADES, and Platform.
* **type** is one of 4 categories for filtering purposes. I don't honestly remember what these different categories meant at the time they were created so I'd be happy to change them. Right now, I'm using
  * "core" as an internal deadline;
  * "external" is a public facing deadline;
  * "ops" - I'm not using this right now. 
  * "milestone" creates a vertical plum lines on the chart as opposed to a bar that shows something happening over time. You create these by entering a `deliverable` name, a `start_date`, and then listing the `type` as "milestone". Check the csv for examples of this.

Give me a shout if you have any further questions!






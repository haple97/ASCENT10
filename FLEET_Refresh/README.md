By 2020, FLEET Tool has been in use for over 10 years with little documentation of changes. FLEET Refresh task aimed to recover the lost data-manipulation process used by past members of the project, in order to re-produce similar and usable data to update the tool the current task, which is route allocation of suspersonic flights. For the purpose of the project and assumptions of FLEET Tool, 'usable' data are the number of passengers (or demand) on all scheduled and passenger-service routes between airports among the WWLMINET 257 airports (WWLMINET: Worldwide Logistics Management Institute Network Queuing Model) by US-domestic airlines (combined as one giant airline).

Currently, the raw demand data are obtained from Bureau of Transportation Statistics (BTS), T-100 Segment (All Carriers). The data are available here: https://www.transtats.bts.gov/Tables.asp?DB_ID=111&fbclid=IwAR1pb1Ts5eMvWPsYVxTGdWtGI0TQM_Wj-ucGip1AlcIwAh9xjJcCjPFLyrg

Python with Jupyter Notebook was used mainly for the task. There were three steps in this task, corresponding to the three folders of code. 
- Data manipulation commands were created based on purpose and assumptions of the project. The Data Filters Code folder consists of 3 different versions: one was the discovered version the original code used up until May 2020, and the other two were updated code for higher validity used since May 2020 for analysis of yearly and monthly demand. 
- Outputs were checked with current data used in FLEET Tool. The code used for this step is in Output Comparison Code folder. 
- Once the data manipulation steps satisfied, the outputs were converted into a demand matrix and MATLAB file. OD Matrix Generation Code folder contains code used for this step. 

Information: 
- Python 3
- Jupyter notebook 
- Libraries: numpy, pandas

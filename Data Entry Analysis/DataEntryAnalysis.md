## **Data Entry Analysis**

### **_Step 1: List some problems in the given data._**

> The following problems were identified from the data given in the 3 files. 

- The name of the files could be something more appropriate and meaningful giving an idea about what the file consists. A consistent format in the naming the file would make it easier to look for the required data when the number of files increase in future. 
- The files named '_pond2010_' and '_zoop-temp-main_' consist a blank yellow block. There is no further information on it nor any mention of what these yellow spaces stand for. 
- Some rows or certain numbered data are highlighted in a different color but again with no information about what it means. 
- Also, the color used to highlight the data is not consistent. Mostly, it is in '_red_' color but a single number in the '_zoop-temp-main_' file is also highlighted in '_orange_'. Why?
- The file '_pond2010_' contains some blank data and this ineficiency in the data will result into flawed conclusions. 
- The tab names used in all the 3 files vary and this inconsistency creates confusion in understanding the data. The file '_zoop-temp-main_' has 2 tabs, '_Station A_' and '_Names_'. The file '_zoop-temp_' has 1 tab, '_Rotifers_'. The file '_pond2010_' has 1 tab, '_Data_'.
- As mentioned in the background, plankton change their distributions from day to night and it varies in different species but none of these files include the time data. 
- The background also had information about how the plankton numbers/units are reported. Under a microscope they are counted as '_individuals per liter or milliliter_'. The file has no data for plankton in these units of measurement. 
- There is no information on what column '_z_' means in the '_pond2010_' file. 
- A description should be given for '_Cuni #/L_' and '_Chippo #/L_'. What does it refer to?
- The '_zoop-temp-main_' file has a tab named '_Station A_' and the '_zoop-temp_' file has some information on '_Station B_'. Are these two different locations or data for different years? The data used and included should be clarified in every file. 
- Units for depth, density and temperature should be mentioned for data efficiency. 

### **_Step 2: Suggest a new system for the organization._**

> The following suggestions are made for the problems listed above. 

- The blank yellow spaces or blank data should be eliminated or appropriate data should be given.
- The meaning of the highlighted data (in a different color) should be explained or not used at all. If more than one color is used then the meaning for each should be mentioned. 
- The file name should be consistent. This makes it easier to manage and understand. Like, '_Plankton_Data_<year>_', where year could vary for all their analysis over the years. For example, 'Plankton_Data_2017', 'Plankton_Data_2018' and so on.
- The tab names used should be consistent. Also every file should have a tab called 'Reference' where all the column names, color-codes, shortforms, etc. are explained for the user's reference and understanding. 
- Units for all the numbered data should be mentioned like 'Celcius/Farenheit', 'Meters', 'Liter/Milliliter', etc. 
- A 'CollectionTime' column is needed to record when the plankton samples were collected. The data can simply be mentioned in 'Am/Pm'. 
- I have removed the column 'z' and not mentioned a column for station as the information is not clear. If needed a 'Station/Location' column can be added by the organization and the same can be explained in the 'Reference' tab. 
- Similarly, to simplify the data, I have created a 'SpeciesName' column along with 'ColonySize' and 'ColonyDiameter' for the specified species.
- Due to lack of information, I have removed the 'Cuni #/L' and 'Chippo #/L' columns.
- The units for 'ColonySize' and 'ColonyDiameter' are not specified in the data so I have left it blank in my template but the organization can add that as per their unit of measurement. 
  
> **_Template for Plankton_Data_2018:_**

| SpeciesName | CollectionTime (Am/Pm) | Date | ColonySize (Unit) | ColonyDiameter (Unit) | Temperature (Celsius/Fahrenheit) | Depth (Meters) | Density (Liter/Milliliter) | Chlorophyll a |
|-------------|:----------------------:|------|:-----------------:|:---------------------:|:--------------------------------:|:--------------:|:--------------------------:|:-------------:|

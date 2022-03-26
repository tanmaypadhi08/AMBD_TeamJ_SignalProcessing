# REQUIREMENTS

## HIGH LEVEL REQUIREMENTS

|S.No| Requirements|Number of Input| Status|
|----|-------------|---------------|-------|
|HLR 1|Oximeter|1|Yes|
|HLR 2|Temperature Check|1|Yes|
|HLR 3|Blood Pressure Check|2|Yes|
|HLR 4|Blood classification|1|Yes|
|HLR 5|Glucometer|1|Yes|
|HLR 6|Blood Platelet Check|3|Yes|
|HLR 7|Condition of Kidney|1|Yes|
|HLR 8|Urine Analyser|1|Yes|
|HLR 9|Thyroid Checkup|1|Yes|

 
 
 
 ## LOW LEVEL REQUIREMENTS
 
 |S.No| Requirements|HLR| Status|
 |----|-------------|---|-------|
 |LLR 1.1 |Only one input is required|HLR 1|Yes|
 |LLR 1.2 |The normal range should be between 93 to 99|HLR 1|Yes|
 |LLR 1.3|If the input exceeds 99, it will show negative output|HLR 1|Yes|
 |LLR 1.4|If the input is less then 93, it will show negative output|HLR 1|Yes|
 |LLR 3.1|Two inputs detemine the condition|HLR 3|Yes|
 |LLR 3.2|Different ranges determine different conditions|HLR 3|Yes|
 |LLR 4|Based on the Antigen and Anti-bodies blood classification can be done|HLR 4|Yes|
 |LLR 5.1|If the input is Less than 5.7% is normal|HLR 5|Yes|
 |LLR 5.2|If the input is lies between 5.7% to 6.4% is diagnosed as prediabetes is normal|HLR 5|Yes|
 |LLR 5.3|If the input is 6.5% or higher then the test indicates diabetes|HLR 5|Yes|
 |LLR 6.1|Only one input is required|HLR 6|Yes|
 |LLR 6.2| If the input is less than 150000 then it is Thrombocytopenia|HLR 6|Yes|
 |LLR 6.3| If the input is between 150000 to 450000 then it is normal|HLR 6|Yes|
 |LLR 6.4| If the input is greater than 450000 then it is Thrombocytosis|HLR 6|Yes|
 |LLR 6.5| If the input is less than 4.8 then red blood cells are low|HLR 6|Yes|
 |LLR 6.6| If the input is between 4.8-9.3 then the red blood cells are normal condition|HLR 6| Yes|
 |LLR 6.7|If the input is greater than 9.3 then the red blood cells are high|HLR 6|Yes|
 |LLR 6.8| If the input is less than 4.0 then the white blood cells are low|HLR 6|Yes|
 |LLR 6.9| If the input is between the 4.0-15.5 then the white blood cells are normal|HLR 6|Yes|
 |LLR6.10| If the input is greater than 15.5 then the white blood cells are high |HLR 6| Yes
 |LLR 7.1|Only one input is required|HLR 7|Yes|
 |LLR 7.2|The Normal condition is 90 - 100 |HLR 7|Yes|
 |LLR 7.3|The Mild loss condition is 60 - 89 |HLR 7|Yes|
 |LLR 7.4|The Moderate condition is 42 - 59 |HLR 7|Yes|
 |LLR 7.5|The Severe condition is 15 - 41 |HLR 7|Yes|
 |LLR 7.6|The Failure condition is less than 15 |HLR 7|Yes| 
 |LLR 8.1|Take input as urine sample value and tell the health condition |HLR 8|YES| 
 |LLR 8.2| Take decimal input and able to tell health condition |HLR 8|YES|
 |LLR 9.1|For overactive thyroid symptomatic the condition the THS value is lessthan 0.1 mU/L.|HLR 9|Yes|
 |LLR 9.2|For subclinical overactive thyroid the condition the THS value is in between 0.1 to 0.5 mU/L|HLR 9|Yes|
 |LLR 9.3|For normal condition the THS value is in between 0.5 to 4.7 mU/L|HLR 9|Yes|
 |LLR 9.4|For subclinical lowlevel thyroid the condition the THS value is in between 4.7 to 10 mU/L|HLR 9|Yes|
 |LLR 9.5|For low thyroid symptomatic the condition is the THS value is greater than 10 mU/L|HLR 9|Yes|
 
 ## SWOT ANALYSIS
 
 ### Strength
 1. This model can run various test on a patient and can give instant result
 2. It is very simple model and design is very neat

### Weakness
1. The model takes very less number of input so there is a chance of getting less efficient results

### Oppurtunity
1. This model is light and can be used anywhere required
2. Also the model cost is less so it is cost efficient

### Threat
1. This model does not cover few basic test which ar required for a patient
1. 

# REQUIREMENTS

## HIGH LEVEL REQUIREMENTS

|S.No| Requirements|Number of Input| Status|
|----|-------------|---------------|-------|
|HLR 1|Oximeter|1|Yes|
|HLR 2|Temperature Check|1|Pending|
|HLR 3|Blood Pressure Check|2|Yes|
|HLR 4|Electrocardiography|1|Pending|
|HLR 5|Glucometer|1|Yes|
|HLR 6|Blood Platelet Check|1|Yes|
|HLR 7|Condition of Kidney|1|Yes|
|HLR 8|Urine Analyser|1|Pending|
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
 |LLR 5.1|If the input is Less than 5.7% is normal|HLR 5|Yes|
 |LLR 5.2|If the input is lies between 5.7% to 6.4% is diagnosed as prediabetes is normal|HLR 5|Yes|
 |LLR 5.3|If the input is 6.5% or higher then the test indicates diabetes|HLR 5|Yes|
 |LLR 6.1|Only one input is required|HLR6|Yes|
 |LLR 6.2| If the input is less than 150000 then it is Thrombocytopenia|HLR 6|Yes|
 |LLR 6.3| If the input is between 150000 to 450000 then it is normal|HLR 6|Yes|
 |LLR 6.4| If the input is greater than 450000 then it is Thrombocytosis|HLR 6|Yes|
 |LLR 7.1|Only one input is required|HLR 7|Yes|
 |LLR 7.2|The Normal condition is 90 - 100 |HLR 7|Yes|
 |LLR 7.3|The Mild loss condition is 60 - 89 |HLR 7|Yes|
 |LLR 7.4|The Moderate condition is 42 - 59 |HLR 7|Yes|
 |LLR 7.5|The Severe condition is 15 - 41 |HLR 7|Yes|
 |LLR 7.6|The Failure condition is less than 15 |HLR 7|Yes| 
 |LLR 9.1|For overactive thyroid symptomatic the condition the THS value is lessthan 0.1 mU/L.|HLR 9|Yes|
 |LLR 9.2|For subclinical overactive thyroid the condition the THS value is in between 0.1 to 0.5 mU/L|HLR 9|Yes|
 |LLR 9.3|For normal condition the THS value is in between 0.5 to 4.7 mU/L|HLR 9|Yes|
 |LLR 9.4|For subclinical lowlevel thyroid the condition the THS value is in between 4.7 to 10 mU/L|HLR 9|Yes|
 |LLR 9.5|For low thyreoid symptomatic the condition is the THS value is greater than 10 mU/L|HLR 9|Yes|

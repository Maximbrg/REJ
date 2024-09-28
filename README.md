# Temp-Material-REJ

This folder represents the online appendix for the paper "Leveraging Machines to Derive Domain Models from User Stories", the tree structure of the directory is the following:

--------------------------------------------------
##   Tree Structure
<pre>
├───A Benchmark for Domain Model    # Section III 
│   ├───Agreement # A directory that contains information regarding the tags of the different taggers
│   │       Agreement - Associations.xlsx     
│   │       Agreement - Classes.xlsx
│   │
│   ├───Domain Models # A directory that contains the gold standard models
│   │       Gold standard - Associations.xlsx
│   │       Gold standard - Classes.xlsx
│   │
│   └───User Stories # A directory that contains the user stories
│           camperplus.txt
│           Fish_Chips.txt
│           grocery.txt
│           planningpoker.txt
│           recycling.txt
│           school.txt
│           sports.txt
│           supermarket.txt
│           Ticket.txt
│
├───Discussion # Section VI  
│   ├───False positive error type # A directory that contains the material for findings 4 and 5
│   │       Findings 4&5.xlsx
│   │       fp-analysis-cohen-kappa.csv
│   │
│   └───ML-class-SHAP values # A directory that contains the material for finding 6
│           planningpoker_shapvalues.png
│           campers_shapvalues.png
│           fishchips_shapvalues.png
│           grocery_shapvalues.png
│           recycling_shapvalues.png
│           school_shapvalues.png
│           sports_shapvalues.png
│           supermarket_shapvalues.png
│           tickets_shapvalues.png
│
├───Prompts # Section IV  
│   ├───classes
│       ├───single prompt
│       │       prompt.txt
│       │      
│       │
│       ├───3prompts1ssesion
│       │       prompt_1.txt
│       │       prompt_2.txt
│       │       prompt_3.txt
│       └───3prompts3session
│               prompt_1.txt
|               prompt_2.txt
|               prompt_3.txt
│   
│   └───relationships # A directory that contains the code for generating the features for classes and associations
│       ├───single prompt
│       │       prompt.txt
│       │      
│       │
│       └───3prompts3session
│               prompt_1.txt
|               prompt_2.txt
|               prompt_3.txt
│
└───Evaluation
    │   classes.csv # Tables shown in the paper
    |   relationships.csv # Experiment with DoMoBOT tool

</pre>

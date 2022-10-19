# The difference in crime in the West Midlands in August 2020 vs August 2021

Group 1 - Hibaa Aldubai, Farah Hayat, Badrija Khalifa, Kazimierz Lubas, Anderson Safo

## Modules used:
Python:

•	Pandas

•	Numpy

•	Matplotlib

•	API

•	GMAPS

## Files for this project:

•	“Crime.ipynb”

•	“README.md”

•	“Presentation.pptx”

•	“2020-08-west-midlands-street.csv”

•	“2021-08-west-midlands-street.csv”

## Introduction

The Covid-19 pandemic had a large affect on all of us during 2020 and 2021. Here we are looking to see whether the pandemic also influenced crime rate in the West Midlands specifically looking at the month of August in 2020 and 2021.

We predicted that there would be less crimes committed in 2020 due to most of the population either working from home or on furlough, which meant that there were less people in public and therefore less crime. There were also stricter lockdown laws and many people were still following government recommendations to stay at home compared to 2021 were the rules were more relaxed. 

## Data Cleaning

We obtained our data from data.police.uk- API documentation.
We downloaded 2 CSV files

“2020-08-west-midlands-street.csv”

and

“2021-08-west-midlands-street.csv”.

We then merged the data, removed unwanted columns and removed rows which contained empty cells, we were left with our final dataframe that had approximately 53 thousand rows and 7 columns and is what we used to perform our data exploration. 

## Question one: is there a difference in the total number of crimes between these two months?

Fully recorded crimes in August 2020: 23644.

Fully recorded crimes in August 2021: 29446.

![image](https://user-images.githubusercontent.com/109045338/196573113-0380c961-a4d4-4ec5-a3b2-5fa3551cbc51.png)

## Question two: what are the top 5 types of crime and if the same trend is observed in these specific types of crimes across both months?

![image](https://user-images.githubusercontent.com/109045338/196573335-8d2c5044-4fb6-4e60-af2c-a0192bbe39a1.png)

![image](https://user-images.githubusercontent.com/109045338/196573345-4fbf7a48-54f6-40ee-973b-8b09239d947b.png)

![image](https://user-images.githubusercontent.com/109045338/196573355-9fba9494-de7f-4042-8c80-683d9b97a606.png)

## Question three: was there anything that went against the general trend?

![image](https://user-images.githubusercontent.com/109045338/196573457-949b57e4-5c78-4af4-94c8-491d46005456.png)

## Question four: what were the top crime outcomes across both months?

![image](https://user-images.githubusercontent.com/109045338/196573519-a139373c-8465-4776-ad48-663b386c89e9.png)

![image](https://user-images.githubusercontent.com/109045338/196573528-1214670d-0b35-4df1-8fc9-9532bf297210.png)

![image](https://user-images.githubusercontent.com/109045338/196573538-3e315f72-d1aa-489e-9468-d58486fd8cd9.png)

## Question five: where were the crimes committed?

2020

![image](https://user-images.githubusercontent.com/109045338/196573620-f8209288-8c82-494d-9643-15d888cf7e82.png)

2021

![image](https://user-images.githubusercontent.com/109045338/196573642-dec4be46-896c-4c40-9f5e-4da98cea3424.png)

### Violence and Sexual Offences crimes around the University of Birmingham

2020

![image](https://user-images.githubusercontent.com/109045338/196573691-a0e3452b-7244-4493-8cc7-4f276ffbb267.png)

2021

![image](https://user-images.githubusercontent.com/109045338/196573703-fc1b4cdb-b8e0-4df8-8669-2676e6a198d9.png)

### Anti-Social Behaviour Crimes around the University of Birmingham

2020

![image](https://user-images.githubusercontent.com/109045338/196573749-d7114df7-0a71-4c4b-bde5-0019a3148bba.png)

2021

![image](https://user-images.githubusercontent.com/109045338/196573767-530e5308-cb79-4ad7-b8d9-bb3718698423.png)

## Outcomes and Conclusions

There is a noticeable increase in the number of crimes in 2021 compared to 2020. This could’ve been as a result of the Covid-19 pandemic and the laws and regulations enforced at the time but there may have been other contributing factors as well.

In 2020 many people were furloughed or made redundant and as a result spent more time at home.

Many people were still unsure about Covid-19 and there were stricter rules on masks and social distancing. These were more relaxed in 2021.
In 2021 furlough payment also stopped which could’ve resorted in more crime being committed.

The “Eat Out to Help Out” scheme, which happened in August 2021, may have also had an effected on the number of crimes.

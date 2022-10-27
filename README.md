# 2022-DATA3406-CC05-Group1


- [Proejct description](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#proejct-description)

- [Group members and contracts](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#group-members-and-contracts)

- [Ethical Considerations](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#ethical-considerations)

  - [Purpose](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#purpose)
  
  - [Why it matters](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#why-it-matters)
  
  - Stakeholder Analysis
  
  - Raw Data
  
- Key files


  - Product notebook
  
  - Meeting minutes
  
  - Ethical analysis
 
  - Cognitive walkthrough
  
  - Think aloud
  
  - Reflection on Group Process

- Individual Contribution
    





- References


# Proejct description

- **Project title**

  - *How do people walk? --- `Analysis on people’s weekly step count data`*

- **Driving Question** 

  - `What are the trends in my week to week data?`

- **Sub-questions**
  - `Does the steps for each week affect by season?`
  - `How does week-to-week steps affect by the rainfall?`
  - `Does temperature affect people's willingness to walk?`
  - `Are students less active during the exam week?`
  - `How does the weekly data reflect the risk of diagnosing diabetes?`
  - `How does the weekly data reflect the probability of participant health?`




<img width="875" alt="截屏2022-10-26 下午9 57 03" src="https://media.github.sydney.edu.au/user/10750/files/4142496f-210f-4cb7-a3f6-f6c99d1102e2">




Advanced electronic device are simple and inexpensive wearable motion sensors that are easily used by researchers and practitioners to assess and motivate physical activity behaviors. Hence pedometer-determined physical activity indices are needed to guide their accumulated data. Our report is introducing some specific factors that would affect step counts weekly and evaluating the probability of being healthy based on in sample data applied to logistic regression.




# Group members and contracts

1. When you will reserve a time to meet outside of class each week, for the 
weeks that are needed.
* `Every Sunday.`
2. How you will meet – include here details people need to know.
* `We meet face to face in fisher library.`
3. How you will communicate e.g. mail and agreed response time.
* `Wechat platform and zoom at 3pm sharp.`

<br>

* `Group manager:` Lixin Mu 490570753

* `Tracker:` Ran Sun 510224273

* `GitHub expert:` Kuai Yu 490443550

* `README co-ordinator:` Yuxiang Ji 500516414

* `Group coordinator:` Pengyu Liu 500679649

* `Code adviser:` De Shi 510526247







# Ethical Considerations. 
#### [Wiki page](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Ethical-consideration)

-------------------

## Purpose

* #### ***The purposes involved ethical issues from in sample data and out of sample data.*** 

`In sample data`
  * We explored different participants' datasets to discover some possible factors that will be affecting weekly step counts based on potential aspect of health.

`Out of sample data`
  * For fairness, we were trying to reach our results as many people as possible to be more comprehensive in out of sample data. Hence, we were trying to use a classification algorithm to predict probability of being healthy not only stakeholders but also majorities.

## Why it matters?

* #### ***Ethical issues concern the well-being of every participant involved. It covers the privacy of participants, fairness of data analysis and results, data usage, etc.***

`Privacy`

*  First of all, privacy should be taken into account when collecting the data and resulting in the final conclusions. All participants must have been told that the step activity data would be collected afterward that would not be leaked and intercepted by a third-party cloud server for some unauthorized exchange of benefits. 

`Fairness`

* For fairness of results, the conclusion should be applied to the majority of people in order to promote heteroskedasticity.


# Individual Contribution


# Key files

### Data origin

Our data is about steps data for each day recorded by participants' activity trackers. Some trackers recorded the steps data seperated by time in hours or date. Predictors are asked for step data. Most of data are gotten from Apple Health processed with a python script to convert the xml to csv.
 
### Data definitions

Summary of files, tables, and fields. You can use markdown `tables` here to improve the formating of the information.

## Ethicals considerations

### Why it is matters

### Stakeholder analysis

### Raw Data

o `Nature of raw data include Categorical and numerical`

Categorical: the date for start, date for finish 

numerical: the stpes count 

o `Describe the process of data collection.`
Collection includes apple watch ,electrical trackers.


 
## Getting started

Short list of intructions for new collaborators to get up and running with the project.

Example list of commands:

- `$ git clone git@github.com/username/project.git`
- `$ cd ./project`
- `$ pip install`
- `$ jupyter lab .`

## Contributing

Intructions on how to contribute to the project. Consider having a `CONTRIBUTING.md` file in the repository.

## Project owner(s) & contact details

Contact details of the people who created and/or are maintaing the project.


## References
How Many Steps/Day Are Enough?

https://link.springer.com/article/10.2165/00007256-200434010-00001

How walking steps contributes reducing risk of diabetes.

Colberg, S. R., Sigal, R. J., Fernhall, B., Regensteiner, J. G., Blissmer, B. J., Rubin, R. R., Chasan-Taber, L., Albright, A. L., & Braun, B. (2010). Exercise and type 2 diabetes: The American College of Sports Medicine and the American Diabetes Association: Joint position statement. Diabetes Care, 33(12), e147–e167. https://doi.org/10.2337/dc10-9990

## License

Include licensing information. Consider having a `LICENSE.md` file in the repository.

[link]('google.com')

# 2022-DATA3406-CC05-Group1


- [Proejct description](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#proejct-description)

- [Group members and contracts](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#group-members-and-contracts)

- [Ethical Considerations](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#ethical-considerations)

  - [Purpose](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#purpose)
  
  - [Why it matters](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#why-it-matters)
  
  - [Stakeholder Analysis](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#stakeholder-analysis)
  
  - [Raw Data](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#raw-data)
  
- [Key files](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#key-files)


  - [Product notebook](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#product-notbook)
  
  - [Meeting minutes](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#meeting-minutes)
  
  - [Ethical analysis](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Ethical-consideration)
 
  - [Cognitive walkthrough](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Cognitive-walkthrough)
  
  - [Think aloud](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#think-aloud)
  
  - [Reflection on Group Process](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#reflection-on-group-process)

- [Individual Contribution](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/README.md#individual-contribution)
    





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

![ethical](https://media.github.sydney.edu.au/user/10750/files/684c348b-f6a7-44f3-8e22-95a5f232f5c8)


<br>

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







## Stakeholder analysis
![FiscalNote-managing-multiple-stakeholders](https://media.github.sydney.edu.au/user/10750/files/b96d0fa6-5b76-44df-aa08-ec711664f612)

`Students`
* Our research results are of direct help to students' physical health, because students can refer to our healthy step count standard to measure whether they are in a healthy state at all times. When students are at a lower step count level, they Will generate the belief to go out and exercise to become healthier


## Raw Data
<img width="165" alt="raw" src="https://media.github.sydney.edu.au/user/10750/files/00bc1956-6544-4724-98f2-fef79004f52c">


`Nature of raw data include Categorical and numerical`

* **Categorical**: Date.

* **Numerical**: Step counts.

* **Why the nature of data is needed, there are 3 important point which is to be able to distinguish between different kinds of data because their nature has
important implications for their reliability and for the sort of analysis to which they can be subjected.**

<br>

`Describe the process of data collection.`

* **Collection methods**: Apple watch ,Electrical trackers.

<br>

 `Describe aspects related to data ownership, data owners and data origin.`

* **Data ownership**: People who donated data in our class

* **Data owners**:  Our coordinator --- Judy Kay.

* **Date origin**: Our data is about step data for each day recorded by participants' activity trackers. Some trackers recorded the steps data seperated by time in hours or date. Most of data had got from Apple Health processed with a python script to convert the xml to csv.

<br>

`State any potential conflicts of interest.`

* **The data is mostly about the privacy of the data ownership, their privacy might be leak.Some data and result analyses by the data can be sensitive and Transparency,otherwise the data only for research use and not in a profit way.**

<br>

`Describe how you ensured anonymisation and reduced the risk of re-identification of data with the people and justify any actions taken (if your group collected data)`

* **First the data without any personal identity, So we do not know other information other than steps, Moreover, our sub-question is based on the aspect of the relationship between steps and temperature, healthy, rainfall, and seasons to research and analyses, those aspects does not attack personal identity, also our analyses all related to the outside factors which we have avoided to develop re-identification of data.**

<br>

`Describe how you have managed the data and will manage it at the completion of the project.`

* **To how we managed the data, we first use colab to explore the data and see the detailed information of the data, and simply do some data cleaning, with renaming drop missing values, Based on our driving question we process the data into a week-to-week form where we define the column week, steps. Then we use the data to do some analyses, and upload it into GitHub to protect the original data, otherwise, we also print out the data that has been cleaned and also upload it into GitHub, and we used it in the final product notebook.**

 
 
 # Key files

## Product notbook

[Link](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_product_notebook.ipynb)

## Meeting minutes

Our group act satisfyingly collaborative through the whole process. In the first few weeks we meet each other every Saturday discussing about the TPP, feedbacks and the progress of the assignment. WeChat group chat was established in the beginning to keep communication with each other. As a team we followed checkpoints of the assignment in time such that we could keep up with the pace. In week 8 all the team members did data cleaning separately and discussed different sub questions individually. In week 9 and week 10 we swapped different datasets within the group and applied the code on them. GitHub issues and wiki were constantly tracked where all the teammates can keep up with the progress. In week 12 we finished personal report and presentation and finally we aggregated everything for assignment2. During these two weeks we increased the frequency of meeting as well due to the tense of deadlines. In conclusion, it was a pleasure journey and we enjoyed the whole progress :)

## Cognitive walkthrough  [    (wiki)](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Cognitive-walkthrough)

| Advantage     | Improvement     |
| :-----------:  | :-----------: |
| 1. First, the significant impressive point is that we have a clear direction throughout the whole project, we have separated the job for each of the members in our group which lead to we have a great structure of readme in GitHub. while we have an outlook that has been designed before writing the readme file for the read for the audience to go through the detail with links for the key words and also provide some visualization to help read smoothly. | 1. Issue: The topic of the allocated issues are generally broad and there are no reflections after finishing each one. 
|2. Moreover, you can discover that our wiki with a clear process of work that our group members do, We divide the part which includes individual work, it includes each week how we process the project and with relative work links in GitHub. Wiki also supports group corporate work with an organized structure, you can find the group roles to find what each group member plays in the group.| 2. Stakeholder: Catering to the stakeholder analysis, basically we were targeting students, hence the stakeholders are not comprehensive which leads to an unsolid conclusion. 
|3. GitHub has been organized so that you can find the code or dataset of each gourp member and are willing to show the whole project to everyone that we own the ability to handle human-in-loop factor.|<br> 3. Collaboration: Overall, we had good cooperation with the group members. Despite this, we need to use GitHub and colab more proficiently in case of code docking. Sometimes we met a merge problem and we took so much time on rearranging them.   |


## Think aloud
<img width="324" alt="graph" src="https://media.github.sydney.edu.au/user/10750/files/d6a93774-781a-4ad6-8972-3ac329158d05">

Sub question:How does week-to-week data illustrates the probability of participate getting healthy?

Participant8

* [Yuxiang Ji](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Yuxiang-Ji#think-aloud)

* [Ran Sun](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Ran-Sun#think-aloud)

* [Lixin Mu](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Lixin-Mu#think-aloud)

* [De shi](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/De-shi#think-aloud)

* [Kuai Yu](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Kuai-Yu#think-aloud)

* [Pengyu Liu](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Pengyu-Liu#think-aloud)
## Reflection on Group Process

# Individual Contribution

`Ran Sun`

* **Issues**: [issue1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/32) [issue2](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/22) [issue3](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/18) [issue4](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/16) [issue5](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/20)

* **Variable**: [Modified dataset](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/modifydata.csv) for participant 05.

   - This dataset is pre-processed that filling the missing values (NaN) with 0, sorting the date in a ascending order and combining the counts in duplicate  date.
   
   - It includes two main variables `Date` in datetime data type  and `Count` in numerical data type.

* **Wiki page**: [Wiki](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Ran-Sun)

`Lixin Mu`

* **Issues**: [issue1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/24) [issue2](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/23) [issue3](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/29) [issue4](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/32) [issue5](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/20)

* **Variable**: [p2-data1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/p2-data1.csv) 

   - This dataset contains date and count as columns where pre-process has been done which missing values are filled and date was already in ascending order. Moreover, groupby method has been applied and outliers were deleted. 
   
   - It includes two main variables `Date` in datetime data type  and `Count` in numerical data type.
   
        [p2-data2](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/p2-data2.csv)
   
   - This data is the original copy of participant2's data.    
   
        [p2-data3](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/p2-data3.csv)
     
   - This data is similar to p2-data1 with one extra column to store a different type of date.

        [p2-data4](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/p2-data4.csv)
     
   - This data is also similar to p2-data1 with one extra column to store 0 and 1 for representing wether the participant is sedentary.

* **Wiki page**: [Wiki](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Lixin-Mu)

`Kuai Yu`

* **Issues**: [issue1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/5). [issue2](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/20). [issue3](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/23). [issue4](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/27). [issue5](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/32).

* **Variable**: [Pre-cleaned Data](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/P03.csv) for participant 3.
    - This dataset was pre-cleaned in previous weeks. 'NA' values were dropped and grouped by weeks. Steps' counts were summarised for each week.

    - THis dataset includes 2 variables. 'Start' is the date of weeks which in datetime data type, and 'Step (count)' is numerical data.

    - Two new colums were added for analysis. 'nth week' is the index of weeks which is factor. And 'diabetes' is binary data includes 'high risk' and 'low risk'. The cut-off value is 50000.

* **Wiki page**: [WiKi](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Kuai-Yu)

`Yuxiang Ji`

* **Issues**: [issue 1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/33). [issue 2](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/14). [issue 3](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/20). [issue 4](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/23). [issue 5](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/23)

* **Variable**: [Participant 08](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/Participant-08.csv) [ShiDe_cleaned_08.csv](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/ShiDe_cleaned_08.csv) [Weeks_and_steps_08.csv](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/Weeks_and_steps_08.csv)
    - My original dataset is the Participant 08. I used it in most of time to run my team mate's code.
    - The second data set is the cleaned participant 8 data. It is only for fitting De Shi's code.
    - The last dataset called Weeks_and_steps_08.csv. That is the cleaned dataset for Yuxiang's subquestion. Due to his sub-question has a step standard principle which is 700000 per week. So the data should be added a column to store 0 and 1 for representing wether the participant is sedentary.

* **Wiki page**: [Wiki](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Yuxiang-Ji)
 
 
`Pengyu Liu`

* **Issues**: [issue1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/25) [issue2](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/32) [issue3](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/31) [issue4](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/29) [issue5](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/24)

* **Variable**: 
 [p1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Process%20notebook/Pengyu%20Liu/Dataset/final%20for%20p1.csv) 
 [for Deshi](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Process%20notebook/Pengyu%20Liu/Dataset/final%20for%20deshi.csv) 
 [for kuaiyu](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Process%20notebook/Pengyu%20Liu/Dataset/final%20for%20kuaiyu.csv) 
 [for lixin mu](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Process%20notebook/Pengyu%20Liu/Dataset/final%20for%20lixinmu.csv) 
 [for ransun](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Process%20notebook/Pengyu%20Liu/Dataset/final%20for%20ransun.csv) 
 [for yuxiang ji](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Process%20notebook/Pengyu%20Liu/Dataset/final%20for%20yuxiangji.csv) 
 

   - The p1 is my own data for participant 01 , and use it to run other's code.
   
   - The other 5 datasets are all the cleaned up Participant data is used to adapt the code of other players and implement the subquestions they explore

* **Wiki page**: [Wiki](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/Pengyu-Liu)

`De shi`

* **Issues**: [issue1](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/15) [issue2](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/32) [issue3](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/31) [issue4](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/29) [issue5](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/issues/24)

* **Variable**: 
* initial dataset for [participant07](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/Participant-07.csv),Second use dataset for [participant07_clean](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/Participant07_clean.csv),Last dataset for [participant07_new](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/blob/main/Final%20product%20notebook/Final_dataset/Participant07_new.csv)

   - The participant07 is my orginal dataset , and use it to run the whole data, which has column about date(Start&Finish) and steps count.
   
   - The participant07_new &participant_clean which are the dataset haven been clean and include date and steps, date are seprated into week-to-week form.

* **Wiki page**: [Wiki](https://github.sydney.edu.au/rsun5771/2022-DATA3406-CC05-Group1/wiki/De-shi)






# References
How Many Steps/Day Are Enough?

https://link.springer.com/article/10.2165/00007256-200434010-00001

How walking steps contributes reducing risk of diabetes.

Colberg, S. R., Sigal, R. J., Fernhall, B., Regensteiner, J. G., Blissmer, B. J., Rubin, R. R., Chasan-Taber, L., Albright, A. L., & Braun, B. (2010). Exercise and type 2 diabetes: The American College of Sports Medicine and the American Diabetes Association: Joint position statement. Diabetes Care, 33(12), e147–e167. https://doi.org/10.2337/dc10-9990


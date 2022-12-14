# SCS Assessments

- **MixPanel_Assessments** notebook upload the csvs files with the original data to a pandas dataframe,
process it and generate new dataframes filtering and arranging data of interest, save each generated dataframe to a new csvs file.

- **MixPanel_Assessments_Analysis** notebook retrives csvs files generated on previous notebook, upload them into pandas dataframe,
print and visualize some information of interest.

- **Tables** notebook, prints tables with statistics of interest.

Note: A folder named *csvs* must be created locally. Inside of it there must be two folders:

- *aggregated*, with the original data in csv format
- *processed*, new generated csvs files will be save to this folder


### Questionnaire (25 items)

#### PHQ (Patient Health Questionnaire for Anxiety and Depression)
* Item 1: suicidality
    + **phq_suicide**

* Items 2, 3: gad2 anxiety
    + **phq_gad_1**
    + **phq_gad_2**

* Items 4, 5: phq2 depression
    + **phq_dep_1**
    + **phq_dep_2**

#### wemwbs

* Items 6 to 19:
    + **wemwbs_1**
    + **wemwbs_2**
    + **wemwbs_3**
    + **wemwbs_4**
    + **wemwbs_5**
    + **wemwbs_6**
    + **wemwbs_7**
    + **wemwbs_8**
    + **wemwbs_9**
    + **wemwbs_10**
    + **wemwbs_11**
    + **wemwbs_12**
    + **wemwbs_13**
    + **wemwbs_14**

#### Retired

* Item 20: "Are you retired or choose not to have a job for reasons unrelated to your mental health?"
    + **retired**

#### WSAS

* Items 21 to 25:

    + **wsas_1**: "Because of my mental health, my ability to work is impaired."
    + **wsas_2**: "Because of my mental health, my home management (cleaning, tidying, cooking, looking after home or children, paying bills) is impaired."
    + **wsas_3**: "Because of my mental health, my social leisure activities (with other people) are impaired."
    + **wsas_4**: "Because of my mental health, my private leisure activities (done alone, such as reading, gardening, collecting, sewing, walking alone) are impaired."
    + **wsas_5**: "Because of my mental health, my ability to form and maintain close relationships with others, including those I live with, is impaired."


### Answers

*  Items 1 to 5 (PHQ):
    + English:
        - 'Nearly every day': 3
        - 'More than half the days': 2
        - 'Several days': 1
        - 'Not at all': 0
        - 'undefined': nan
    + French:
        - 'Presque tous les jours': 3
        - 'Plus de la moitié des jours': 2
        - 'Plus de sept jours': 2
        - 'Plusieurs jours': 1
        - 'Jamais': 0

* Items 6 to 19 (wemwbs):

* Item 20 (retired):
    + 'false': 0
    + 'true': 1
    + 'undefined': nan

* Items 21 to 25 (WSAS):
    + 0 not at all to 8 very severely (impaired)

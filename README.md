# HH_project

-    [1 Projects description](https://github.com/mLiverinova/HH_project/blob/main/README.md#project_description)
-    [2 What case is solving](https://github.com/mLiverinova/HH_project/blob/main/README.md#what-case-is-solving)
-    [3 Data information](https://github.com/mLiverinova/HH_project/blob/main/README.md#data-information)
-    [4 Stages of the project](https://github.com/mLiverinova/HH_project/blob/main/README.md#stages-of-the-project)
-    [5 Result](https://github.com/mLiverinova/HH_project/blob/main/README.md#result)

#### Project_description
This project contains the preparation, processing and analysis of the HeadHunter database

:yellow_circle:[To contents](https://github.com/mLiverinova/HH_project/blob/main/README.md#сontents)

#### What case is solving
It is necessary to explore the data structure, process the data and transform it into a form accessible for analysis. You also need to analyze applicants on various grounds (age, work experience, city, and so on)

#### Data information 
The source database contains the following columns: "Пол, возраст", "ЗП", "Ищет работу на должность:", "Город, переезд, командировки", "Занятость", "График", "Опыт работы", "Последнее/нынешнее место работы", "Последняя/нынешняя должность", "Образование и ВУЗ", "Обновление резюме", "Авто".

#### Stages of the project
1. Data transformation: extracting key information about education, separating the "Пол, возраст" column into "Пол" and "Возваст", bringing work experience to a single unit of measure (month), determining readiness for business trips and relocations in a boolean format, categorizing the city of residence, creating columns , signaling the applicant's readiness to work on various schedules, the conversion of the requested salary to rubles.
2. Data dependency analysis.
3. Emission cleaning, pass processing.

#### Result
The result is a processed table suitable for data analysis, as well as dependency graphs and their analysis.


:yellow_circle:[To contents](https://github.com/mLiverinova/HH_project/blob/main/README.md#сontents)

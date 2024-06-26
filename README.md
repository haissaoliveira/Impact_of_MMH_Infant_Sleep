# Impact_of_MMH_Infant_Sleep
This dataset provides insight into an important question, the influence of maternal mental health difficulties on infant sleep during the first year postpartum. Data was collected from 410 postpartum mothers and their babies aged 3 to 12 months. A wide range of variables were included, such as number of participants, information on parental type and age, week of child gestation, marital status, education. In addition, measures were recorded of several maternal mental health symptoms (including depression, anxiety, and birth-related post-traumatic stress disorder), as well as factors affecting infant sleep (including baby sex, perceptions of temperament, and method for putting children to bed).
Firstly, the data was analyzed in Python, where I eliminated NaN and regrouped columns with data that had been separated. I used Matplolib to visualize important targets in the dataset and see how they were distributed, and only then make a correlation between two groups:
mental_health = ['sex_baby1','epds', 'had', 'cbts']
infant_sleep = ['night_awakening_number_bb1', 'how_falling_asleep_bb1'].
Using K-Means Clustering we visualize how different levels of anxiety, depression and birth trauma are associated with children's sleep quality, identifying groups of similarity within the data.
Even with the impact that maternal mental health has on babies' sleep quality, it is not as negative an impact as expected, beyond what is expected in babies up to one year old.
Viewing the same data in Tableau, it is clear that even women with high levels of psychological disorders, the direct impact is not high, therefore women with high levels of disorders may still have babies who wake up less at night than those with lower levels and greater support network, in this case women who are in a relationship.
Datasource: https://zenodo.org/records/5070945#.Y8Oq4NJBwUE
Dataset_maternal_mental_health_infant_sleep.csv
This dataset is related to: Sandoz, V.; Lacroix, A.; Stuijfzand, S.; Bickle Graz, M.; Horsch, A. Maternal Mental Health Symptom Profiles and Infant Sleep: A Cross-Sectional Survey. Diagnostics 2022, 12, 1625. https://doi.org/10.3390/diagnostics12071625.  

Tableau Public Link : https://public.tableau.com/views/ProjectMMH/Dashboard2?:language=pt-BR&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

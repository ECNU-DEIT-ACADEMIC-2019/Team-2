# team0
templated team repository
## 7	Technology applying  
&nbsp;&nbsp;&nbsp;&nbsp;The APP mainly uses location technology, speech recognition technology, deep learning technology, big data technology, and mobile development technology.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part7.png" height="360" width="604" > </div> 
####  （1）Location technology
&nbsp;&nbsp;&nbsp;&nbsp;The location technology is mainly embodied in the app's ability to detect the user's location in real time and automatically provide corresponding scenes for the user based on the location. If the user has needs or interests, the user can learn the scene. 
&nbsp;&nbsp;&nbsp;&nbsp;As an informal oral English learning APP, the general learning process is that learners find appropriate learning resources according to their own needs and use learning resources for learning. If the resources cannot meet their needs, learners will find more appropriate resources again. However, a very important issue is how learners think about what kind of resources they need. In many cases, learners will not be aware of what they could have learned. Special reminders will weaken the function of technical services and enhance the visibility, making learners pay more attention to peripheral learning tools or environmental factors instead of learning content.
&nbsp;&nbsp;&nbsp;&nbsp;With the introduction of positioning technology, learners can focus on the task of oral learning more smoothly and naturally without additional cognitive burden. Therefore, this APP combines the ubiquitous learning theory, and makes use of location technology, blending oral English learning in learners' daily life, and even its current environment. This makes the oral English learning and learners encounter problems or the real scene a combination, enables learners to study at any time, any place, and better reflect the self-orientation of learning.

####  （2）Speech recognition technology
&nbsp;&nbsp;&nbsp;&nbsp;Speech recognition technology is mainly embodied in the APP's ability to detect and recognize users' pronunciation of English words, sentence reading and dialogue information, and score and give feedback based on their pronunciation. At present, Baidu speech technology, JD speech recognition technology, iflytek speech recognition technology and other speech recognition technology have been developing rapidly, and their accuracy and timeliness have reached a good level.
&nbsp;&nbsp;&nbsp;&nbsp;As an oral practice APP, user's pronunciation recognition is a very important function. Through speech recognition technology, users can transfer their pronunciation audio files to the database, which will automatically analyze and compare, point out the defects of their accents, and correct them in time. Speech recognition technology allows learners to learn anywhere, anytime, without relying on teachers or partners.
&nbsp;&nbsp;&nbsp;&nbsp;Through this technology, learners can choose to interact with the machine, and the system will automatically recognize its pronunciation and give feedback, saving human and material resources. And this automatic grading system can help students who are afraid to open their mouths in front of other people to practice. At the same time, the APP has added the real person matching dialogue mode of specific scenes, and the high accuracy, high speed recognition and the speech recognition technology that supports customized optimization can satisfy the demand for timely feedback.

####  （3）Deep learning technology
&nbsp;&nbsp;&nbsp;&nbsp;Deep learning technology is mainly embodied in the ability to predict where you might want to go, and deep learning technology can also be used to generate the human-computer conversation.
&nbsp;&nbsp;&nbsp;&nbsp;Before the deep learning technology, the evaluation process of oral English APP was generally to randomly select speech samples from the predetermined speech training library and follow them according to the standard pronunciation of the samples. After the emergence of deep learning technology, in the process of learners' pronunciation, the system can extract the information of learners with high scores and the standard characteristic information for comparison, so as to constantly modify and improve.
&nbsp;&nbsp;&nbsp;&nbsp;As an English-speaking practice APP, the platform needs to record learners' preferences and habits, automatically predict and recommend the possible learning scenarios in the next stage according to learners' psychological hobbies and behavioral habits, and provide them with seasonal or phased services, as well as recommendation services for interested content.

####  （4）Big data technology
&nbsp;&nbsp;&nbsp;&nbsp;Big data technology is mainly embodied in three aspects: first, it records the most frequently visited places by learners through big data technology, and recommends them according to the times and dates of visits. Second, according to the rank of the learner, the system can customize it to match the real person. Third, in the scene dialogue, if there are words or sentences in the collection of the incorrect words, it will be provided to be remembered again.
&nbsp;&nbsp;&nbsp;&nbsp;With the development of Internet, learners' behaviors on the network platform can be recorded. This kind of big data can help us better understand human behavior and psychology and better understand objective laws after certain analysis. For example, learners' learning time, learning content and learning path on the Internet can be taken as data to identify learners' learning style and learning status.
&nbsp;&nbsp;&nbsp;&nbsp;Through big data analysis, the APP can record learners' learning records and scene search, and develop personalized learner service experience that meets learners' actual needs. At the same time, the personalized recommendation based on big data technology can select the content suitable for learners' English level, push the key and difficult knowledge, and match the characters of the same level according to their English level for game dialogue, making oral English learning more accurate and meaningful.

####  （5）Mobile development technology
&nbsp;&nbsp;&nbsp;&nbsp;In addition, the app also uses other mobile development technologies, such as communication technology, algorithms which all contribute to the normal operation of the application.

## 8 Learning Analytic
&nbsp;&nbsp;&nbsp;&nbsp;In this section, we'll detail how to apply xapi or equivalent techniques to our design to get to the user's data, as well as what interface operations get to what data.

### 8.1 What data do you need? 
&nbsp;&nbsp;&nbsp;&nbsp;In this APP, we need to collect the data of the places frequently visited by learners to facilitate the system to automatically recommend; We need to collect data on where learners are likely to go, so as to facilitate the active prediction of the scene that learners want to learn. We need to collect data on learners' oral English level to help the system automatically recommend appropriate dialogue scenes for them and match real people of the same level for dialogue. We need to collect data on learners' learning priorities and difficulties so as to train and learn them more pertinently. We need to obtain data on learners' learning habits to adapt to their learning styles. The specific data categories can be shown in table 8-1.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8.png" height="360" width="604" > </div>  
  
&nbsp;&nbsp;&nbsp;&nbsp;The following figure (Figure 8-1) lists several sources for each type of data. The places that learners often to go include the time, place, numbers and frequency of their visits. The places that learners may go include the scenes they collect and the places they often visit. Learners' speaking level includes the overall score, ranking and scoring of each test. Learners' learning difficulties and key points include frequently mispronounced words or sentences, favorite words or sentences, and the time and scene of looking up words. Learners' learning habits include when they will study every day, how long they will study every time, the play model they often choose, how many times they click on the path, and how many times they talk to their contacts.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-1.png" height="360" width="604" > </div>  
  
### 8.2 How will you capture that data?
&nbsp;&nbsp;&nbsp;&nbsp;After the APP development completed, the database connection will be established, and the external database will show some relevant information, these data can be obtained from an external database. The APP itself also has the function of storage at the same time, a part of the data also can come from in the storage structure of the APP itself. The collection methods for each data are shown below.
#### (1) Places learners often go
&nbsp;&nbsp;&nbsp;&nbsp;The external database creates a table of "date - time - place - times - frequency of the last week”. Every time you arrive at a new location and open the map scene provided by the APP, the external database will get the corresponding data, including the date, time and location of this time, and store it. "places you often go" on the home page is sorted according to this number. See figure 8-2.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-2.png" height="360" width="604" > </div>  
  
#### （2）Places learners might go
&nbsp;&nbsp;&nbsp;&nbsp;This part of data is also obtained from the external database, which has a table of "scene collection". When learners click on the table of "scene collection", the tag of the scene will be transferred to the corresponding table. The "guess you want to go" on the home page will be pushed based on the data in the table. Meanwhile, the system uses deep learning algorithm to calculate the information in the table of "places you often go", so as to recommend the scene of "guess you want to go". See figure 8-3.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-3.png" height="360" width="604" > </div>  
  
#### （3）Learner's level of oral English
&nbsp;&nbsp;&nbsp;&nbsp;The scores obtained from the dialogue between the learner and the machine, and the conversation between everyone. And these scores will be summarized into a total grades. The grades of the total score determines the level of the learner, from which comes the data of the learner's oral English level. See figure 8-4.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-4.png" height="360" width="604" > </div>  
  
#### (4) Learning difficulties and key points
&nbsp;&nbsp;&nbsp;&nbsp;When learners mispronounce a word or sentence, the internal database of the APP will record and give feedback. When the number of times reaches a certain limit, the word or sentence will be transferred to the external database and marked as a learning difficulty. At the same time, the time and scene of learners' checking words in the process of using the APP will also be recorded and sent to the database, which will be reflected in "collections". See figure 8-5.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-5.png" height="360" width="604" > </div>  
  
#### (5) Learning habits of learners
&nbsp;&nbsp;&nbsp;&nbsp;After the learner completes the learning of a scene, the system will upload the learning start time, the learning end time, the selected mode, the number of prompts clicked in everyone mode and the number of conversations with friends in the learning process to the external database to obtain the learning situation of each learner. Then through big data analysis technology, we can understand the learning interests and habits of learners. See figure 8-6.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-6.png" height="360" width="604" > </div>  
  
### 8.3 How will you structure the data?
&nbsp;&nbsp;&nbsp;&nbsp;In this APP, xAPI documents need to be defined in such aspects as places learners often go, places learners might go, learner's level of oral English, learning difficulties and key points and learning habits of learners. The following table respectively illustrates the xAPI statements for each kind of data.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-7.png" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-8.png" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-9.png" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-10.png" height="360" width="604" > </div>  
  
## 9 UX evaluation  
### 9.1 The questionnaire 
### 9.2 Confidence_Intervals Sheet
### 9.3 Answer_Distributions Sheet
### 9.4 Inconsistencies
### 9.5 Sample_size
### 9.6 Scale_Consistency
&nbsp;&nbsp;&nbsp;&nbsp;Judgment criteria: there is no unified standard to determine how big the value of the reliability coefficient should be. However, it is generally believed that if the reliability coefficient is above 0.9, the reliability is very well. The reliability coefficient is acceptable at 0.8-0.9. At 0.7-0.8, the scale does not lose its value. But if the coefficient below 0.7 indicates a change. In this analysis, the scale was judged to have reliability based on the alpha value greater than 0.7.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/wu1.JPG" height="319" width="904" > </div> 
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/wu2.JPG" height="319" width="904" > </div> 
&nbsp;&nbsp;&nbsp;&nbsp;Alpha coefficient and Guttmans Lambda2 coefficient can both be used to measure the reliability of the scale, and there is little difference in this analysis. In the six dimensions, the two coefficients above 0.9 of attractiveness, stimulation and novelty indicate that the attractiveness stimulation and novelty scale has a high reliability. the perspicuity alpha and Guttmans Lambda2 value are both 0.87, which indicates that the reliability of problems in perspicuity dimension is acceptable. The alpha and lambda2 values of efficiency and dependability are all above 0.7, which proves that the scale of efficiency and dependability does not lose its value. Therefore, Therefore, the whole scale has a certain credibility.
### 9.7 Benchmark
&nbsp;&nbsp;&nbsp;&nbsp;In the chart, we can see data from 18,483 people studied in 401 studies concerning different products (business software, web pages, online stores, social networks). It can be used as a benchmark and compared with the questionnaire data, and then the grade of qushuojingying relative to other products can be obtained.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/wu3.JPG" height="240" width="903" > </div> 
&nbsp;&nbsp;&nbsp;&nbsp;As can be seen from the mean line of the reference graph that the mean value of the six dimensions of qushuojingying application are all above 1.4, which is above the middle level. Attractiveness (mean=1.84), stimulation (mean=1.76) and novelty (mean=1.73) are all rated as excellent level. Efficiency (mean=1.73) and dependability (mean=1.63) are in good level. And the perspicuity (mean=1.43) is the above average level. In this way, it can be seen that the performance of qushuojingying application in Attractiveness, stimulation and novelty are recognized with customers. The performance of efficiency and dependability is good. But perspicuity in the qushuojingying applacation needs to be improved.
### 9.8 Main result

## 10 final design
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/own.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/two.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/three.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/four.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/five.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/six.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/seven.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/eight.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/nine.PNG" height="360" width="604" > </div>  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/ten.PNG" height="360" width="604" > </div>  
  

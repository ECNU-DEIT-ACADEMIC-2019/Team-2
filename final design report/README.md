# team2
templated team repository
## abstract
&nbsp;&nbsp;&nbsp;&nbsp; With the rapid development of technology, more and more people choose to learn English on mobile phone. In the Baidu index, we can see that the search of the English speaking learning software has a high popularity. We did an interview and a questionnaire survey. It is found that users’ needs for the spoken English application include pronunciation diagnosis, word searching, and common expression learning. Based on some technologies such as deep learning technology, location technology, Qushuojingying application can satisfy the needs of the users and help to increase users' interest in learning English and improve users’ spoken English.

## 1 introduction
&nbsp;&nbsp;&nbsp;&nbsp; With the rapid development of speech recognition technology, spoken English learning software cut the price of learning English, and there are no geographical and time restrictions, which meets the requirements of learners to practice speaking at any time and place. It is favored by learners. More and more learners have chosen to use fragmented time to learn on their mobile phones, instead of sitting in front of a computer or a classroom for a long time. However, the mobile phone spoken application market is chaotic, and the phenomenon of good and bad mixed together is serious. A well-designed and fully-functional spoken language application is a good teacher and friend for students, and a good assistant for teachers. Inferior software will waste time and money, even make learning efficiency down. So we decide to develop an application which can satisfy learners’ need.

&nbsp;&nbsp;&nbsp;&nbsp; Qushuojingying is an application that can help you improve your spoken English. The product positioning of Qushuojingying revolves around spoken English. There are two modes of oral speaking which are human to human mode and man to machine mode. In the human to human mode, the user should choose the number of spoken partner and then choose the character he wants in the scene. The partner ’level is as the same as you. Then the user can conduct the spoken dialogue according to the prompts given by the application. In the human to machine mode, it is a simulated dialogue practice between user and application. The user needs to speak the sentences given by the application, and the application will intelligently score based on the user's speaking performance. This application based on U-learning theory, Users can learn anywhere, anytime. If the user walks into a cafe shop, the scene recommendation given by the application is the café shop. The user can learn the words and sentences related to the cafe, and then select a mode to learn.

## 2 Customer Needs Assessment
&nbsp;&nbsp;&nbsp;&nbsp; The Baidu Index is a data sharing platform based on Baidu's massive netizen behavior data. It can research keyword search trends, observe changes in netizen needs, monitor media public opinion trends, and locate digital consumer characteristics. In the Baidu index, the search is conducted using the English speaking learning software as a keyword, and it can be seen that the search of the English speaking learning software has a high popularity.

 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part2-1.png" height="360" width="604" > </div>

 <div align="center">Figure 2.0.1. Baidu Index Search Results1</div>


&nbsp;&nbsp;&nbsp;&nbsp; From the perspective of urban areas in the Baidu Index, the search sources are mainly Shanghai, Beijing, and Shenzhen. This shows that current oral English learning still has market demand.
 
 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part2-2.png" height="360" width="604" > </div>

 <div align="center">Figure 2.0.2. Baidu Index Search Results2</div>
 
&nbsp;&nbsp;&nbsp;&nbsp; For the initial product purpose, an interview outline was designed, including two questions, question one: "How do you evaluate the existing app for practicing spoken English?" Question two: "What functions do you think the spoken app should have?" Using online interviews, 6 potential customers were interviewed, keywords were extracted from the interview results to create a word cloud, and an initial customer demand list was obtained.As can be seen from the word cloud, including real-life video conversation, intelligent speech recognition, situational practice, correct pronunciation, repeated listening and practicing follow-up reading are the functions and elements that current users think are particularly needed for oral English learning software.
  
 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part2-3.png" height="360" width="604" > </div>

 <div align="center">Figure 2.0.3. Customer Needs Word Cloud</div>
  
&nbsp;&nbsp;&nbsp;&nbsp; By summarizing the word cloud, you can extract the twelve dimensions about the needs of spoken English learning software, which are live video dialogue, real situation practice, pronunciation diagnosis and correction, checking words, watching videos, learning common expressions, American and English pronunciation, setting speed, games, dubbing, study groups and teacher training
  
 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part2-4.png" height="360" width="604" > </div>

 <div align="center">Figure 2.0.4. Initial Customer Needs List Obtained from Interviews and Observations</div>
  
&nbsp;&nbsp;&nbsp;&nbsp; For each requirement in the initial customer demand list, a demand level questionnaire is produced, and the statistical results form a customer demand list with weighting factors.From the results, we can see that the average score of each part is 3.5 points, real situation practice is 4.2 points, pronunciation diagnosis and correction is 4.5 points, checking words is 3.8 points, watching videos is 3.5 points, and learning common expressions is 4.2 points. The score is 4.1 for American and English pronunciation, 4.3 points for setting speed, 2.9 points for games, 3.3 for dubbing, 3.1  points for study groups and 3.4 points for teacher training.
  
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part2-5.png" height="360" width="604" > </div>

 <div align="center">Figure 2.0.5. Customer Needs List (With Weighting factors)</div>
  
### 2.1 Weighting of Customer Needs

&nbsp;&nbsp;&nbsp;&nbsp; Analytic Hierarchy Process（AHP）analysis of 12 dimensions of live video dialogue, real situation practice, pronunciation diagnosis and correction, checking words, watching videos, learning common expressions, American and English pronunciation, setting speed, games, dubbing, study groups and teacher training , It can be concluded that the weights are in turn from pronunciation diagnosis and correction, setting speed, real situation practice, learning common expressions, American and English pronunciation, word search, live video conversation, watching videos, dubbing, teacher training, games and Dubbing.
 
 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part2-6.png" height="360" width="604" > </div>

 <div align="center">Figure 2.1.1. Example of AHP Pair wise Comparison Chart to Determine Weighting for Main Objective Categories</div>
 
## 3 Revised Needs Statement and Target Specifications

&nbsp;&nbsp;&nbsp;&nbsp; After multiple interviews and opinions from various groups and teachers, our product has undergone 2 iterations, from the initial word learning, sentence structure learning, oral interaction, and test evaluation to new word query after the first modification Functions and English-Chinese translation functions, and the second modified positioning push function, as well as some shortcuts and functions designed to optimize the user experience, such as favorites. Fully meet the needs and suggestions of users in the previous survey.
 
 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part3-1.png" height="360" width="604" > </div>

 <div align="center">Figure 3.0.1. Customer requirements revision process</div>

## 4 External search
&nbsp;&nbsp;&nbsp;&nbsp; There are many spoken English applications on the market, but they all have certain limitations, so we decided to develop this application. The spoken applications on the market are as follows.
### 4.1 Liulishuo&Qushuojingying
&nbsp;&nbsp;&nbsp;&nbsp; Firstly, the Liulishuo is very famous in spoken English applications. Users can add personalized lessons according to their interests, and learn the lessons through the challenge mode. There are many courses and many role-playing in this application, the user practice speaking by following the conversation. The users will earn gold coins based on the score of the follow-up recording. In addition, the app also has an English proficiency test, which can locate and evaluate your English proficiency. This application also has a real person-matched dialogue, but both of you should speak the specified sentence, which cannot have freedom to speak what you want to speak. But this application also has drawbacks. First of all, in the context of dialogue practice, it is not possible to choose a character, and secondly, there is no real partner matching dialogue, which cannot simulate real situations well.

 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-1.png" height="360" width="604" > </div> 

&nbsp;&nbsp;&nbsp;&nbsp; As you can see, in Qushuojingying application, you can select the character which you like to simulate. If you want to simulate a waiter in a restaurant, you can simulate the tone and intonation of the waiter as you like. And also you can practice with your real spoken partner which can simulate real-life scenes perfectly. You can say what you want to say, your partner will give you a good respond which is closely related to your conversation.
### 4.2 Shanbay & Qushuojingying
&nbsp;&nbsp;&nbsp;&nbsp; Secondly, this application is called Shanbay spoken English whose interface is clean and tidy. It is the same as Liulishuo, the user can follow the conversation that the application provide. And the application will give the user a score based on their performance. Also there are many courses and many role-playing in this application just like Liulishuo. But this application pay more attention to intonation. There is no doubt that it can train our tone well. In addition, there is a Shanbay spoken story section, this section is really very interesting. This section will provide you a story scene, you can simulate the character in the story, you can't help learning. It is helpful for the pronunciation and intonation of spoken English. The application’s first disadvantage is that there is no real person-matched dialogue. Another disadvantage is that story scene is limited and charge for the customers which is intolerable. 
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-2.png" height="360" width="604" > </div> 
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-3.png" height="360" width="604" > </div> 
&nbsp;&nbsp;&nbsp;&nbsp; As you can see, based on your interest, you will be personally recommended scenes. If you used to choose the library scene before, you will also be recommended the library scene next time. The festival theme will be intelligently provided according to the time. You can select to the New Year theme scene because it is close to the New Year. Based on your location, you will be recommended for your location related scenes. You can study anywhere, anytime. There is a greater possibility that you will use the dialogue in the real world.

### 4.3 Fun dubbing & Qushuojingying
&nbsp;&nbsp;&nbsp;&nbsp; Fun dubbing is mainly learned by dubbing movies and TV shows. You can choose the video you like to dub, listen to it one by one, imitate, and repeat it until you are satisfied. In addition, you can see other people's excellent dubbing works. At the end of the whole video, you will have a sense of accomplishment. Great progress was made in imitating the characters in the play. The application is mainly based on imitation for video dubbing, but it does not involve the simulation of real scenes. It is only helpful for the pronunciation and intonation of spoken English. Another disadvantage is that you can repeat the conversation, but you cannot get a score of the follow-up recording until you pay for it, which can’t help you to judge whether the performance is good or not. And if you like the sentence that appears in the movie, you can’t add to your favorites. 
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-4.png" height="360" width="604" > </div> 
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-5.png" height="360" width="604" > </div>
&nbsp;&nbsp;&nbsp;&nbsp; As you can see, in Qushuojingying application, you can repeat the conversation and get a score based on your performance. You can know your progress well. And if you like some sentences, you can add to your favorites. The review will be convenient. The real scene will bring you to achieve an immersive experience and not just to imitate for the movie.

### 4.4 Mofunshow & Qushuojingying
&nbsp;&nbsp;&nbsp;&nbsp; The Mofunshow is also learned by dubbing movies and TV shows. starting from follow-up imitation, and also has a professional oral assessment like Liulishuo, but the application has many disadvantages. The first is that there are relatively few dubbing resources compared to fun dubbing. The dubbing resources of the Mofunshow is not a complete movie fragment. It is difficult to satisfy different users’ need. Secondly, the classification of the sound resources allocated by the Mofunshow is not completely accurate. Some difficult movies and TV shows recommendations appear in the resources of primary level classification, which brings learning difficulties to primary level users. Thirdly, the software's sentence segmentation is not precise enough, the pronunciation of some sentences have more content, or some are missing. Finally, you only can add the whole movie fragment into favorites but can’t add a sentence into favorites.
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-6.png" height="360" width="604" > </div>
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-7.png" height="360" width="604" > </div>
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part4-8.png" height="360" width="604" > </div>
&nbsp;&nbsp;&nbsp;&nbsp; As you can see, in Qushuojingying application, you can pick up many scenes to learn and there are many topics in every scene. You can add the sentences into your favorites, which increase usage in daily life. You can match your partner depends on your spoken level, you will not feel yourself inferior.

### 4.5 Application restrictions
&nbsp;&nbsp;&nbsp;&nbsp; This application is based on a mobile phone system and cannot be used on a computer. In addition, the product positioning of this application is oral learning, so it has limitations in other aspects of English learning, such as word recitation or listening practice.


## 5	The KIEBIE analysis of you learning platform 

  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part5-1.jpg" height="360" width="604" > </div> 
  
&nbsp;&nbsp;&nbsp;&nbsp; Our oral English learning platform named “趣说精英”is a mobile application. This platform try to provide users an ubiquitous and immersive learning experience to practice their pronunciation, grammar, situational conversation and daily dialogue. the detail information about our platform would be illustrated based on mainly key factors, which is KIEBIE analysis.

####  （1）Environment 
&nbsp;&nbsp;&nbsp;&nbsp; Users can use our application with their smart phone by download it from app store. We design this platform as a mobile app, because the most significant feature of our platform is ubiquitous. Nowadays, almost everyone all over the world have a smart phone as a necessary social media tool. It means, smart phone is the best choice for users to send message or get real time information from their surroundings no matter where they are, or what they are doing.
####  （2）Knowledge，Skills，Attitude
&nbsp;&nbsp;&nbsp;&nbsp; The main function of our platform is practicing user’s spoken English. It need to be mentioned that, so many people including students or working stuff are not willing to speak with foreigner in English. According to our observation and some interviews, the reason are showed as they are lack of confidence to speak out, and they don’t have good chance to practice their spoken English in a real word situation. In addition, there are some kind of people who are good at writing or listening, but need to improve their quick reaction in speaking.

&nbsp;&nbsp;&nbsp;&nbsp; Based on the upon evidence, it is necessary to design and develop a kind of English learning platform which include the knowledge of vocabulary, sentences and pronunciation of some specific context and real word situation. For example, in a café situation, users need to learn related vocabulary like “美式咖啡”,“卡布奇诺”etc to create a sentence like “ I would like to drink a cup of Americano coffee.”  All of this basic knowledge is essential for users to make a conversation with other people based on real situation. (figure5-2)

&nbsp;&nbsp;&nbsp;&nbsp; In addition, we are going to improve user’s speaking skills and problem solving skills by creating real world context and synchronous online chatting model. As for the attitude, this platform can improve user’s confidence and interest in speaking English and chat with other people in English.

  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part5-2.jpg" height="360" width="450" > </div> 
  
 ####  （3）Behavior and mental process &status
&nbsp;&nbsp;&nbsp;&nbsp; Our platform refers to learning behavior like listening, speaking, translating, sending message, thumbs up, sliding left and right, pressing to speak, searching, opening location, uploading pictures and files. Adding new friends etc.

&nbsp;&nbsp;&nbsp;&nbsp; Firstly, in human – machine learning model, this platform can measure user’s learning outcome by giving an in-time score which include the accuracy of pronunciation, vocabulary, listening level and accomplishment. At the same time, platform would give an intelligent reflection according to user’s performance.

&nbsp;&nbsp;&nbsp;&nbsp; Secondly, our platform also give users an ranking grade which can be found under the function of personal account. This ranking grade can give users a visible comparison with other people about their ranking position and ranking level, which include bronze, silver, gold, diamond. The ranking grade would be higher with more and more practice and learning.

 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part5-3.jpg" height="420" width="300" > </div> 
 
  ####  （4）Interaction
&nbsp;&nbsp;&nbsp;&nbsp; Interactions would happen as long as users open this application in their smart phone. 
if users open their location identification, then they would receive an message from system to ask user if he or she want to start ubiquitous learning. If not, then user can choose his favorite situation to learn. For example, the café situation.

&nbsp;&nbsp;&nbsp;&nbsp; Then, user can start their interaction with our platform by learning or listening situation-based vocabulary and useful statement. If he want, he can also click “heart” image to add into collections for future review.Furthermore, user can click practice to start their real world spoken English practice. Which include human-human interaction and human-machine interaction. In the human-human model, user can create an online synchronous chatting room to start conversation with different users. In this chatting room, he can send voice message, upload image and files, add partner as a friend. In human-machine model, user can interact with machine by completing a pre-designed dialogue. 
  ####  （5）Experience
&nbsp;&nbsp;&nbsp;&nbsp; This application was designed to improve user’s English speaking skill. The strategies for good performance need to attract user’s attention, and then improve their interest and motivation to learn and practice.

&nbsp;&nbsp;&nbsp;&nbsp; User’s experience would be acted as they can pronounce the vocabulary accurately by listening to standard pronunciation, express ideas more quickly by day-by-day practice and guidance , chat with other users or computer more fluently and confidently, so that they can improve their spoken English more easily. In addition, with the influence of reflection from our platform and another user, user can find their existing problems more directly, user can find the difference between other people more clearly by noticing ranking grade. 

&nbsp;&nbsp;&nbsp;&nbsp; All in all, user can improve their learning outcome and spoken English by using our platform.

 ####  （6）Interact Object
&nbsp;&nbsp;&nbsp;&nbsp; As we all know, speaking can happen face to face or online when people talking to real human. Online chatting can help them get connected more easily. So far, we aimed to create an simulated online situation for users to talk with different people. In this model, their interact object is real people who have different characteristic and different culture, maybe different accent but same learning goals. Therefore, the situation would be more complicated but also more interesting and challenging.

&nbsp;&nbsp;&nbsp;&nbsp; In addition, human-machine interaction also necessary because users need to practice their speaking skill with an virtual partner. This virtual partner can interact with users based on pre-designed dialogue to help users memorize or command different expressions. Well, virtual partner is always online and accompanied with users.  

  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part5-4.jpg" height="420" width="300" > </div> 

&nbsp;&nbsp;&nbsp;&nbsp; Based on the upon illustrations, we fill out some concept framework to summarize the relationship between these five factors. These relationships can be explained more clearly by combining learning theory. So let’s move into part 6 to see how to understand these two framework.  

## 6	Learning theory  
####  （1）What learning theory do you mainly applying
&nbsp;&nbsp;&nbsp;&nbsp; We mainly applied constructivism and behaviorism learning theories in our platform. Constructivism theory means learners can construct new knowledge in the process of discussing or collaborating with others based on their previous knowledge.  Behaviorism learning theory emphasize the stimulus, reaction and feedback. It means external environment or situation would stimulate learners to learn and react, like asking questions (stimulus)and giving answers(reaction), then following feedback for learners (true or false). 
####  （2）Why do you applying this(these) theory
&nbsp;&nbsp;&nbsp;&nbsp; Constructivism is necessary because speaking is a kind of social interactive skill which can be improved by discussing and collaborating with real people in real situation. Thus, in our platform, users can be randomly paired with different people and then have a conversation about specific topics like café, or hospital to construct new knowledge. and new knowledge would affect their learning behavior like speak loudly, fluently and quickly, and learning experience like improving learning interest and motivation. 

  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part6-1.jpg" height="360" width="604" > </div> 
&nbsp;&nbsp;&nbsp;&nbsp; In addition, we applied behaviorism theory because we believe speaking skill can be improved by training and practicing. For example, learners need to do a lot of exercise before attending final exam. In this view, we designed various of sceneries to teach users how to spell, pronounce, and how to speak. Users can learn some basic vocabulary and useful statements before they move into practice. when users choose human-machine model, they can also interact with virtual partner to complete pre-designed dialogue. After this stimulation and reaction between users and virtual partner, there is an in-time feedback from our platform to give users reflection, suggestions and ranking score.

 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part6-2.jpg" height="360" width="604" > </div> 

## 7	Technology applying  
&nbsp;&nbsp;&nbsp;&nbsp;The APP mainly uses location technology, speech recognition technology, deep learning technology, big data technology, and mobile development technology.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part7.png" height="360" width="604" > </div> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 7-1 primary technology  

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
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Table 8-1 Required data and functions
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8.png" height="360" width="360" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;The following figure (Figure 8-1) lists several sources for each type of data. The places that learners often to go include the time, place, numbers and frequency of their visits. The places that learners may go include the scenes they collect and the places they often visit. Learners' speaking level includes the overall score, ranking and scoring of each test. Learners' learning difficulties and key points include frequently mispronounced words or sentences, favorite words or sentences, and the time and scene of looking up words. Learners' learning habits include when they will study every day, how long they will study every time, the play model they often choose, how many times they click on the path, and how many times they talk to their contacts.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-1.png" height="360" width="604" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 8-1 The specific composition of each type of data
 
### 8.2 How will you capture that data?
&nbsp;&nbsp;&nbsp;&nbsp;After the APP development completed, the database connection will be established, and the external database will show some relevant information, these data can be obtained from an external database. The APP itself also has the function of storage at the same time, a part of the data also can come from in the storage structure of the APP itself. The collection methods for each data are shown below.
#### (1) Places learners often go
&nbsp;&nbsp;&nbsp;&nbsp;The external database creates a table of "date - time - place - times - frequency of the last week”. Every time you arrive at a new location and open the map scene provided by the APP, the external database will get the corresponding data, including the date, time and location of this time, and store it. "places you often go" on the home page is sorted according to this number. See figure 8-2.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-2.png" height="360" width="604" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 8-2 The collection methods of Places learners often go

#### （2）Places learners might go
&nbsp;&nbsp;&nbsp;&nbsp;This part of data is also obtained from the external database, which has a table of "scene collection". When learners click on the table of "scene collection", the tag of the scene will be transferred to the corresponding table. The "guess you want to go" on the home page will be pushed based on the data in the table. Meanwhile, the system uses deep learning algorithm to calculate the information in the table of "places you often go", so as to recommend the scene of "guess you want to go". See figure 8-3.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-3.png" height="360" width="604" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 8-3 The collection methods of Places learners might go

#### （3）Learner's level of oral English
&nbsp;&nbsp;&nbsp;&nbsp;The scores obtained from the dialogue between the learner and the machine, and the conversation between everyone. And these scores will be summarized into a total grades. The grades of the total score determines the level of the learner, from which comes the data of the learner's oral English level. See figure 8-4.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-4.png" height="360" width="604" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 8-4 The collection methods of Learner's level of oral English

#### (4) Learning difficulties and key points
&nbsp;&nbsp;&nbsp;&nbsp;When learners mispronounce a word or sentence, the internal database of the APP will record and give feedback. When the number of times reaches a certain limit, the word or sentence will be transferred to the external database and marked as a learning difficulty. At the same time, the time and scene of learners' checking words in the process of using the APP will also be recorded and sent to the database, which will be reflected in "collections". See figure 8-5.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-5.png" height="360" width="604" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 8-5 The collection methods of Learning difficulties and key point

#### (5) Learning habits of learners
&nbsp;&nbsp;&nbsp;&nbsp;After the learner completes the learning of a scene, the system will upload the learning start time, the learning end time, the selected mode, the number of prompts clicked in everyone mode and the number of conversations with friends in the learning process to the external database to obtain the learning situation of each learner. Then through big data analysis technology, we can understand the learning interests and habits of learners. See figure 8-6.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-6.png" height="360" width="604" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 8-6 The collection methods of Learning habits of learners

### 8.3 How will you structure the data?
&nbsp;&nbsp;&nbsp;&nbsp;In this APP, xAPI documents need to be defined in such aspects as places learners often go, places learners might go, learner's level of oral English, learning difficulties and key points and learning habits of learners. The following table respectively illustrates the xAPI statements for each kind of data.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Table 8-2 The xAPI of places learners often go
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-7.png" height="360" width="604" > </div>  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Table 8-3 The xAPI of learner's level of oral English
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-8.png" height="360" width="604" > </div>  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Table 8-4 The xAPI of places learners might go
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-9.png" height="360" width="604" > </div>  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Table 8-5 The xAPI of learning difficulties and key points
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-10.png" height="360" width="604" > </div>  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Table 8-6 The xAPI of learning habits of learners
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part8-11.png" height="360" width="604" > </div>   
  
## 9 UX evaluation  
### 9.1 The questionnaire 
&nbsp;&nbsp;&nbsp;&nbsp;We collected a total of 31 questionnaires, of which 30 were valid. There are 13 boys and 17 girls. Among them, there are 9 undergraduates and 21 postgraduates. The proportion of each grade was 67.74%, 6.45%, 6.45%, 6.45% and 12.9% respectively.
  <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/Questionnaire%20introduction.png" height="360" width="400" > </div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Figure 9-1 Questionnaire introductio 

### 9.2 Confidence_Intervals Sheet
&nbsp;&nbsp;&nbsp;&nbsp;In the Confidence_Intervals Sheet, when the confidence level is equal to 95%, the corresponding Z value is 1.96, the standard error calculation formula is SE = Std / root number N, the confidence degree Confidence is equal to SE * 1.96, and the confidence interval is equal to Mean -Confidence to Mean + Confidence. For example, in the first line of Item1 in the Confidence_ Intervals Sheet, when the confidence level is equal to 95%, the corresponding Z value is 1.96, the standard error calculation formula is SE = 1.083 / root number 30, and the confidence level Confidence = SE * 1 96 = 0.387, the corresponding confidence interval is 1.613 ~ 2.387. This shows that when there is another sample, there is a 95% probability that it will appear in the range of 1.613 ~ 2.387. In the second line, when the confidence level is equal to 95%, the corresponding Z value is 1.96, the standard error calculation formula is SE = 1.626 / root number 30, and the confidence degree Confidence = SE * 1 96 = 0.582, corresponding to The confidence interval is 1.085 ~ 2.248. It means that when there is another sample, there is a 95% probability that it will appear in the range of 1.085 ~ 2.248.

 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part9-2.png" height="360" width="604" > </div>
 
 <div align="center">Figure 9.2. Confidence_Intervals</div>
 

### 9.3 Answer_Distributions Sheet
&nbsp;&nbsp;&nbsp;&nbsp;In the Answer Distributions Sheet, it can be seen that the green part (higher score) occupies the majority, and the right side is basically biased towards better evaluation content, such as innovative, appealing, practical, and high-quality. People are pleasant, efficient, able to provide assistance, meet expectations, etc. It can be seen that users have a good experience with the elites of spoken English learning software, which indicates that the design products of our group have been obtained by users to a certain extent. Approved. Of course, there are also some problems with the products designed by our group. For example, some users will think that our products are drowsy, complex and unpredictable, indicating that the products designed by our group need to be improved. The functional design should be more concise and easy to operate, and enriching some functional applications becomes more interesting. In addition, the unpredictable and predictable keep at a relatively equivalent level, indicating that the products designed by our group have some English on the market. The functions of the spoken language learning software also have some unique features of the products designed by our group to attract more users to use our products.

 <div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team-2/blob/master/images/part9-3.png" height="360" width="604" > </div>
 
 <div align="center">Figure 9.3. Answer_Distributions</div>

### 9.4 Inconsistencies
&nbsp;&nbsp;&nbsp;&nbsp; In Inconsistencies sheet, the detect Suspicious Data can detect such more or less random or not serious answers because not all participants will answer all items seriously. In a participant's questionnaire, in the same dimension, if the best evaluation minus the worst evaluation score is higher than 3, it means that the participant's answer in this dimension is not serious.

&nbsp;&nbsp;&nbsp;&nbsp; In our questionnaire data, five people did not answer seriously in one dimensions. It is indicated that most of the participants were very serious about this questionnaire.
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part9-4.png" height="360" width="400" > </div>  

### 9.5 Sample_size
&nbsp;&nbsp;&nbsp;&nbsp; The Sample_size sheet can give the minimum sample number of our questionnaire under certain precision and confidence interval according to the standard deviation. The precision refers to the deviation between true scale mean in the population and the estimated scale mean from the sample. The confidence interval refers to interval estimate of a population parameter and is used to indicate the reliability of an estimate. The standard deviation refers to the square root of the variance.

&nbsp;&nbsp;&nbsp;&nbsp; Our sample size is 30, and confidence interval is calculated to be 95%. The precision is 0.5.

&nbsp;&nbsp;&nbsp;&nbsp; The value in the population is the value from the sample plus or minus 0.5, and we have a 95% probability that the true value in the population is within this interval.
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part9-5-1.png" height="360" width="400" > </div>  
<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part9-5-2.png" height="360" width="400" > </div>  

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

&nbsp;&nbsp;&nbsp;&nbsp; As we can see from following table1, mean value of 6 scales are all higher than 1.4. the highest is attractiveness whose mean value is 1.839(SD=1.00), then followed by stimulation, efficiency and novelty. While the dimension of perspicuity is the lowest one. thus, we can have a result that users experience of 	QuShuoJingYing platform from different regions and major are positive and good.

<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part9-8-1.jpg" height="360" width="604" > </div> 

&nbsp;&nbsp;&nbsp;&nbsp; As it shown in following figure1, we can have a visualized and intuitive description of users experience, the overall average were really positive and close to value 2. But we can’t see the detailed mean value and standard deviation of each scale if we ignore the table1. 

<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part9-8-2.jpg" height="360" width="604" > </div> 

&nbsp;&nbsp;&nbsp;&nbsp; Let us move into more detailed descriptions of each item.（figure3） Obviously, this figure can give us more direct and clear explanation that why the mean value of 6 scales are higher than 1.4. for example, the mean value of attractivenss scale is 1.839. the result is mainly due to users experience of our platform are enjoyable, pleasing, good and attractive.  

<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part9-8-3.jpg" height="500" width="500" > </div> 

&nbsp;&nbsp;&nbsp;&nbsp; The table2 is a statistical description of pragmatic and hedonic quality of our platform. The results showed that attractiveness, pragmatic and hedonic quality are good (between 1.6, 2). That means users thought that our platform are attractive and practical, not to mention its hedonic quality.  

<div align="center"><img src="https://github.com/ECNU-DEIT-ACADEMIC-2019/Team2/blob/master/images/part9-8-4.jpg" height="360" width="604" > </div> 



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
  
 
 ## 11 conclusion


&nbsp;&nbsp;&nbsp;&nbsp; The table2 is a statistical description of pragmatic and hedonic quality of our platform. The results showed that attractiveness, pragmatic and hedonic quality are good (between 1.6, 2). That means users thought that our platform are attractive and practical, not to mention its hedonic quality.   
### 11.1 self assessment
&nbsp;&nbsp;&nbsp;&nbsp; After the collaboration with my partner, I have learned a lot from their group members. They are very creative and impressive, they also can give me a lot of suggestions and guidance. In addition, I have cultivate my interest in designing. We used very useful collaborative tools to design our platform, there are a lot of useful templates we can use. Furthermore, I have improved my critical thinking skill by modifying and designing oral English learning platform, I believe that our platform is useful and meaningful.Finally, my contribution for this group project are mainly include:
(1)	Designed the function of human-human interactive interface, which include the functions of video and audio chatting, searching dictionary, adding new friends, translation of speaking, uploading files and images, conversation guidance for users, address book, pressing to speak, adding favorite, etc.
(2)	Writing the final reports, which include the KIEBIE analysis, learning theory , UX survey and analysis.
(3)	Giving presentation of our final reports

. 

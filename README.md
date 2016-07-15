# Expense-Manager-App
Expense Manager Android App 

Expense Manager Mobile Application
Mahender Rao Arshanapally, Sai Sri Ram Kotcharlakota and 
Suma Bhargav Nallajeru, Members of Group 7, CPS 610 Fall 2014

Abstract:- Mobile applications stood top among usability and user convenience. Many applications are available in the market to manage personal and group expenses. Not many applications provides a comprehensive view of both use cases. In this project, we develop a mobile application that keeps track of user personal expenses, his/her personal contribution towards group expenses, maintain monthly incomes, recurring and adhoc payments. It provides information of "who owes who and by how much".

The proposed application would eliminate sticky note, spreadsheet and ledger that cause confusions, data inconsistency problems while recording and splitting of expenses. With our application user can manage his expenses more effectively.

As part of research, we would consider adding certain features to the application to make it more useful to the user. Some of the extra features are like enabling users to register to the application using existing email or social network account[15][16], it will synchronize the users profile information to the application. Apart from this, the application can be used to collect samples of data related to user’s expenses with permissions and use those sample data as parameters to evaluate patterns of spending. Using some data mining technique expenses can be classified and can be used in market analysis and planning.

This application will not only helps users to manage their expenses but also help marketing executives to plan marketing according to the needs of users. 

Index Terms: - Mobile applications, expenses, social networking accounts, data mining techniques, market analysis.



1.	Introduction

The Expense Manager is a mobile application intended to run on android device namely smart phone. Expense Manager is designed to efficiently cater the needs of users by eliminating imparting costs and settling vows to friends. The application encourages corresponding users help in who owes who, and for what. Aim is use better approaches to help users and their companions to share expenses easily. 

This new application will let bunch users and their companions to have detailed view inside this application around individual costs. 

The app allows its users to add a remark to an expense, click on the expense name in any expense list. Bill posting will have space for comments and notes container with a "Post" catch underneath. The Expense Manager has notification option to notify each time somebody adds a remark to an expense user is on, or user can withdraw to posted bill. 

The additional feature that we are going to add in this application that enable us to collect the sample data of users expenses and use this to study patterns of expenses in certain area or by specific kinds of spending for market analysis. These patterns can be derived using some data mining techniques [7][17][18][19] such as clustering, classification and association. 

2.	Background Study

The idea of developing this project in  platform arises with the frequent problems being experienced by people in sharing among them. 
Some of the concerns related dividing expenses are like maintaining personal expenses is a BIG problem, splitting the expenses among group is confusing. 
Some of the conventional methods used to tackle this problems in normal circumstances are like making use of a sticky note by normal users, Proficient people deal with this kind problems by using spreadsheet to record expenses and using a ledger to maintain large amounts data by especially by experts. As this show that it is variable methods used by different people. This make using this data inconsistent.
There are still problems in areas like there is no assurance for data consistency, there are chances of critical inputs can be missed and the manual errors may creep in. The Data recorders are not always handy and it could be hectic process to have overall view of those expenses.

We believe a handy design a handy mobile application which handles these problems.
Such that app is capable of recording the expenses and giving comprehensive view with easy to use user interface and this app is intelligent enough to answer : ‘ Who owes who ?And by how much ??’

3.	3. Objective of research

The mobile applications that are available in the market are very useful to the smartphone users and make their life easy. The expenses manager is also one of those applications, which much scope in daily life. As there are many similar applications available today we added some innovative features to make our application unique, easy to use and efficient. 
Apart from adding unique features like combining group expenses and personal expenses in to one application, we also added features like trends, estimations.
Here, we have an idea of making use of application for the purpose of survey in the field of expenditures of user. This idea serves as main objective of research project. The research also includes syncing of the applications with some social networks and emails as well[15][16].  

4.	Methodology

This section of paper is very important and this will guide our team to successfully accomplish the goals set for research. Here, the research project methodology describes the steps and approaches to be fallowed to attain final product. As explained above our project is of splitting the expenses between the groups and also to efficiently manage the personal expenses as well. However, our projects will have additional features included as part of our research so that it makes our project unique in the market. These features would make the project more efficient and very useful for our users. Apart from the benefits user gets and there is an important use of the system that enables us to use the data of the user with his prior permissions for the purpose of data mining for several other functionalities to be applied in market by analyzing user expenses [7][17][18][19]. 

4.1	User registration/creation

This application like most of the applications will have user login screen and option for registration. The user must register in this application when he/she is using for first time. However, the user who is already registered can login to the application using his/her login credentials that are created by the user at the time of registration. 

4.2	Creating, alter of user groups

The expense manager applications has the option to create different groups as they wish and add members to the group accordingly. The user can create, alter and delete the group as the user intends.
  
4.3	Adding income/expenses

The every user of the application has the options to add incomes and expenses accordingly. This application will provide drop downs to choose the categories or type of income or expenses. Each record should have details like date of occurrence of item, details of items etc.
 
4.4	Splitting of expense

One of the main feature of expense manager application is to split the expenses within the groups as intended by the user in an efficient and accurate manner.
This will be done based on the algorithm designed to split the expenses using the records made available.
 
4.5	All expenses details

This apart of our application will provide user with option to view all the records of expenses and income with selection from-date and to-date. This will give comprehensive view of the expenses/income records for give selection of user.


4.6	Showing trends

The trends is one of the unique factors of our mobile application. This is the graphical representation of the overall user expenses per certain period, that could be monthly, quarterly, half-yearly and yearly as well. This works with the algorithm that calculates average expenses of the user for certain period by using the expenses records created using this application.
Apart from showing trends of expenses on whole, this will also give expenses in detail by showing the trends by expense categories.
 




4.7	Estimating expenses

The other part unique part of our expense manager application is to estimate expenses that user may spend in current or next month. This will help the user to adjust his expenses accordingly so he/she can avoid running out of money.
This estimations can be derived from his/her previous expenses using algorithm that uses records from expense table. During estimating expenses the algorithm should avoid using records that has huge variations because these expenses could be for long term in nature and they doesn’t occur frequently. This helps users to manage their expenses efficiently.
The below graph is estimations for month of December, here it shows higher expense then that shown in trends graph because it considers Christmas in this month and expects overspending of money. 




4.8	Collecting user data

The collection of data of expenses and income of user from databases is easy task since every record of user activity is stored directly in database server maintained by us. But, to make our application safe and to maintain confidentiality of user data we undertake necessary steps to counter this problem. We will ask for user permissions to use user data for analysis purpose and will ensure confidentiality of every data related to data. The data samples are collected from user without disclosing any of user identity.

4.9	Applying Data Mining Techniques

The data collected from user is used to evolve certain user patterns, clustering and association of the expenses. The Extraction of interesting patterns that is non-trivial, implicit, previously unknown and potentially useful patterns or knowledge from huge amount of data [7]. We would apply appropriate algorithms of some famous data mining techniques [7][17][18][19] available today. However, this would need helping hand from a data mining expert.
4.10	Usage patterns in Market analysis

The Data collected from user and the patterns evolved after applying data mining techniques [7][17][18][19] as elaborated in the above part of this report are used for market analysis. The experts in the market can use these patterns of user expenditures based on age, gender, place of user. This will help market strategist to plan accordingly so that it stabilize the demand supply in the market benefiting all the stakeholders.


5.	Implementation

5.1	Methods

The method adopted to develop the application to manage both personal and group expenses are proposed in earlier section of this paper. However, this section will elaborate those method used to obtain results using inputs from the users and this would also use data from database to evolve results like trends and estimations. 

5.1.1	Splitting expenses

This is done by using division of the total expenses with number of group members. However, this would change with the choice of users on number of members to divide between. This is application of simple arithmetic operations.

5.1.2	Trends Representations

This is one of the unique feature of application, here we use the records from database and group them month wise. The sum of all expenses monthly of all previous months and also sum of expenses based on expenses type separately.
After calculating the sum, we divide total by no. of months to achieve average.
This will give the trends of expenses in total and trends for each expenses type for each month on average.
Here, to make analyzing expenses trends easy to users we choose to represent those figures graphically (bar graph).
   
5.1.3	Estimations

This is also a unique feature of expense manager. The estimations of expenses of user are suggested to them. This would help the user to adjust his spending accordingly. Our application will estimate the expenses using the records of the user expense from database tables. This works similar to the evolving trends in above method but here we avoid some expense types and also avoid expense that doesn’t occur frequently like buying electronics, which are not recurring expense.   

5.1.4	Usage of collected data

The data is collected from databases tables of users after having their prior permissions. This will depend on the type of data mining technique [7][17][18][19] adopted so this method is applied at server end have no direct involvement of user. The technical consultant is always available at server end for maintenance service.  

5.2	 Results of research

5.2.1	Splitting expenses

Each and every individual will have their actual debts and credits who used to share in a group or individually. The splitting expense results in hassle free calculation of shared expenses occurred in a group. 

5.2.2	Trends Representations

Here we use the records from database and social event them month insightful. The aggregate of all expenses month to month of all prior months moreover entire of expenses concentrated around expenses sort autonomously. 

In the wake of discovering the total, we parcel signify by no. of months to perform typical. This will give the examples of expenses out and out and designs for every one expenses sort for consistently generally.  

Here, to make breaking down expenses floats easy to customers we choose to identify with those figures graphically (reference chart).
  
5.2.3	Estimations

This is also a unique feature of expense manager. The estimations of expenses of user are suggested to them. This would help the user to adjust his spending accordingly within their budget. However, this application will not consider some expense types like buying electronic appliances, automobiles and other expensive products which do not occur frequently.

5.2.4	Usage of collected data

            Entire usage of collected data will be used only by third party for the purpose analyzing expenses and will have no direct involvement of user. The results obtained this will help market strategist to plan accordingly so that it stabilize the demand supply in the market benefiting all the stakeholders.

6.	Testing

6.1	Analysis of results
      
     The results obtained seem to be accurate on the preformed operations on the application. The application delivered efficiently in calculating split expenses and recording the expenses along with date and time. 
The application is accurate as the sum of expenses after split is always equal to total expenses. The sharing of expenses according to users, which is also accurate.
 
6.1.1 Trends
The mobile application is working correctly for resulting of trends based on previous monthly records. Those results are just average of expenses monthly for both group and personal expenses from database tables.  

6.1.2	Estimations

The mobile application is working approximately estimating results based on previous monthly records. Those results are just average of expenses monthly for both group and personal expenses from database tables. This only considers recurring expenses of the particular user

6.1.3	Collection of data

This is not part of client side application and solely server side application. These are always hassle free because it is handled by people with technical knowledge.


7.	Conclusions and further study

 In this project, we develop a mobile application that keeps track of user personal expenses, his/her personal contribution towards group expenses, maintain monthly incomes, recurring and adhoc payments. It provides information of "who owes who and by how much".

The application will eliminate sticky note, spreadsheet and ledger that cause confusions, data inconsistency problems while recording and splitting of expenses. With our application user can manage his expenses more effectively.

As part of research, we considered adding certain features to the application to make it more useful to the user. Some of the extra features are like enabling users to register to the application using existing email or social network account, it will synchronize the users profile information to the application[15][16]. Apart from this, the application can be used to collect samples of data related to user’s expenses with permissions and use those sample data as parameters to evaluate patterns of spending. Using some data mining technique[7][17][18][19] expenses can be classified and can be used in market analysis and planning.

This application will not only helps users to manage their expenses but also help marketing executives to plan marketing according to the needs of users. 

8.	Acknowledgment

The Expense Manager mobile application is the idea inspired from several mobile applications dealing with managing of the problems related to managing the funds and expenses. Some of the application that we would like list are splitwise, financial calculators, Expense manager by bishinwes, Expenser, personal expenses, etc.[10][11][12] all those available in android market.

However, our application only inspires idea and we implement them on our own by including some more unique features that make application more useful to the user.

9.	References

[1] Fundamentals of Database systems – book by Elmasri and Navathe
[2] Scrum Methodology & Agile Scrum Methodologies
[3] Developer.android.com
[4]http://www.appbrain.com/app/expense-manager/com.expensemanager
[5]http://expense-manager.com/how-expense-software/
[6] https://www.splitwise.com/terms
[7]Textbook-Data Mining: Concepts and Techniques (3rd Edition)
by J. Han, M. Kamber, and J. Pei -- Morgan Kaufmann Publ. 2012
ISBN: 978-0-12-381479-1
[8]IEEE Transactions on software engineering, vol. 31, No. 3, March 2005
[9]R.Pressman, software engineering A practitioner’s approach. Fifth edition McGraw-Hill, 2001.
[10]https://www.xpenditure.com/en?
[11]https://markushintersteiner.at/
[12]http://expense-manager.com/how-expense-software/
[13]www.vogella.com/tutorials/Android/article.html
[14]www.raywenderlich.com/56107/make-first-android-app-part-1
[15]http://code.google.com/p/socialauth-android/wiki/Facebook
[16]http://code.google.com/p/socialauth-android
[17] Data Mining and Analysis: Foundations and Algorithms, Mohammed J. Zaki and Wagner Meira, Jr, Cambridge University Press, 2013. 
[18] Introduction to Data Mining, by Pang-Ning Tan, Michael Steinbach, and Vipin Kumar, Addison Wesley, 2006.
[19] Data Mining: Concepts and Techniques (2nd edition), by Jiawei Han and Micheline Kamber, Morgan Kaufmann, 2006.


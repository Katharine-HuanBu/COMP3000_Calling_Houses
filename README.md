![Plymouth Logo](https://user-images.githubusercontent.com/64517811/165017815-866b8dfa-13fa-4374-883f-d996cf986fdd.png)

# Project title
   Calling Houses_Housing rental management system 
# Author Information
1. Name : Huan Bu
2. Student Reference Number : 10719608
# Project Allocated supervisor
Lingfen Sun
Associate Professor in Multimedia Comms and Networks
# Project Objectives
1. Quick search - more accurate and faster search through multiple criteria; Such as the location of housing supply; Area; The rent; Room type and other conditions, common
2. Search for houses that meet users' needs;
3. Low cost - housing rental management system can liberate people from labor, reduce labor costs;
4. Large storage capacity -- housing rental management system can accommodate houses from all over the world, providing users with a wealth of choices;
5. Excellent confidentiality -- through dynamic verification code, improve the security of user personal information and system privacy;
6. Sentiment analysis -- Users can share rental comments, and the system classifies the comments to help other users better understand the housing situation.
# Functional requirements
The user roles of the housing rental management system are mainly divided into three types: 1. Visitor; 2. User; 3. Administrator.
The following are the functional requirements that the housing rental management system needs to meet:
# Visitors
1) Visitors can log in to the system.
2) Visitors can register for the system.
3) Visitors can browse the details of all houses.
4) Visitors can search for houses according to different house conditions.
# Users
1) Users can log in to the system.
2) Users can log out of the system.
3) Users can view information about the rental properties in the User Centre.
4) Users can view the details of all properties.
5) Users can search for properties according to different housing conditions.
6) The user can sort the properties according to the different property criteria.
7) You can rent a property.
8) You can pay to rent a property.
9) The user can extend the rental period of a property.
10) The user can pay rent for the delayed rental period.
11) The user can withdraw from the rental.
12) You can change your personal password.
13) The user can read the contract of the rented property.
14) The user can comment on the housing.
15) The user can see what other people have said about the property in the details of the property.
16) The user can see the system analyse the sentiment of the user's comments, positive or negative.
17) The user can see the visualisation of the sentiment analysis of the comments.
# Administrator
1) The administrator can log in to the back office system.
2) The administrator can log out of the system.
3) The administrator can return to the front page.
4) The administrator can view the user's information.
5) The administrator can add users' information.
6) The administrator can delete the user's information.
7) The administrator can view the monthly profit of the lease.
8) The administrator can view the annual profit of the house rental.
9) The administrator can retrieve and count the profit of the house rental over a period of time.
10) The administrator can search for a property by its name or status.
11) The administrator can add information about a property.
12) The administrator can delete the information of a property.
13) The administrator can edit the information of the house.
14) The administrator can add pictures of a house.
15）Administrators can delete pictures of properties.
16) The administrator can view the information of the properties that have been requested to be unsubscribed.
17) The administrator can view the information of the properties that have been postponed.
18) The administrator can change the password.
19) The administrator can adjust the font size of the displayed page.
20) The administrator can change the background colour of the theme displayed in the background.
21) The administrator can choose the visualisation method according to the housing profit statistics, such as bar graph or line graph.
22) The administrator can download the visualisation of the housing profit.
23) The administrator can add user comments.
24) The administrator can delete user comments.
25) The administrator can edit user comments.
26) The administrator can review the housing information that the user has requested to unsubscribe.
27) The administrator can view the information of the properties that have been reviewed and unsubscribed.
# Related library
1. certifi==2021.10.8
2. Django==2.2.5
3. django-admin-tools==0.9.2
4. django-filter==21.1
5. django-ranged-response==0.2.0
6. django-simple-captcha==0.5.14
7. django-tables2==2.4.1
8. Pillow==9.0.0
9. PyMySQL==1.0.2
10. pytz==2021.3
11. six==1.16.0
12. sqlparse==0.4.2
# Running the project locally
1. Drop down the repository: https://github.com/Katharine-HuanBu/COMP3000_Calling_Houses.git
2. Use PyCharm to open the project file.
3. Change the database connection name and password and port in setting.py.
4. Install the dependencies: pip install -r requirements.txt
5. Start the service: python manage.py runserver
# jquery plugins
https://www.jqueryscript.net/categories/
# Sentiment analysis
https://github.com/huggingface/transformers/blob/main/README_zh-hans.md
```python
from transformers import pipeline
classifier = pipeline('sentiment-analysis')
classifier('We are very happy to introduce pipeline to the transformers repository.')
# [{'label': 'POSITIVE', 'score': 0.9996980428695679}]
```

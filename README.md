# COMP3000_Housing_rental_management_system
  Used for Plymouth University graduation project  
# Author Information
1. Name : Huan Bu
2. Student Reference Number : 10719608
# Project Version : Version1
The first version of the project mainly completed the following functions:
1. User login and registration function;
2. The function of browsing housing information;
3. Search different house information functions according to different conditions;

# Project Objectives
1. Retrieve quickly - more precise and faster search through multiple criteria; Such as the location of the housing supply; Area; The rent; Room type and other conditions, common 
2. Search in line with user needs of the housing; 
3. High efficiency - Through the voice recognition function, can quickly enter the user's search content; 
4. Low cost - Housing rental management system can liberate people from labor, reduce labor costs; 
5. High reliability - Through face recognition login registration, can improve the user's personal information security and system security;
6. Large storage capacity - Housing rental management system can accommodate housing from all over the world, providing users with a wealth of choices; 
7. Excellent Confidentiality - Login registration through face recognition can improve user personal information security and system privacy;

# Functional requirements
The user roles of the housing rental management system are mainly divided into three types: 1. Visitor; 2. User; 3. Administrator.
The following are the functional requirements that the housing rental management system needs to meet:
# Visitors
1. The functional requirements of tourists itself is not a lot, but in order to guarantee that the house lease management system using the quality and efficiency, visitors can also according to different conditions to search houses, such as the name of the building, the location of the building, the area size of the building, housing prices, housing condition and so on different conditions can be searched.
2. Visitors can also according to the different housing conditions for housing information for sorting, for example, the housing ID can be from big to small or from small to large, arrangement can be carried out in accordance with the building name initials arranged, can be in accordance with the details of the house of words the first letters, can also according to the size of the house, can be arranged according to the price of the house, They can be arranged by the location of the house, they can be arranged by the time the house was updated, they can be arranged by the state of the house.
3. In order to ensure the security of tourists' registration and login system, we have specially added dynamic verification code. Tourists can protect their personal information by means of dynamic verification code when they register and log in.
# Users
1. In order to ensure the security of user registration and login system, we also specially add dynamic verification code, users can use dynamic verification code to protect their personal information when registering and logging in.
2. Users can also according to the different housing conditions for housing information for sorting, for example, the housing ID can be from big to small or from small to large, arrangement can be carried out in accordance with the building name initials, may, in accordance with the details of the house of words the first letters, can also according to the size of the house, can be arranged according to the price of the house, They can be arranged by the location of the house, they can be arranged by the time the house was updated, they can be arranged by the state of the house.
3. Users can also query the house information they want to rent according to their own needs, and can choose to rent the house, read the contract, manually enter the lease period, the system calculates the deadline and rent, convenient for users to use, to provide the efficiency of housing lease;
4. The user can also extend the lease of the house, when the house is still in effect, the user has a chance to extend the lease of the house, so that the user can rent the house for a longer time;
5. When the user rents the house or extends the lease of the house, when suddenly do not want to rent the house, they can choose to return the house. Click the user center to view the detailed information of the house you rent, and choose to cancel or surrender the house you rent. When the user confirms to vacate the house, the state of the house will be displayed as the application for vacating the house. After the backstage administrator agrees to the user's vacating the house, the user can vacate the house. This ensures the rationality and fairness of the whole rental house.
# Administrator
1. for the administrator to increase the one of the biggest function is about the statistics of the profits, the administrator can search page enter start and end time in profit, search within a period of time, the number of rental housing, as well as the detailed information of the building, and the administrator can also see the level of profitability, it was a time when convenient administrators to manage the information.
2. In addition to profit retrieval, a more important change is the statistics of housing information. Administrators can click the button waiting for application on the housing information statistics page to query the housing information waiting for application; Click on the "Deadline" button to check the housing information before the Deadline; Click "Delay" button to query delayed housing information; Click 'Total' to query the information of the whole house; Click 'Empty' to display information about Empty houses; Click on the 'Rented' properties to display information etc. It'll show you the annual profit and the monthly profit of the house and so on.
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

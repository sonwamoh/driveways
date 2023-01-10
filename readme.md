--------------------------------------------------------------------------------------------------------
<font size = "12">
<b>Access the Project</b>
<br>
Team 1 - Dat, Mohit, Michael - Driveways
<br>
Connection: 'root'
<br>
Password: 'Root123!'
<br>
Dump: DrivewayDump.sql (includes create)
<br>
Admin Login: mike@driveways.com
<br>
Admin Pw: pw
<br>
User Login: gon@gmail.com
<br>
User Pw: pw
<br>
</font>
---------------------------------------------------------------------------------------------------------
<b> Project Description </b>
<br>
<b> Functional Requirements <b>
<br>
This application provides functionality for different types of users, including hosts, renters, and admins. Hosts and renters will be the primary user. The primary user will be able to create an account and be able to list a driveway rental or rent a parking space from the rentees. The behaviors will change depending on the selection of roles when the user interacts with the application. Renters will have to input their basic information, car identification, and payment methods. The application will provide them with the list of closest parking spots when they search based on their location. The hosts will have the option to list their driveways on the application. The application will ask for the space description, address to approve a listing. They also have the authority to modify and update their listings at any time. Admins have access to remove, edit and add any listing at any time. This allows admins to maintain and test the application.
<br>
<br>
1>User Login / Sign-up:The system will prompt a “guest” user to either login or signup, and will prompt the user with a form to do so. 
The first time users should sign-up inorder to access the application.A “Signed-in” user will be able to search and reserve listings, or list their own listing on the system.
<br>
2>Account creation:There will be user accounts and admin accounts. Admin accounts will have additional features on top of the standard user account.There will be a form provided to the user by the system to input user details such as name, email, payment information, and car details.
<br>
3>Display Parking Information:The user will be able to search an area for available parking spots (limited to the Bay Area in this project). They will be able to see price data, size of parking spots, available dates/times, and location.
The system will display the parking spots on a map (Google Maps API), and the user will be able to click each spot to reveal a detailed view of that specific spot.
<br>
4>Host Parking Spot:A user account will be able to list a parking spot that they own for “rent”.
The user will need to provide details of the parking spot such as size of vehicle permitted, dates/times available.
<br>
5>Search for Parking Spot:Users will be able to enter an address (within a valid area) and the system will display all the nearest parking spots. Also the available parking spots are up on the map GUI (See: “Display Parking Information”).
<br>
6>Update / Edit Listing:Admin  will be able to update and edit the current rental postings (add/remove place for rent, and modify ) 
<br>
7>User classification (host / guest):Non-admin users will be separated into hosts and renters based on their selection when accessing the web application.
<br>
8>Vehicle Identification:Users will be able to provide car identification (ID) such as VIN, Color, Make, Model and license plate number.
Users can add multiple vehicles into their accounts. 
<br>
9>Parking Duration :The User’s while booking a parking spot can enter the date and time from the time of drop-off to pick-up.
<br>
10>Payments:The user can enter their card details in order to book the parking on our website.
<br>
<br>
<br>
<b>Entity Relationship Diagrams</b>

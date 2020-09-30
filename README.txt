Project: Angular Certification Training 
Project Title: FoodOrb

Team Members: Caleb Thomas
	      Akshay Bora
	      Raynier Leroux
	      Monali Balani
	      Hannah Dubois
	      Bhola Dhital

Database:  Json-server (file name : db.json)

Front-End: Angular 

Modules:

1. Registration: This Module allows a new user to register for the app. The details are passed in the json-server which can be used for Logging in.

2. Login: This Module Verifies the username and password and passes it along to the homepage.

3. Forgot password: This component verifies your email and lets you change your password.

4. Profile/ Settings: This Page displays the User Details and provies us with functionality to Edit User, View FriendList

5. FriendList: This List contains all the friends the user has with the functionality to add,delete functionality of a friend.

5. Homepage/ SearchPage : this component provides with a search Box which allows us to search by food category (Indian, Chinese, Mexican etc.)

6. restaurants list: This list is generated based on the search item. Each Restaurant in the list can be clicked to move to its details and menu.

7. Restaurant Details: This Page contains all the Restaurant information along with the Menu items and provides us the functionality to add items to our cart.

8. Orders Page: this Page contains all the orders for that user along with buttons to navigate to the Tracking Page.

9. Tracking Page: this page displays static data to check the status of the order placed.


Additional Notes:
1. The Orders are not removed from the user even if he logs out of the application.
2. Each Restaurant Menu only has a single item.
3. The legacy code has not been used rather a json server needs to be run to access the data.

Login Credentials:
1. username: admin, password: admin	
2. username:bob@gmail.com, password: 1234 
*Note there are additional 3 users inside the db.json and you can register more.Almost all current users will have friends and orders already set.

Register Credentials:
1. For a New User the username will be your email and password will be password
2. For a New user there are 0 items in cart and there are 0 friends.

Steps for running the application:

1. Open CMD inside the Extracted project. 
2. Run npm install
3. Run ng serve
4. Run npx json-server db.json
5. Open web page address: http://localhost:4200/
6. Use Register or Login with existing credentials.
Project name
URL Shortner

Project Description
This is the repository for the final submission of the ACM open project. The tech stack used in the project is: -

ReactJS:- The primary frontend JavaScript library
Redux:- Used together with ReactJS to manage and centralize the application state 3.CSS:- Used to provide the website with custom design elements. 4.NodeJS:- Runtime environment for the backend server 5.MongoDB:- Non-relational database system for storing data.
In the project directory, you can run:
npm install
Above command can be used on the shortner_frontend side to install dependencies

npm install
Above command can be used on the shortner_backend side to install dependencies

npm start
Above command can be used on the shortner_frontend side to run client side

npm start
Above command can be used on the shortner_backend side to run server side

Internal working of the project
Backend
Authentication using bcrypt and jsonwebtoken while logging in and signup.
Shortening of URL using shortid
Search functionality using MongoDB atlas search.
Fetching of all URLs with their notes and shortid in addition to its earlier extended URL.
Frontend
Login and Signup page for authentication
Home page to get information about the website
The actual feature page consists of an area for notes and URL pasting to get shortened URL.
Implemented authorization to keep user data secure and private


References
1.React documentation :- "https://react.dev/" 2.NodeJS documentaion :- "https://nodejs.org/en/docs" 3.MongoDB Atlas Search documentation :- "https://www.mongodb.com/docs/atlas/atlas-search/tutorial/" 4."https://www.npmjs.com/package/shortid"

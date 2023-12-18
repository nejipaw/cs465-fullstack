# CS-465

Architecture:
the different styles of frontend developments that i used in the project were, Express HTML, JavaScript, and SPA(Single page application) they are all similar yet very different at the same time, all of them use some for of static HTML as well as css, express and SPA were the most similar they both used dynamically built pages but used it differently, in express there we multiple pages that shared similar layouts and elements spreading out the different areas of the site, where as the SPA used it all on one pages resulting in a slightly longer load time but overall more efficent webpage to built.

Why did the backend use a NoSQL MongoDB database?
we used mongoDB for a few reasons, i think the biggest one is that the schema is not super essential and is allowed to be a little more flexible when setting up parameters, it also allowed us to index base on a few of them and create our own shcema, another reason being is that MongoDB uses Javascript which helps fit right into the MEAN stack, this made it so we can code in Javascript within the database and easier to setup.

Functionality
How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
JSON is JAvascipt object notation and it breaks object up into various key/value pairs, this is different cause you can't do things within json it just holds data in a usable and readable format that is easily used by javascript, this ties in with frontend development becasue most front end uses javascripts objects to hold JSON data and do various things with it like in our project we used it to convert information like image name, trip name, destination etc and we then used that to populate the HTML fields and display the data.

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
in this project originally the trips page was just a static HTML we then had to refactor this in order to use the handlebars and static json data without the database this allowed us to imporve the user interface and future development because we now only had one set of html to work with for the entire list instead of 5-6 line of code per trip.

Testing
Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
for this project the testing methods we used were within the console logs and status codes, as well as running various tests with data and APIS through postman and on the site, the different status codes would allow us to know where the issue was encontered helping us find out quicker, and we could used postman in order to test our get,post,put and delete methods.

Reflection
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
this course has helped a lot as it's given me a greater insight as to what all goes into making a fully funcitoning website as well as taught me the skills on how ton diagnose and test different things, such as testing apis through postman as well as using mongodb and implementing it into a website, i also learned more on how to tie in diufferent methods like SPA and Express in order to test and try different layout types for a website, so i this this will help me be more marketable within and computer science field because i didn't just learn back end skills i learned skills for both front end and database as well as troubleshooting skills which can be very valuable.

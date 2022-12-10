# IS211_FinalProject
Book Catalogue: A web application that helps a user record details about the books they
own. The application allows a user to login and type in an ISBN, which will instigate a
search using the Google Books API. The server will save some of the information to a
database, which will be used to show the user their list of books. 

The application is using four different tables 
users: contains users 
/clouds: contains an identifier that links the owner of the cloud 
/books: contains books 
/items: contains an Identifier that links a Cloud to the book

The two admin users are:
User: admin / Pass: password 
User: system / Pass: password

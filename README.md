# Project-3-Planning
img src='./Wireframes/HomePage.png' alt='./Wireframes/HomePage.png
This app will allow you to store your comic book collection on the Web!
This app will let you edit,delete,add comic books.
When adding comic books it will allow you to put the name, the date you obtained it, and condition of the comic book.
This will for comic book collectors if they want to keep track of their collection without the hassle of looking for the physical copy.
It will have server that will store the information for future reference
Users will be able to create profiles to store their comic book information and toggle them to be public or private
Users will be able to view other users profile without editing their comic books

We will have routes that will take you to a Login Page, Sign Up Page, your comic book collection, Edit Page.
there will be in back-end /login route for the Login page to show the Login Page and allow them to log in
a /signup route for the Sign Up Page to show the Sign Up Page and sign up authenticated
a /comicbooklist  route for the index of all the comic books the user has
a /comicbook route that shows a single comic book that a user clicks on to edit,delete, and update
a /home route that shows the words "Welcome to Comical! Click the Sign Up button to create an account! If you already have an account click the Login Button!" It will have a Login button and Sign Up button

 comicBook = {
Name:'',
Published:'',
Condition:'',
Date:
}

userProfile = {
username:'',
email:'',
password:''
}


Stretch goals:
Being able to view other users pages
Being able to set profile to public or private
Being able to customize your profile i.e: profile picture,about me

Scrum Master: Brandon Wenning
Roles:
Front-end team:
Will G. :CSS Styling/State management
Urvil P. :front-end routes/connecting front-end/back-end
Back-end team:
Chelsae D: MongoDB connections/models/Schemas
Brandon W: CRUD/Routes/back-end/Scrum Master/userauth


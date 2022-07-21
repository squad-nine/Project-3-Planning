# Project-3-Planning

This app will allow you to store your comic book collection on the Web!
This app will let you edit,delete,add comic books.
When adding comic books it will allow you to put the name, the date you obtained it, and condition of the comic book.
This will for comic book collectors if they want to keep track of their collection without the hassle of looking for the physical copy.
It will have server that will store the information for future reference
Users will be able to create profiles to store their comic book information and toggle them to be public or private
Users will be able to view other users profile without editing their comic books

<details>

  <summary>We will have routes that will take you to a Login Page, Sign Up Page, your comic book collection, Edit Page.</summary>
  
  # Routes
 <ul>
 <li>/login will take you to the login page</li>
 <li>/signup will take you to the sign up page</li>
 <li>/comicbooklist will take you to your comic book collection</li>
 <li>/comicbook will take you to the comic book you click on and enable you to edit/delete that particular comic book</li>
 <ul>
 
</details>
Technologies used:
<ul>
<li>React-Router</li>
<li>JS,TS, MongoDB, Mongoose, Node.js, Express.js</li>
<li> CSS, HTML, API </li>
</ul>




a /home route that shows the words "Welcome to Comical! Click the Sign Up button to create an account! If you already have an account click the Login Button!" It will have a Login button and Sign Up button

![image](https://user-images.githubusercontent.com/102195640/180117261-880a7a5b-ceb1-455f-b885-c267ffd1ac4d.png)

here will be in back-end /login route for the Login page to show the Login Page and allow them to log in
![image](https://user-images.githubusercontent.com/102195640/180117494-3b2605de-2cd6-4030-ada3-00b064322092.png)


a /signup route for the Sign Up Page to show the Sign Up Page and sign up authenticated
![image](https://user-images.githubusercontent.com/102195640/180117560-37c8fac3-53d9-4f86-8da3-24b78751f28c.png)

a /comicbook route that shows a single comic book that a user clicks on to edit,delete, and update
![image](https://user-images.githubusercontent.com/102195640/180117796-6cea163a-23c4-4e00-814b-ae8650489c23.png)

a /comicbooklist  route for the index of all the comic books the user has
![image](https://user-images.githubusercontent.com/102195640/180117867-c66ac2ef-9455-46b1-aafa-fa45c42de006.png)


Models and Properties
 ```js 
comicBook = {
name:'string',
published:'string',
condition:'string',
date: number
}

userProfile = {
username:'string',
email:'string',
password:'string'
}
```


# Stretch goals
<ul>
<li>Being able to view other users pages</li>
<li>Being able to set profile to public or private</li>
<li>Being able to customize your profile i.e: profile picture,about me</li>
</ul>

## Scrum Master: Brandon Wenning

# Roles
## Front-end team:
<ul>
<li> Will G. :CSS Styling/State management</li>
<li> Urvil P. :front-end routes/connecting front-end/back-end </li>
<ul>

## Back-end team:
<ul>
<li>Chelsae D: MongoDB connections/models/Schemas </li>
<li>Brandon W: CRUD/Routes/back-end/Scrum Master/userauth </li>
</ul>


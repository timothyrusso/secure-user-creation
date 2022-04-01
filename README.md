# secure-user-creation
User creation with hashing password

In this task, we're going to protect our users. Inside of app.js, the passwords will be hashed using a salt with a length of 10. Using the bcryptjs module.
Also, we make it so that the response when users are created returns JSON with two fields: _id (the user's ID) and email (the user's email), and not the password.

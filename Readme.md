# Login Portal with Password Reset Functionality

This project demonstrates a simple login portal with features for user registration, login, and password reset using a web API. It is built using HTML, CSS, and JavaScript. The project uses the `fetch` API to communicate with the server.

## Features

1. **User Registration**
   - Collects user information (name, email, and password).
   - Sends the information to the server for registration.
   - Redirects to the main portal page upon successful registration.

2. **User Login**
   - Requires user email, password, and role (optional).
   - Authenticates user credentials with the server.
   - Stores a token in local storage upon successful login.
   - Redirects to the main portal page.

3. **Password Reset**
   - Allows users to request a password reset.
   - Sends an OTP (One Time Password) to the user's registered email.
   - Redirects to the reset password page.
   - Users enter OTP and set a new password.
   - Redirects to the main portal page upon successful password reset.

4. **Logout**
   - Allows users to log out, clearing the token in the local storage.

## API Endpoints

- User Registration: `POST https://geek-store.onrender.com/user/register`
- User Login: `POST https://geek-store.onrender.com/user/login`
- Forgot Password: `POST https://geek-store.onrender.com/user/forgot-password`
- Reset Password: `POST https://geek-store.onrender.com/user/reset-password`

## Hosted Link
https://ameya-shinde.github.io/Login-Portal/

## Technical JavaScript Functionalities Used

The JavaScript code in this project demonstrates the following key functionalities:

1. **DOM Manipulation**:
   - Accesses and modifies elements in the HTML document using `document.getElementById()`.

2. **Event Handling**:
   - Listens for user interactions such as button clicks and form submissions using `addEventListener()`.

3. **Asynchronous Programming**:
   - Utilizes `async` and `await` to handle asynchronous operations, ensuring a smooth user experience during API calls.

4. **HTTP Requests**:
   - Makes use of the `fetch` API to send POST requests to the server for user registration, login, and password reset.

5. **JSON Handling**:
   - Serializes JavaScript objects into JSON format using `JSON.stringify()` before sending them in the request body. It then parses JSON responses from the server using `JSON.parse()`.

6. **Local Storage**:
   - Stores the authentication token retrieved from the server using `localStorage.setItem()` and removes it when the user logs out with `localStorage.removeItem()`.

7. **Conditional Statements**:
   - Employs `if` statements to conditionally execute code based on the results of API calls, such as displaying success or error messages.

8. **String Manipulation**:
   - Extracts data from the URL using string manipulation methods like `split()` and concatenation. This is demonstrated in the password reset functionality.

9. **Page Redirection**:
   - Utilizes `window.location` to redirect the user to different pages within the application upon successful operations.

These functionalities collectively enable the application to perform user authentication, registration, and password reset operations with a smooth user experience.

## Screenshots
Main Portal Page

![Screenshot 2023-09-11 230128](https://github.com/Ameya-Shinde/HelloBonsai.com/assets/93002372/36bf845d-0b16-46a0-b99f-48381751ae36)

Register Page

![Screenshot 2023-09-11 230350](https://github.com/Ameya-Shinde/HelloBonsai.com/assets/93002372/5d3a876d-0987-4394-9030-32d711813a7c)

Login Page

![Screenshot 2023-09-11 230434](https://github.com/Ameya-Shinde/HelloBonsai.com/assets/93002372/c209d449-b473-4a6a-ba31-ec709d182256)

Forgot Password Page 

![Screenshot 2023-09-11 230518](https://github.com/Ameya-Shinde/HelloBonsai.com/assets/93002372/061a377a-aa48-452a-95b5-c089a695c648)

![Screenshot 2023-09-11 230611](https://github.com/Ameya-Shinde/HelloBonsai.com/assets/93002372/1dfdd476-96c3-45aa-b8fb-4a6ed14affc1)

Reset Password Page

![Screenshot 2023-09-11 230648](https://github.com/Ameya-Shinde/HelloBonsai.com/assets/93002372/bb39d58c-9356-41aa-8062-0c658d8f9441)

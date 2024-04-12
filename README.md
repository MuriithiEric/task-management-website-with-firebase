
# Task Management Website using Firebase

## Introduction
This is a simple task management website that allows users to add, delete, and update tasks. The website uses Firebase as the backend to store the tasks. The website is built using HTML, CSS, and JavaScript.

## Technologies
- HTML
- CSS
- JavaScript
- Firebase

## Features
- Add a task
- Delete a task
- Update a task
- Mark a task as completed
- View all tasks
- View completed tasks
- View pending tasks
- Responsive design
- User authentication
- Real-time updates


## Setup
1. Clone the repository
2. Create a new Firebase project
3. Enable Firestore in the Firebase project
4. Add the Firebase configuration to the `app.js` file
5. Run the `index.html` file in a browser
6. Sign up and log in to the website
7. Add, delete, and update tasks
8. View all tasks, completed tasks, and pending tasks
9. Mark tasks as completed
10. Log out of the website
11. View the changes in the Firebase Firestore database
12. Enjoy the task management website
    

## Note
The `new.sh` file is a shell script that contains the commands a new Firebase project, enables Firestore, and adds the Firebase configuration to the `app.js` file. The script requires the Firebase CLI to be installed on the system. The script can be run using the following command:

## Hosting to firebase
1. Install Firebase CLI using the following command:
    ```bash
    npm install -g firebase-tools
    ```
2. Login to Firebase using the following command:
    ```bash
    firebase login
    ```
3. Initialize Firebase project using the following command:
    ```bash
    firebase init
    ```
4. Select the Firebase features you want to use
5. Select the Firebase project you created
6. Enter the public directory as `public`
7. Configure as a single-page app
8. Deploy the website using the following command:
    ```bash
    firebase deploy
    ```
9. View the website URL in the console
10. Enjoy the hosted task management website!
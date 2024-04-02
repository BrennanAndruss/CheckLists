# ☑️ CheckLists

A Google Tasks clone with React and JavaScript, with additional features. This app was completed as an individual project for the Cal Poly Google Student Developer Club, created to put React and Firebase skills from workshops into practice on a CRUD application.

## 🛠️ Technologies

- `React.js`
- `JavaScript`
- `CSS`
- `Firebase`

## 📝 Features

- **CRUD Operations**: Create, edit, and delete lists and tasks. To see all task operations, hover or focus on a task. 
- **Task Details**: Add details and dates to tasks. Dates can be selected with the built-in Date input GUI.
- **Complete Tasks**: Check and uncheck tasks to mark as complete. Tasks appear with strikethrough text when completed.
- **Keyboard Navigation**: Perform all operations through navigation with the TAB key.

## 🔍 The Process

I started by creating an sign up page using Firebase authentication, allowing users to create accounts and access their unique checklists. The user information was gathered with a form element and handled with Firebase functions.

Next, I created the main panel with React, including lists and tasks manually entered into Firestore along with a top bar for additional functionality. Here I focused on the layout of the page and responsiveness for different devices.

With the elements in place, I added the CRUD functionality and integrated the Firestore database. Information about the user obtained from the sign in page is used to render the main panel, and user information can be manipulated with the standard CRUD operations.

While building out the functionality, I also implemented a clean user interface, utilizing intuitive icons from Iconify for buttons and minimizing the use of pop-up menus for all main operations. To ensure keyboard accessibility, I also made sure that all elements could be accessed using the TAB key and all buttons and input fields functioned with the ENTER key.

## 📚 What I Learned

This project was my first time using Firebase and my first time using any backend service. In combination with React's component-styled architecture and rendering, this allowed me to create a much more complex application than I have created before. I also took careful consideration of UX and UI principles for my application to create a clean, intuitive, and accessibile application.

Additionally, undertaking a relatively larger project with a submission deadline and requirements taught me skills in project management and documentation. With a set deadline, I had to strike a balance between creating a minimum viable product for submission and adding in extra features and visual flair with extra time. I documented the full process of creating my task application, making note of all the new features I learned or discovered along with all the bugs and solutions along the way.

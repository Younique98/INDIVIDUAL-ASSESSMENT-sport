# vocab-YOU-lary

In this student assessment, you will be creating an application that allows users to CRUD sports cards, authenticate with Google, and filter.

## Learning Objectives
- Single Responsibility Principle (each component/function should have one job)
- Import/Export modules
- DOM manipulation with Vanilla JS
- DOM querying with Vanilla JS
- Representing data as HTML
- Usage of semantic HTML5 tags
- Asynchronous Programming
- Promises 

## REMINDER
We are not looking for completion of all stretch goals, but are focused on you hitting MVP, although if you can make it work completely, then wahoo!

What we are looking for is MVP, time management, critical thinking about the concepts, creative thinking to bind the concepts together for a solution, and collaboration with your teammates and instruction team.

If you only get MVP complete, but display the above Core Skills and can demonstrate understanding of the fundamental code concepts, then you are learning and growing - which is what we care about.

## Tools To Use:
- Postman for API testing
- Firebase for database, rules, and authentication
- Webpack template setup steps
- dbdiagram.io or something similar for creating your ERD
- Figma, google slides, or paper for flow charting your application
- Fetch for requests
- Github issues/milestones for planning out work
- Bootstrap for styling

Make sure your Developer Tools are open at all times while working on this project. Use the messages provided in the console to determine what code needs to be fixed or implemented, and use breakpoints in the Sources tab to step through your code as you debug.

## Get Started
Create issue tickets from the items below to help you get started. 
- [ ] Setup your firebase project and create the `.env` file with your keys. (Reference the [Firebase videos](https://vimeo.com/showcase/codetracker-firebase) if you need help getting started)
- [ ] Plan your project. Take no more than an hour to plan (ERD, Flow Chart, Postman)
- [ ] `git clone YOUR_GITHUB_REPO_LINK`
- [ ] `cd` into the directory
- [ ] Run `npm install` to install your dependencies
- [ ] Type `code .` to open the project in VS Code
- [ ] `npm start` to start your server
- [ ] Plan your project by creating the tickets you will work through using Github Projects
- [ ] START CODING!

# MVP Requirements
[MVP Wireframe](https://www.figma.com/design/K9b5MxHU4yH77wygWdqmu3/Sports-Individual-Assessment?node-id=0-1&t=dZUzD5RjHc93J0r6-1)
- [ ] An ERD of your data
- [ ] Use Firebase for DB and authentication
- [ ] Technical Flow chart (timebox this)
- [ ] The app has a navigation bar that includes:
  - [ ] A Title/Logo (do not spend a ton of time on this until you reach MVP)
  - [ ] Logout button
  - [ ] Create Entry
  - [ ] Any other options you would like to add

**The most basic requirement for this project is that a user can:**
- [ ] Login and Logout of the application using Firebase Google Authentication
- [ ] only see the sports entries that they created
- [ ] CREATE a sports entry:
  - [ ] Title
  - [ ] Definition
  - [ ] Sport Name
  - [ ] Time submitted - Not on form. Handle in your JS
  - [ ] user ID - Not on form. Pull from User object.
- [ ] READ THIER entries
- [ ] UPDATE THEIR entries
- [ ] DELETE THEIR entries
- [ ] Filter by Sport Name
- [ ] Style your application using your own creativity!
- [ ] No errors - linters should be clean
- [ ] [ Wireframe](https://www.figma.com/design/K9b5MxHU4yH77wygWdqmu3/Sports-Individual-Assessment?node-id=0-1&t=dZUzD5RjHc93J0r6-1)
- [ ] Allow users to order entries alphabetically, newest, oldest


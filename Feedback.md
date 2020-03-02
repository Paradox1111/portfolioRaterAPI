# Project 3 Feedback

## Code Quality - Excelling

Criteria: Is the code well-formatted? Are variable and function names semantic and sensible? Is the code easy to read and understand?

### Strengths:

-   Code formatting and quality are impeccable! You all paid such attention to detail here, and I couldn't find a single console.log() or stray piece of pseudo-code.
-   Really nice formatting and spacing throughout the frontend and backend, that made the code very easy to read.
-   Variable names throughout are semantic and sensible, with consistent use of variable declaration key words and function syntax as well.

### Areas for Growth:

-   There are parts of the code that could benefit from having some comments, such as the handle login method in App.js, for example -- the logic of the count variable and how you're tracking your users wasn't immediately apparent to me there.

## Technical Requirements - Excelling

Criteria: How does the project stack up to the requirements for this project? Are the developers making use of the material we've covered in a way that makes sense?

### Strengths:

-   All technical requirements met: Full stack application with React frontend and Mongo/Express backend, fully deployed and functional.
-   EXTENSIVE history of commits in both repos, with good distribution between all team members. Git messages for the most part written in correct format and concise yet meaningful, present-tense singular verb
-   In React frontend, great job using class components for state-ful components and functional for the rest. CSS Grid incorporated in the UI and at least one test per component (as you learn more about React testing, consider coming back to write more complex tests for some routes).
-   Great structure in the Express API, with files organized according to MVC structure and tests for each route.

### Areas for Growth:

-   A fun thing to try out would be using Heroku's free scheduler feature and keeping the servers for both stacks awake during US business hours. This makes the app seem much more professional, when the user isn't waiting 15+ seconds for the web dynos to wake up.
-   Continue to build out the authentication piece to incorporate passwords! Other than that, no technical recommendations. :)

## Creativity and Interface - Performing

Criteria: Is the application easy to navigate? Does it work well in every major browser? Is it responsive? Does it incorporate modern UI Themes?

### Strengths:

-   The app concept is so creative, and such a great way to show off your technical skills and ALSO your very cool portfolios! Very smart to land on this idea, and then execute it so well!
-   Excellent job learning how to implement Bootstrap! The project's visual design has a very professional, clean, and cohesive feel. I love the fonts and logo as well!
-   The mobile view looks great. I love how the portfolio display goes down to one column, with each portfolio blurb fitting neatly into the screen view. The nav bar also appears to be resizing to adjust to the smaller window.

### Areas for Growth

-   I think the UI could be improved on the detail view if the format was side-by-side, with the portfolio clip on the left and the information on the right. A small change, but would keep the user from having to scroll down to see the summary, comments, rating and portfolio link.
-   I noticed y'all changed the favicon on the React frontend, which is awesome! But the image is really hard to decipher -- what is it? I would probably use something that's not a detailed image there - maybe black text that reads 'PR' on a blue background that matches your site's look.

## Functionality - Performing

Criteria: Does the application work without errors or bugs? Does it present a complete app, where every feature is fully implemented in a way that makes sense?

### Strengths:

-   The application works great, with no bugs identified!
-   Super user-friendly. Love how the create route is protected with the log-in popup. After logging in, login button automatically becomes logout.
-   The comment and likes features are also a great interactive, and very well-implemented!
-   Love how the nav bar highlights what part of the app you're in!

### Areas for Growth:

-   The loading message that says "Portfolio not loading?" is a bit distracting and alarming, when in fact we're just waiting on the API call to return data. Are there other loading displays y'all could use, and have a separate error message?
-   If you try to click on a protected route, the log in window pops up, which is great! However, after you enter your credentials, the page goes back to where you originally were instead of taking the user to where they were trying to go. Try refactoring so that after the user logs in, they're taken to where they're trying to go.
-   A confirmation message upon logging out would be great for UX as well.

## Presentation - Performing

Criteria: Is there adequate documentation? Is the repository well-organized and free of clutter?

### Strengths:

-   Your backend repo is very well-organized, with a planning directory and project structure organized according to the MVC architecture that we discussed in the Express unit.
-   Nice job with your backend README, including a screenshot, API endpoints, and a snapshot of your MongoDB documents and schema! This shows off all the hard work you all put into creating a robust API.
-   Your frontend README looks awesome! So engaging with the app screenshot, user stories, and an overview of the app itself.
-   Good organization in the frontend as well, with a planning repo and a components folder organized by individual components, which are accompanied by their own stylesheets and tests.
-   No extraneous files or clutter noted.

### Areas for Growth:

-   The API endpoints in the backend README could be organized a bit better, perhaps in a diagram or graphic, or Markdown table, to make them easier to read. I would also highlight the Mocha/Chai testing, including giving a couple examples of the cooler tests y’all wrote (there are a ton!), since TDD is hugely important!
-   In a similar vein, I would expand the frontend README a bit more as well, highlighting the great tests y’all wrote, sharing more screenshots of major app views (including the CRUD operations), and maybe even talking about how you incorporated principles of React into your application (unidirectional data flow, why you chose state-based components, life-cycle methods, etc.).

## Hard Requirements - Complete:

**Back-End Requirements:**

-   [x] Your back-end must be a Node, Express, and Mongoose API with at least 1 non-user models. No associations are required.
-   [x] You must have CRUD functionality built throughout the app
-   [x] You must have a test for each of your routes.

**Front-End Requirements:**

-   [x] Your front-end must use React and leverage the backend API in the above requirements.
-   [x] You must communicate with the back-end API RESTfully to Create, Read, Update, and Destroy resources.
-   [x] You must use either CSS Grid or Flexbox along with media queries to make your app responsive across mobile, tablet, and desktop widths.
-   [x] You must have at least 4 components and at least one test for each of your components

**Overall Project Requirements:**

-   [x] You must include a planning/ directory that sufficiently demonstrates your team's planning process.
-   [x] Both your front-end and back-end repos have a README that adequately documents the project.
-   [x] Every team member must have roughly the same number of individual commits in the commit history for your app (dividing responsibilities between different parts of the app is fine, but every team member must have commits in the project).
-   [x] Every team must follow a Git Workflow
-   [x] Every team member must speak for roughly the same amount of time during the group presentation

**Deployment Requirements:**

-   [x] Your back-end/API must be deployed to Heroku and your front-end must be deployed to GitHub pages or Heroku.

## Grade: Pass! Awesome work. 🎉🎉🎉😎😎😎

Overall, very well done. I can tell you all put a LOT of work into this application, and it is such a cool project to have in y'alls portfolios. I love the meta quality of the project, and how you used the technologies you learned in this course to make an app that will help show off your portfolios; it's also very generous to share the portfolios of your classmates, and providing a place to give and receive portfolio feedback is really such a cool service. Congrats on meeting all of the hard requirements and passing project 3! I know this team also had a wonderful group dynamic and workflow, which is a huge accomplishment in and of itself. Thanks for being amazing devs!

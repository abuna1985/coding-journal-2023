# coding-journal-2023

This is my coding journal for the year 2023. If you need to search for something specific, use `crtl + f` and enter the term in the search bar.

## Table of Contents

- [02/04/2023](#02-04-2023)
  - [02/04/2023 - Webpack Starter Project](#02-04-2023-webpack-starter-project)
- [02/17/2023](#02-17-2023)
  - [02/17/2023 - Sortable User Table Additional Requirements](#02-17-2023-sortable-user-table-additional-requirements)
  - [02/17/2023 - Vue Memory Game Additional Requirements](#02-17-2023-vue-memory-game-additional-requirements)
  - [02/17/2023 - React.js Real-Time Chat Application Requirements](#02-17-2023-reactjs-real-time-chat-application-requirements)

## 02-04-2023

### ***02-04-2023 Webpack Starter Project***

I needed to determine the SASS folder structure and how I am organizing my styling. I found the following files during my research phase

- [https://gist.github.com/AdamMarsden/7b85e8d5bdb5bef969a0](https://gist.github.com/AdamMarsden/7b85e8d5bdb5bef969a0)
- [https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4](https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4)
- [https://github.com/fransyrcc/starter-html-sass-js-webpack](https://github.com/fransyrcc/starter-html-sass-js-webpack)

For the next phase of my research, I wanted to have a clear variable naming structure. I found this article that I think I will use this strategy to ensure a clear separation from base/layout styling 

- [https://sandstorm.de/de/blog/post/bem-sass-scss-variable-naming.html](https://sandstorm.de/de/blog/post/bem-sass-scss-variable-naming.html)

Finally, I wanted a clear guide to properly import Google fonts in my sass files. I found this article in my research phase

- [https://www.developerdrive.com/how-to-easily-use-google-fonts-with-sass/](https://www.developerdrive.com/how-to-easily-use-google-fonts-with-sass/)

[back to top](#coding-journal-2023)

## 02-17-2023

### ***02-17-2023 Sortable User Table Additional Requirements***

- Add pagination capability
    - Add pagination options to the HTML table, allowing users to navigate through large sets of data easily.
    - Implement pagination on the client side by limiting the number of rows displayed per page and adding navigation controls (e.g., next, previous, first, and last).
    - When the user selects a new page, the project should call the API to retrieve the next set of data and update the HTML table accordingly.
    - Test the pagination feature thoroughly to ensure that it works correctly, even when there are large amounts of data.
    - To optimize performance, consider using server-side pagination to reduce the amount of data sent to the client.
- convert to webpack starter so scss/js can be utilized
- Add jest/mocha build unit tests
    - Install a unit testing framework such as Jest or Mocha.
    - Write test cases to ensure that the API is called correctly and the data is parsed and displayed correctly in the HTML table.
    - Test cases should cover different scenarios, such as successful and failed API calls, empty or invalid responses, and data with different properties.
    - Use test-driven development (TDD) approach to write code that passes the tests and refactor as necessary.
  
[back to top](#coding-journal-2023)

### ***02-17-2023 Vue Memory Game Additional Requirements***

- Appealing Animations: The user should be able to enjoy watching the background animations, which should be appealing to the eye and appropriate for the game's theme.
  - Smooth Performance: The animations should not affect the performance of the game or cause any lags or delays while playing.
- Customization: The user should have the ability to customize the background animations, such as changing the colors, speed, and style of the animations.
  - Toggle the button for Light/Dark mode
  - Toggle button for cowboy/forest theme
- Show dial to speed up/slow down tumbleweed/animal animation
- Button to disable animations
  - Would just show a static animal in the background for the forest theme (fade-in)
  - Would show tumbleweed in the background for the cowboy theme (fade-in)

[back to top](#coding-journal-2023)
  
### ***02-17-2023 React.js Real-Time Chat Application Requirements***

1. User Login and Registration: Users should be able to create an account and log in to the app with their email or social media account.
2. User Profiles: Users should be able to view their profile and update their profile picture, name, and other details.
3. Real-time Text Chat: The app should allow users to communicate with one another via real-time text chat, with the ability to send and receive messages instantly.
4. Audio and Video Calls: The app should allow users to make audio and video calls with other users, with the ability to switch between audio and video during the call.
5. Group Chats: Users should be able to create and join group chats, where multiple users can communicate with one another.
6. Push Notifications: The app should notify users of new messages, calls, and other events with push notifications.
7. Encryption and Privacy: The app should use end-to-end encryption for all messages and calls to ensure the privacy and security of user data.
8. User Blocking: Users should be able to block other users and report abusive or inappropriate behavior.
9. User Status: Users should be able to update their status, indicating whether they are online, offline, or away.
10. User Search: Users should be able to search for other users by name or email address to find and connect with them.

[back to top](#coding-journal-2023)
### Description

Create a [single page web app](https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58) that plays a game with the user to _read their mind_

For this project we will be learning about state management

### Table of Contents

<!--ts-->
- [Project/Exercise Name](https://GitHub.com/bootcamp-students/Resources/wiki/State-Managing-Mind-Reader)
- [Description](#Description)
- [Table of Contents](#table-of-contents)
- [MVP (Minimum Viable Product)](#MVP)
  - [Wireframe](#Wireframe)
  - [Tech Stack](#Tech-Stack)
- [Process](#process)
  - [Setup](#Setup)
  - [Application File Structure](#Application-File-Structure)
  - [Develop](#Develop)
  - [Deploy](#Deploy)
- [Requirements](#Requirements)
  - [Additional Requirements](#Additional-Requirements)
  - [Stretch Goals](#Stretch-Goals)
- [Additional Resources](#Additional-Resources)
<!--te-->

### MVP

By default, the app should prompt the user to click through the _single page app_ and see a new view for every step

You need to be able to scroll through the numbers to see your symbol (page 5 on the wireframe)

#### Wireframe

See [wireframe](https://xd.adobe.com/view/d4197d89-2c18-4e0e-5a01-c4ad9240fbc2-a228/)

#### Tech Stack

1. HTML
2. CSS
3. JS

### Process

#### Setup

1. Plan out and pseudocode your project - see [example kanban](https://GitHub.com/bootcamp-students/Resources/projects/10)
2. [Create GitHub repo (either online or locally)](https://GitHub.com/bootcamp-students/Resources/wiki/Git-Instructions), for example: `my-app`
3. Create necessary files for application and view in VS Code
4. Import and route necessary css/js files (E.g. Bootstrap)
5. Save all and create your first commit to `master`, **then** switch to a `dev` branch

#### Application File Structure

```raw
repo/
    index.html - main page
    css/ - folder to contain CSS files
        style.css - main stylesheet
    img/ - folder to contain any images
    js/ - folder to contain JavaScript files
        main.js - main JavaScript file
    README.md - any important information
    .gitignore - file that omits any directory/file from being tracked
```

Additional pages will be relative to the index.html file.

It is okay if your project has more files and directories, but you at least need the ones listed above.

#### Develop

1. Create a `dev` branch to commit your code to
2. Add content and elements to your website
3. View changes and test locally
4. Save often, and commit to your development branch on GitHub when important changes happen
5. Push your commits to GitHub remote
6. For bug fixes, refactored code, and feature branches, you must create a branch off of `dev` onto a `new-feature` branch and create a Pull Request into dev branch when complete

#### Deploy

1. Create a Pull Request from `dev` into `master`
2. Confirm code is up to date and works correctly
3. Link your `username.github.io` to point to your new project or add it to an existing portfolio in settings
4. Post a link to your GitHub Pages Site to the Projects Slack channel

---

### Requirements

To complete the assignment, you must complete the following:

1. Pseudocode the problem in its entirety before you start coding
2. Use JavaScript to successfully show the animation transitions
3. Successfully show state management for each step of the single page app( "view" 1, 2, 3, ..) without refreshing the page, this means that you will only create a single index.html
4. The restart button should not refresh the page, but rather, reset the state of the mind reader
5. Use Icons of your choice, we recommend [https://fontawesome.com/icons](https://fontawesome.com/icons)
6. All multiples of 9 should be the same symbol
7. Only one page is needed, manage state via updating a "state" variable that stores the current view to display

#### Additional Requirements

- You must Pseudocode
- Website must be responsive
- Website must be styled
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Wiki](https://GitHub.com/bootcamp-students/Resources/wiki/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Dynamically generate content using JavaScript
- Dynamically change CSS with JavaScript
- Use a Framework to generate the SPA

#### If you finish early

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.GitHub.com/PurpleBooth/109311bb0361f32d87a2)
3. Share links and resources from this week to the Resources slack channel.

### Additional Resources

- Ask questions :smile:
- Learn more about [Good GitHub Practices](https://guides.github.com)
- [W3 Schools - Learn JS](https://www.w3schools.com/js/)

For more information about single page web apps, see these articles:

- [W3 schools local storage](https://www.w3schools.com/html/html5_webstorage.asp)
- [Bootstrap hide element](https://getbootstrap.com/docs/4.0/utilities/display/#hiding-elements)
- [JavaScript Transitions](https://css-tricks.com/controlling-css-animations-transitions-javascript/)
- [Wiki page about SPA](https://en.wikipedia.org/wiki/Single-page_application)

# Instructions

Welcome! If you are reading this, it's likely because you want to work with us. If you have already applied, then continue on. If not, check out our [careers](https://newstorycharity.org/careers/) page to see our available openings. No software developer opening? Email us anyway!

The goal of this coding challenge is to allow us to see how you approach technical problems, architect a small application and work with existing API's. 

This should take about **3-5 hours** to complete, but please don't spend more than 5 hours on it.

Upon completion, a **public** Github URL should be emailed to the following email:

- [tim@newstorycharity.org](mailto:tim@newstorycharity.org)

## The Challenge

You will be creating a simple front-end application that will accomplish a few things. You'll need to use React JS for the front-end framework, but can use any CSS grid library to make stying a bit easier.

You'll be working with two different API's. 

1. [Google OAUTH](https://swapi.dev/)
2. [Star Wars API (SWAPI)](https://developers.google.com/identity/protocols/oauth2)

You'll work with Google Auth to estabilish a way for a user to log in to the application. 

You'll work with the Star Wars API (SWAPI) as your data source.

Feel free to utilize any libraries that make your work easier. Work smarter, not harder :)

## User Stories

Below is a list of User Stories that we would like to be able to accomplish in the final version of the application.

### **Part 1**

- As a user, when I view the root of the application, I should see a logged out state with a "Google Login" type button.
- As a user, I should be able to click the button and proceed log in with a Google Account.

### **Part 2**

- As a user, once logged in, I see my information on the page (name, photo, email).
- As a user, once logged in, I can view a list of Star Wars characters (/people)
- As a user, I can click on a character and see information about that character in a seperate routed view.

### **Part 3**

- As a user, I can "favorite" a character and view them on a "/favorites" page within the application.

Hint: To do this, you'll want to utilize local storage to keep track of this. A user should be able to log out and then back in and view the list. Also, multiple users on the same computer/browser should be able to see their seperate favorites when they log in.

## Styling

The core of this project is around the front-end code that you'll be writing, however please ensure that the project you turn in is easy to use and looks profesional. You can use Bootstrap, Tailwind, Bulma or any other CSS library to make this easier to accomplish.

## Suggestions

- Commit early and often. Your commit messages should be logical and show your train of thought.
- Use best practices when writing your code. Including, but not limited to:
    - Documentation/Commenting
    - Indentation and Code Structure
    - DRY Code
    - Unit Tests
- To get started with Google OAUTH, start at the [Credentials](https://console.developers.google.com/apis/credentials) page. You'll probably need to [create a new project](https://console.developers.google.com/projectcreate) to get started.

## API Docs

- [Star Wars API (SWAPI)](https://swapi.dev/)
- [Google OAuth](https://developers.google.com/identity/protocols/oauth2)

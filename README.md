# Instructions

Welcome! If you are reading this, it's likely because you want to work with us. If you have already applied, then continue on. If not, check out our [careers](https://newstorycharity.org/careers/) page to see our available openings. No software developer opening? Email us anyway!

The goal of this coding challenge is to allow us to see how you approach a technical problem. You will also get an introduction to our API. 

This should take about **3-5 hours** to complete, but please don't spend more than 5 hours on it.

Upon completion, a **public** Github URL should be sent to the following:

- [morgan@newstorycharity.org](mailto:morgan@newstorycharity.org)
- [tim@newstorycharity.org](mailto:tim@newstorycharity.org)

## The Challenge

You will be creating a simple front-end application that will accomplish four things. We ask that you use React as your JavaScript framework, but you can use any state library that you so choose. You will be hitting our existing backend API.

Our API is built using GraphQL, so you will need to interact with that via a GraphQL tool on the client side or by building an HTTP request with properly formatted JSON. Again, you can use any library you choose to help with this, and we have provided a template for making requests if you don't have experience with GraphQL.

We will provide you with an API token, login credentials, as well as some basic API and architecture documentation to help you get started.

### **Part 1**

- As a user, I should be able to open your App and log in with the credentials provided.

### **Part 2**

- As a user, once logged in, I can view a list of recipients with an indicator denoting that they have taken a survey (at least one submission belonging to the recipient).
- As a user, I can click on a recipient and see a list of all surveys they have taken (submissions belonging to the recipient).

### **Part 3**

- As a user, I can click on a submission and view the questions (in English, ie us_en context) and answers for that submission.

### **Part 4**

- As a user, I can click on a question to be taken to a "stats" page and view all multiple choice answers (from all recipients) and see the percentage of times that answer was chosen.

## Suggestions

- Commit early and often. Your commit messages should be logical and show your train of thought.
- Make use of libraries, but don't overuse any and don't rely on one to help with any core logic, like in **Part 3**
- Use best practices when writing your code. Including, but not limited to:
    - Documentation/Commenting
    - Indentation and Code Structure
    - DRY Code
    - Unit Tests

## API Sandbox

- API Endpoint: [`http://api-dev.newstory.io/graphql`](http://api-dev.newstory.io/graphql)
- API Key: (will be provided)
- Credentials (will be provided)
  
> **Note**: All requests should pass the API key as the `X-Api-Key` header. Also, after signing in, you should grab the user's `token` and pass it as the `Authorization` header for all subsequent requests.

## Resources

- [Documentation](./resources/Documentation.md)
- [GraphiQL](./resources/Documentation.md#choose-how-you-will-interact-with-the-api)

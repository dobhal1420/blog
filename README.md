# blog
# Overview

This document aims to provide you a structure for the front end interviews. It should be used more as a guide than a strict script.

Here are the suggested steps for the interview:

1. Quick round of introductions (current position, team, professional background, personal note) (5 min)
2. Encourage the candidate to talk about her professional experience and current projects (10)
3. Start with the technical questions (25 min)
4. Live Coding (30 min)
5. Candidate's questions (5min)

# Technical Questions

With the list of questions below, we try to cover some aspects which we believe are must-have's for the Senior Front End position. We also included a few nice-to-have's in the end, if you still have time to ask.

## Must-have

### Testing

1. What is the difference between a unit test and a functional/integration test?
2. What tools would you use to test your code's functionality?
3. What is the purpose of a code style linting tool?
4. What is your experience with E2E testing?

### React

1. What do you understand by Virtual DOM? 
2. What are the different phases of React component’s lifecycle?
3. How to prevent components from re-rendering?
4. What is a High Order Component? Could you give us an example of one?
5. What are React Hooks? Why should I use hooks?
6. How do you control state in React?

### Scalabe projects

1. What are some common anti-patterns you see in React projects?
2. When it comes to project structure, how to organize in a scalable way?

### Performance

1. What tools would you use to find a performance issue in your code?
2. How would you handle an investigation about performance issues in a web app?

### Abstractions

1. How to create useful abstractions to reduce boilerplate code without making the code fragile?
2. What does DRY mean to you and how do you apply it?

### Network

1. What are the differences between Long-Polling, Websockets and Server-Sent Events?
2. What are HTTP methods? List all HTTP methods that you know, and explain them.

## Nice-to-have

### Caching

1. What is a CDN and what is the benefit of using one?
2. How does the HTTP protocol help with Cache?

### Security

1. What are some best practices regarding security in web applications?
2. What are some main threats in web applications?

# Live Coding - JIRA Ticket

With this live coding session, we aim to evaluate the candidate's skills regarding React, CSS, JS and so on. We decided that presenting the task as a JIRA ticket could be a good idea since it is more similar to what we do on a daily basis at Forto. Below you can find the User Story:

**User Story**

> As a user,
> 
> I want to pass my credentials (email and password)
> 
> So that I can login into the system.

**Acceptance Criteria**

> Given the credentials are passed,
> 
> When the user clicks Sign Up,
> 
> Then a validation needs to happen. If one of the fields is empty, or if the email is not a valid email or the password is less than 8, an alert with an error message will be displayed. Otherwise, the user can login into the system and a success message should be displayed. The exact spacings, colors and sizes do not matter. They should roughly match. But the overall shapes should resemble the ones in the layout.

**Additional Criteria: (DO NOT SHARE WITH THE CANDIDATE)**

- Candidate knows how to center a box (vertical/horizontal)
- Preferred if they use modern methods to layout stuff (flexbox, css grid)
- Both inputs in a form
- Password field is of type password
- Button should be a button
- Semantic html
- (plus) gradient
- (plus) rounded corners

![fe challenge](https://user-images.githubusercontent.com/791485/52260839-9d3d1480-2927-11e9-8e10-e8825bc7c098.png)

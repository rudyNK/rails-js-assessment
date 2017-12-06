# Build a SPA with JavaScript and a Rails Backend

## Overview

In this assessment your will be building a SPA (Single Page Application). The frontend will be built using HTML, CSS and JavaScript. You will also be tasked with constructing your own backend API build with Ruby on Rails. The frontend application must communicate with the backend using JavaScript's native `fetch` function.

This is an exciting time, as this is will be a compilation piece of everything that you've learned in the program so far. As part of this, we want to stretch your autodidactic skills. You are going to learn how do create a full SPA, implement CRUD actions asynchronously, and build a dynamic application that shows off your skills with Javascript, can you learn these skills on your own?

## Requirements

 1. Must be a HTML/CSS/JS frontend with a Rails API backend. These *must* live in two separate repositories. All interactions between the client and the server should be handled asynchronously using `fetch`.

 2. Must contain CRUD actions for a resource with at least one has-many relationship (that's two resources total) in the JSON. For example, if we were building Instagram, we might display a list of photos with associated comments. Both resources should be editable.

 3. Must use your Rails API and a form generated by the client to create a resource and render the response without a page refresh. For example, if you create a new Photo post, and form data would be serialized, and submitted via an Fetch POST request, with the response being the new object in JSON and then appending that new photo to the DOM using JavaScript (ES6 Template Literals, can help out a lot with this).

 4. No user authentication with passwords. When the page refreshes the current user will effectively be signed out. The way you learned this in the previous module relied on the fact that Rails was sending small pieces of data (cookies/sessions) back and forth along with every request and response. Now, we have two separate applications and need to use a slightly different pattern. We'll look at patterns for dealing with client-side auth later in the semester, so you'll have plenty of time to deal with this case. If your application requires a user model you can have users "sign in" or "sign up" by providing a username and/or email, but hold off on passwords for now.

 5. jQuery is often helpful to use for DOM traversal and DOM manipulation and you are welcome, though not required, to use it. Remember that what you can do with jQuery you can do with vanilla JavaScript ( You Might Not Need jQuery ) if often a little less elegantly.

    Having said that we require that you use `fetch` and not `$.ajax`, `$.get` etc. Fetch is built into JavaScript now and you should get used to using it and dealing with some of it's quirks!  Going forward, we don't want you to get the wrong idea that you need to import the entire jQuery library to make a single AJAX request.

## Example Project Setup

[This repository](https://github.com/learn-co-curriculum/mod3-project-week-setup-example) goes through the first few steps of setting up an example project for both the frontend and backend applications. **Please spend some time looking through this before getting started**. If your question (ex: "How do i set up the `rack-cors` gem?") can be answered by reading this repository, you will be directed there.

## Instructions

1. Create a seperate repo for both your Rails API Backend App and your JavaScript Client App.
2. Add the spec-js.md file from this repo to the root directory of the JavaScript Client App, commit it to Git and push it up to GitHub.
3. Submit the JavaScript Client repo to the assessment immediately, but make sure to include the link to the Rails Backend API repo in the README.md file of the JavaScript Client App Repo.
4. Build your app there. Make sure to commit early and commit often. Commit messages should be meaningful (clearly describe what you're doing in the commit) and accurate (there should be nothing in the commit that doesn't match the description in the commit message). Good rule of thumb is to commit every 3-7 mins of actual coding time. Most of your commits should have under 15 lines of code and a 2 line commit is perfectly acceptable. **This is important and you'll be graded on this**.
6. Record at least a 30 min coding session. During the session, either think out loud or not. It's up to you. You don't need to submit it, but we may ask for it at a later time.
7. Submit a video of how a user would interact with your working application.
8. Make sure to check each box in your spec.md (replace the space between the square braces with an x) and explain next to each one how you've met the requirement *before* you submit your project.
9. Submit the url to your github project
10. Write a blog post about the project and process.

Unlike the rest of the curriculum, if you have any questions about your assessment or need help with it, please don’t use the Ask New Question feature. Rather than working with Learn Experts, please reach out to your Learn Instructor responsible for this section instead.

## If you're a Learn-Verified Premium student:

We should reach out to you soon to schedule a review. If you don't hear from us in 48 hours after submission, reach out to us on Slack!

### Be Prepared to:

1. Explain your code from execution point to exit point. We're making sure you wrote it and understand how it works, nothing else. 5-10 minutes
2. You'll be expected to provide expected return data of methods. You'll need to know how your code should work. 20-30 minutes
3. Refactor code. 20-30 minutes
4. Extend the application with a new feature, more data, a different domain etc. 20-30 minutes
5. Submit an improved version.
6. Write a README.md.

### What to expect from the instructor review

We have two goals for the instructor review. The first is to make sure that you understand, can talk about and can add to your code in real time - we want to make sure that you've really learned the material in this section. The second goal is to prepare you for technical/coding interviews when you graduate.

Your instructor wants you to succeed, but starting at the Rails portfolio project and on the portfolio projects after it, they're going to quite deliberately give you a bit of a harder time and be less obviously supportive during the portfolio project reviews so you get a better sense of the kind of experience and pressure that you might get when taking a technical interview. Unlike some technical interviewers, we really do want you to succeed, and we'll work with you as many times as necessary to get you through the review if you don't nail it the first time (which is quite common and completely OK). However, we will potentially give you a hard time, cut you off, push you on your use of vocabulary and/or your coding choices. We want to try to give you a sense of what a coding interview might be like, so you build the confidence to describe your app and to write code even in a higher pressure, slightly more adversarial environment.

Given this, don't be surprised if the instructor doesn't necessarily take the time to "teach" you anything you get wrong. As a rule of thumb, if the instructor has to teach you something, you didn't pass the project review! However, if you feel there was anything you didn't understand or would like to discuss, let the instructor know at the end of the session and they can suggest another instructor who will be able to pair with you on that to help you with your understanding before you retake the project review.

<p class='util--hide'>View <a href='https://learn.co/lessons/rails-js-assessment'>JavaScript SPA</a> on Learn.co and start learning to code for free.</p>

# [BEW 1.3] Course Review

<!-- omit in toc -->
## Table of Contents

1. [**Syllabus Updates**](#syllabus-updates)
1. [**Plan Improvements** <small>(<a href="https://github.com/Make-School-Courses/BEW-1.3-Server-Side-Architectures-and-Frameworks/tree/master/Lessons" target="_blank">🔗 All Plans</a>)</small>](#plan-improvements-smalla-href%22httpsgithubcommake-school-coursesbew-13-server-side-architectures-and-frameworkstreemasterlessons%22-target%22blank%22%F0%9F%94%97-all-plansasmall)
   1. [✅ Intro to Node](#%E2%9C%85-intro-to-node)
   1. [✅ JavaScript Tricks](#%E2%9C%85-javascript-tricks)
   1. [✅ HTTP Methods & Endpoint Design](#%E2%9C%85-http-methods--endpoint-design)
   1. [✅ Databases](#%E2%9C%85-databases)
   1. [✅ Data Modeling (Mongoose)](#%E2%9C%85-data-modeling-mongoose)
   1. [✅ TDD + Advanced Testing](#%E2%9C%85-tdd--advanced-testing)
   1. [✅ Authentication with JWT](#%E2%9C%85-authentication-with-jwt)
   1. [✅ More Authentication](#%E2%9C%85-more-authentication)
   1. [✅ Documentation (Docsify)](#%E2%9C%85-documentation-docsify)
   1. [✅ Putting it Together](#%E2%9C%85-putting-it-together)

## **Syllabus Updates**

- [x] Standardize syllabus based on the syllabus template: [Make-School-Courses/Syllabus-Template](https://github.com/Make-School-Courses/Syllabus-Template)
- [x] Update syllabus schedule and `_sidebar.md` to reflect new titles
- [x] Update schedule section for next term using provided tables in [Make-School-Courses/Syllabus-Template](https://github.com/Make-School-Courses/Syllabus-Template)
  - [x] Change dates
  - [ ] Update lesson titles

---

## **Plan Improvements** <small>(<a href="https://github.com/Make-School-Courses/BEW-1.3-Server-Side-Architectures-and-Frameworks/tree/master/Lessons" target="_blank">🔗 All Plans</a>)</small>

### ✅ Intro to Node

> 👀 **OVERALL**: Good base, needs more introductory JS content and skill drills.

#### OBJECTIVES

1. Write a route using Node and Express.js.
1. Use the Handlebars templating language to pass data to a template.
1. Compare and Contrast Express routes with Flask.

#### AGENDA

```txt
📖 [15m] Course Overview
📖 [15m] A Brief Introduction
📖 [15m] Review: How to Pair Program
💻 [50m] Lab Activity: GIF Search
📖 [30m] Review Node & Express
```

#### CHANGES

- [ ] Change title to `Getting to Know JavaScript`

---

### ✅ JavaScript Tricks

> **👀 OVERALL**: Lots of code examples and TT already exist; more skill drills and fun domains will help keep students interested.

#### OBJECTIVES

1. Use basic JavaScript constructs such as functions, conditionals, loops, and objects.
1. Read, understand, and use arrow functions to write shorter, more concise code.
1. Create and resolve Promises in order to execute code asynchronously.

#### AGENDA

```txt
Warm-Up: Observations (5 minutes)
JavaScript Fundamentals & Arrow Functions (20 minutes)
Activity: Pair Programming (15 minutes)
Intro to Promises (20 minutes)
Work Time: Codecademy JS (30 minutes)
```

#### CHANGES

- [ ] Rename plan to `Skills and Drills`
- [ ] Create some skill drills to make the class more interactive
- [ ] Gather inspiration from [javascript.info](https://javascript.info)

---

### ✅ HTTP Methods & Endpoint Design

> **👀 OVERALL**: Plan covers **middleware**, **routes**, and **nested routing**. Omits critical sections on REST, HTTP Methods, and how to design endpoints.

#### OBJECTIVES

1. Write a RESTful API using Express for one resource.
1. Identify best practices on designing routes, such as middleware and modular routing.
1. Practice pair programming techniques.


#### AGENDA

```txt
Activity: Write an API (45 minutes)
Review Messages API (25 minutes)
Activity: Design an API (25 minutes)
Overview: How to Use Postman (20 minutes)
```

#### CHANGES

- [ ] Rename plan to `Express Yourself`.
- [ ] Add section on
- [ ] Add section `Express in Production`
  - [ ] Who uses it?
  - [ ] How many websites run it?
- [ ] Introduce Express via serving HTML rather than JSON.
- [ ] Demonstrate Postman as soon as possible. Demo it with HTML first, then JSON.
- [ ] Rewrite the `Write an API` activity. Come up with a unique idea instead of utilizing someone else's tutorial.
- [ ] Remove references to `babel`; not in scope for an introductory lesson plan.

---

### ✅ Databases

> **👀 OVERALL**: Step by step code examples with descriptions for each instruction. Accurate technical information. Lacks a description of Mongoose or who uses it IRL.

#### OBJECTIVES

1. Use Mongoose models to represent data using a variety of types.
1. Use the find, findOne, etc. functions to query Mongoose objects.
1. Practice writing routes to return database objects.

#### AGENDA

```txt
Databases using Mongoose (20 Minutes)
Activity: Create an Events app (30 Minutes)
Activity: Tutorial Time (50 Minutes)
```

#### CHANGES

- [ ] Add section that introduces and describes Mongoose, which companies use it, etc.
- [ ] Compare and contrast this **wrapper** for MongoDB with projects that support other frameworks, like Flask.

---

### ✅ Data Modeling (Mongoose)

> **👀 OVERALL**: Appears to be missing or incorrectly linked on [make.sc/bew1.3](make.sc/bew1.3)

---

#### CHANGES

- [ ] Find or write plan

### ✅ TDD + Advanced Testing

> **👀 OVERALL**: Solid plan after combining TDD and Testing Express Routes plans and removing Advanced Testing content.

#### OBJECTIVES


1. Provide an introduction to unit testing with JavaScript.
1. Experience Test Driven Development and Behavior Driven Development first-hand through the use of Mocha and Chai.
1. Write unit tests for routes using the chaiHttp library.
1. Use describe() blocks to logically arrange unit tests.
1. Use the beforeEach() and afterEach() functions to specify test set-up and tear-down routines.

#### AGENDA

```txt
TT: Testing with Mocha & Chai  (30 minutes)
Overview: Behavior Driven Development (15 minutes)
Activity: BDD Practice (30 minutes)
Overview: Testing Controllers (20 minutes)
Activity: Write Route Tests for Messages API (50 minutes)
```

#### CHANGES

 - [ ] Combine TDD and [Testing Express Routes](https://github.com/Make-School-Courses/BEW-1.3-Server-Side-Architectures-and-Frameworks/tree/master/Lessons/06-Testing-Express-Routes) plans

---

### ✅ Authentication with JWT

> **👀 OVERALL**: Great bones but a bit high-level; add practical use cases and a hands on activity.

#### OBJECTIVES

1. Explain session-based and token-based authentication using real-world analogies.
1. Describe the 3 parts of a JWT token and their purposes.
1. Write code in Node.js to create and verify JWT tokens using the `jsonwebtoken` NPM package.

#### AGENDA

```txt
TT: Terms (5 minutes)
Video: JWT Concepts (25 minutes)
Activity: Analogies (5 minutes)
TT: JWT Format (15 minutes)
TT: Using JWT with Node.js (20 minutes)
Activity: Work Time (30 minutes)
```

#### CHANGES

- [ ] Add several examples of how JWTs are relevant to real projects
- [ ] Add visuals that reveal how JWTs are transmitted and stored
- [ ] New activity: Authenticate via JWT to Dani's Website

---

### ✅ More Authentication

> **👀 OVERALL**: Skeleton plan. Needs fleshed out with information and activities.

#### OBJECTIVES

1. Identify and describe different Passport.js strategies for authentication.
1. Contrast and compare Passport.js authentication strategies to JWT authentication.
1. Apply a Passport.js strategy of your choice to your Custom API project.

#### AGENDA

```txt
Overview / TT (30 Minutes)
In Class Activity - Passport Tutorial (60 Minutes)
```

#### CHANGES

- [ ] Add information about Passport and OAuth
- [ ] Add `Authenticate with Github` activity
- [ ] Rename plan to `Oh, Auth! One Click Login`

---

### ✅ Documentation (Docsify)

> **👀 OVERALL**: Good teacher talk but misses some key elements of why Docsify is useful.

#### OBJECTIVES

1. Define what Document Driven Development means with regard to software engineering.
1. Practice using Document Driven Development in conjunction with Docsify in order to kick off the Custom API project.
1. Deploy a live, autogenerated documentation website on Github Pages.

#### AGENDA

```txt
Activity: Custom API (25 minutes)
TT: Documentation Driven Development (15 minutes)
Activity: Create a Docsify Site + Deploy to GitHub Pages(30 Minutes)
```

#### CHANGES

- [ ] Add information about Docsify
- [ ] Add a video for the [code along](https://github.com/Make-School-Courses/BEW-1.3-Server-Side-Architectures-and-Frameworks/tree/master/Lessons/08-Documentation#everyone-do-code-with-me)
- [ ] Ask students to create a docsify site that documents their personal knowledge of a hobby or collectable.

---

### ✅ Putting it Together

> **👀 OVERALL**: Covers the technical aspects of deployment, but lacks TT and engaging activities.

#### OBJECTIVES

1. Push your project to production using Heroku
1. Progress on your final project

#### AGENDA

```txt
Activity: Deploy to Heroku! (45 minutes)
Project Work Time (50 minutes)
```

#### CHANGES

- [ ] Write precise learning objectives
- [ ] Create a simple express project for students to deploy
- [ ] Add a video for the [code along](https://github.com/Make-School-Courses/BEW-1.3-Server-Side-Architectures-and-Frameworks/tree/master/Lessons/12-Deployment)


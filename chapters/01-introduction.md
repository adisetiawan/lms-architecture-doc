# Introduction

This document provide high level overview and explains the application architecture for Learning Management System for multiple platform including but not limited to web based application and native mobile application. 

## Chapter Explanation

* Chapter 2 provide context diagram for high-level overview in related with Actor or persona which interact with the whole system.
* Chapter 3 provide container diagram for more detailed interaction of software architecture and system flow for each container.
* Chapter 4 provide component diagram to zoom in for each container and how it related to each other and interaction between components inside and outside container.
* Chapter 5 provide class diagram for entity relationship and also system landscape deployment diagram.
* Chapter 6 provide timelines and resource allotment for development phase.
* Chapter 7 provide technology stack choices and references.

## Goals and Constraints

* The system should be able to scale horizontally in real-time for any amount of traffic including spikes during N periods of times.
* The system should use any open source technologies and/or frameworks to avoid third party vendor lock.
* The system should be able to anticipate any future changes without doing major rewrite or refactors.
* The system should be resilient and secured by default with proper CI/CD deployment.

## Features Overview

Learning Management System is a platform for organizations such schools, campuses or education institution to host their whole operation into one single platform which can be accessed either via web based application or native mobile application.

### Core Features

* Student/Mentee management
* Teacher/Mentor management
* Class/Study group management
* Assignment/quiz management
* Video conference
* Audio conference
* Event calendar
* Payment system
* Notification system
* Multi languages interface
* Search system

### Actors

* Student/Mentee
* Teacher/Mentor
* Class/Study Group Administrator or Organization Owner
* Class/Study Group Moderator
* Parent/Viewer
* Super Administrator

### User Features

* Registration using social media accounts
* Membership with payment subscription

### Class/Study Group Features

* Visibility can be: public (searchable) or private (can be accessed within organization only).
* Each Class/Study group can have newsfeed/announcements, event calendar (for video conference audio conference, assignments/quizzes deadline).
* Each Class/Study group can have resource learning (documents, e-books, videos) for student to view, watch or download.
* Search system for resource learning and newsfeed.
* Notification for upcoming assignments, quizzes, new announcements, and test result.

### Assignments/quizzes features

* Online test means the student should run the test in real-time with limited n times to finished.
* Offline test means assignments with specific deadline to be collected and can be worked offline by upload the test to the system.
* Teacher/mentor will receive notification if there are any completed assignments.
* Student and/or parents will receive notification if the result come-up

### Resource Learning features

* Class/Study group moderator or/and teacher can upload any document for learning purposes and pin those documents the most important ones.
* Student can download or view online
* Student can search resource learning based on keywords or document types
* Student will receive notification if there are new document uploaded

### Event Calendar

* Display all events and deadlines including assignments created and deadlines, video or audio conference event.
* Integration with third party calendar such Google calendar, Microsoft calendar.

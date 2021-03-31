---
layout: essay
type: essay
title: "Final Project Idea"
date: 2021-03-30
labels:
  - Software Engineering
  - Meteor
---

Created by Germaine Juan, Adam Parrilla, Chad Oshiro, Joshua Paino, Kha Bui, Mark Young

## Overview 

*The Problem:* In many cases, having access to supplementary learning material can be the difference between receiving an A in a course or a C. It can be very time consuming to search and filter for useful information. Additionally, students may have self-created material or old material that is no longer available that may be of benefit to other students.

*The Solution:* The “Give and Take” application allows the UH community to pool in resources and online findings under one application that can enhance their understanding for their various classes.  Specifically, students will be able to create a profile, select courses of interest, and then any supplementary material uploaded by other users will be available to the user. The user can also upload material of their own to make available to the other users.

## Approach

The site has two user roles, the regular user and the admin user. The admin has the power to remove items from the site, in the case that inappropriate items are uploaded, such as answers to homeworks or tests or potentially copyrighted material.

Each user account will have a different state because each user will have items that they have uploaded and items subjects they are interested in.

Mockup Pages include:
- Landing Page
- Sign-In / Sign-Up Page
- Admin Home Page
- User Profile Page
- View Your Items
- Add/Edit your Items
- View Recommended Items
- Browse by search
- Browser by class or user

## Use Case Ideas
Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

- A person goes to the landing page, clicks to create a new account. The new user enters their profile information and submits. The new user is taken to their profile page. They then click to Add/Edit items and are taken to the Add/Edit items page. They go to the add url option and include a url to a youtube video that was useful to them. Then they tag it as ICS 314 and include the title JavaScript Classes.  They add a small description on what it is and how it can be helpful. They hit submit.  They then are able to view it in their profile as well as the page that displays all external material provided by other users that have been tagged with ICS 314. Then they click the Sign out button.
- An Admin user logs in. Then they view the list of all users. They click on a user. Then click to view that user’s items. They click on one item. The admin then notices that the item is a list of the answers for a test and was flagged as inappropriate by other standard users. So the admin clicks to edit the item. And then clicks to delete the item. An automated message gets sent out to the user who contributed the item and notifies that their item has been removed. 
- A regular user can also search classes and favorite them for later viewing.  Each class will have a collection of contributions from other students.  Each contribution displays the material itself, the user who provided it, a small description, and a possible overall rating determined by other users.
- Regular users can also view their own profile which displays their bio, a list of their contributions and reputation which is the average ratings of all their contributions.  Other people can view profiles of other users and see their reputation in order to gauge the quality of their contributions.

## Beyond the Basics

- Rating system for various materials that contributes to a reputation system for the users.
- Uploading system for various items such as PDF’s, mp4 videos, powerpoint presentations, external links, etc.
- Notification system for when people leave ratings or when admins have removed a contribution.

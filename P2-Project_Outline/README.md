# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
My project / app, Dinner Circle, is a meal planning application with an integrated shopping list, pantry check feature, and social integration.

The main component of the app will be a 7-day meal plan that auto clears with reminders to add new meals each week, tracks things like number of times / last made, and will be filterable by ingredient or meal type. As the user fills out the meal plan, the "pantry check" will populate with total quantities of each ingredient needed, and the user will then be able to add those items to the integrated shopping list.

Social features will be added to allow users to add friends, suggest meals, and see what their friends are making, along with "reacts" and comments.

This app idea sprang from a conversation with my wife, who plans meals on a whiteboard each week having not yet found an app that meets all her needs. "Pantry Check" and the shopping list also came from the conversation, just simply asking what her pain points were with planning and grocery shopping.

### Features
 - User Login: Users will have unique logins to track meals, lists, friends, etc, as well as "family account" integration.

 - 7-Day Meal Plan: Users will be able to add meals to a meal plan for the upcoming week.  Meal plan will clear each week and remind users to add meals for the next week.

 - Search / Filter: Users will be able to filter meals by ingredient, last made, number of times made, and meals marked as "favorites".

 - Create / Edit / Remove Meals: Users will be able to create and edit meals from scratch, as well as some Pinterest API integration.

 - Shopping list: Users will be able to add items to a shopping list.

 - Pantry Check: As users add meals to their meal plan, totals of each ingredient needed will update for the user to check stock and be sure they have enough, or add the ingredient to the shopping list.  

### Technologies
 - Java
 - Spring Boot
 - Thymeleaf
 - Hibernate
 - Thymeleaf Templates
 - Spring Security
 - Some sort of social media - like framework, possibly Stream?
 - Database capable of images, not sure that MySQL is the right choice here.

### What I'll Have to Learn
 I will need to for sure learn OAUTH login integration, very likely a new database, and a how to build/integrate a social framework. I will also need to learn how to clear the meal plan on a schedule, as well as sending user notifications (probably by email?).

### Project Tracker
 - https://trello.com/b/A2LqKRKq/meal-planning-app
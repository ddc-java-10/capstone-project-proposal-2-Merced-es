---
title: Budget Manager
description: "Managing and tracking your budget as a group or family."
layout: default
---

## Summary

An Android app that helps groups of people manage and track their spending. Users will create categories for bills, gas, groceries, dining out, miscellaneous, personal spend, savings, and any other categories of their choosing. Personal and group savings goals can also be created for any duration of time.
Each user in the group will enter all transactions made on a daily basis. Bills can be entered and split up between the members of the group according to whatever is agreed upon. The due dates and any notes can be entered for each bill for organizational purposes. Budgets can be made for categories like dining out and personal spend. The app will send notifications to a user when they have spent half of their budget and again when they have spent 3/4 so they can rethink their spending depending on how far along they are in the month. 
## Intended users

Write a bullet list here, including at least 2 different types of intended users. Make it reasonably specific; simply saying "Anyone who likes games" (for example) is not sufficiently specific.

For each type of intended user, include at least 1 _user story_. A user story is usually just 1 simple sentence (no more than 2 sentences), in the voice of the intended user, stating a specific task that the user needs to perform, and the benefit that will be obtained. The simplest user stories take the form 
* A person who feels like they never have any extra money.

	> As someone who has more month at the end of their money, I need an app that will track my spending and help me budget.

* A family member who is saving for their portion of the family vacation coming up next year.

	> As someone saving for a family vacation, I am looking for an app that will help me calculate what I can save each month to pay for it.

## Client component

* **Functionality**

    The user will be able to log savings goals and daily spending. They can document their monthly expenses on a chart and calculate them in total. The user can also set up notifications to prevent them from exceeding their budget.

* **Persistent data**

    The user will be able to see the expense chart they have created, as well as a summary of their budget which was updated the previous day. The savings goals a single user or group have will also be stored within the app.
    
* **Device/external services**

    * Calculator
	* Messaging
	* Notepad
	* banking API (stretch goal)
	* Google Sign in
	* Google chart/graph generator API
		-https://developers.google.com/chart
    
## Server component

* **Functionality**

Key functional aspects of the server include daily data and progress updates, expense budgets, and group goals.
    
* **External services**

* The banking API would be an external service that would easily track all transactions in an account. This would take away the work of manually logging all money spent each day. 

    
## Stretch goals/possible enhancements 

The banking API is a stretch goal that would allow access to a user's bank acount to track transactions. This API would allow for less manual data input on the user's end. The banking API would also require special security measures to ensure confidentiality.
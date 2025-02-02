# MyLife

Author - Dhruv Gupta
Date Started - 1/02/2025

Purpose - This is a side project I thought would be cool for my own use and some of my friends if it works well.

NOTE: This is just ideation for now. Nothing has yet been implemeted and the description is still rough as well.

## General Purpose

This system has a general purpose to essentially grow alongside you and after monitoring your behaviour via keyboard inputs or voice inputs, be able to help you with your daily life and take better care of yourself.

## Tasks to Accomplish and Plans

### Priority Scheduler

<u>Description:</u> 

- Takes the to do list from the user
- Takes the time from the user i.e a window for when the user is free throughout the week
- Takes a note of the tasks the user completes and does not complete throughout the week and generates new tasks which are better attuned to the user and the tasks are divided in a way the user is more likeky to complete.
- If not possible to optimize more then asks user for another time slot and if the user says no then tries to reduce durations for adjustments.
- Hands out a productivity chart for the user to track their progress for motivation.

<u>Requirements:</u>

- <i>Database System:</i>
- - Users access (static) - users that are present using the system.
- - To_DO (dynamic) - stores the tasks that are meant to be scheduled. NEW FOR EACH USER.
- - Timings (dynamic) - used to store timings for each user and how productivity is changing and convergence. NEW FOR EACH USER
- - General_Timings (static) - used to store timings which are generally considered productive by all the users and gets updated based on weekly tracks.

- <i>Frontend System Design</i>
- - <-will add later->

- <i>Backend System Design</i>
- - <-will add later->

### Food Mapper/Meal Maker

<u>Description:</u>

- Will ask the user to choose from the available options which will be at first simply the most popular and high rated items from the users in general. It will still have all the items at your disposal based on a category system.
- A user will have their own category system and the food will be sorted based on that. Note initially we will create the generic categories only and then options of category manipulation will be available. This is so that if the user wants to find a specific item they can easily find it. 
- A user will be able to add a new item which is not at present within the database and may/maynot assign it a category at first. The cost of the item needs to be filled for the FINANCIAL TRACKER to be able to do it's job.
- Each day after studying a person's preferances and food habits the FOOD MAPPER is supposed to propose a meal. The user may accept it or modify it. The modifications will be noted by the food mapper to see what combinations of food does the user like and on what day.
- The food mapper will recommend new things to try and to expand the diet of the user. If the user does not want that they can turn off this function. But nonetheless the foodmaker will try to pick a new type of dish for each day so as to not make the diet monotonous and keep it a diet the user would like.
- We will ask the users to mark the flags to whether a food is healthy or not when entering a new food item and thus it is highly recommended you don't lie to the system for your own benefit.
- Any new item that the user adds will be stored in their own little space for that particular user and will not affect other users. The general list of items will be uploaded by the admins.
- Even though a meal schedule is prepared by the meal maker it will monitor the timings you log into MyLife and based on that decide when you have your meals aside from your usual entered timing for a meal.
- A user will be able to turn off food transactions for the time they wish for and can enable transaction tracking anytime. 
- If a lunch or dinner is missed then we will not count that input for the day.
- There will always be an option of order acceptance and then a bill. A user will be able to adjust the bill to the true amount or say that I did not have to pay. Please update the values of the food items that can be updated to ensure perfect bill. This part will be handled majorly by FINANCIAL TRACKER.


<u>Requirements:</u>

- <i>Database System</i>
- - Menu (static) - base menu for all users updated by the admins 
- - Categories (static) - base categories that cannot be manipulated except by the admins
- - User__-Menu (Dynamic) - for the user to manipulate at his/her will
- - User__-Categories (Dynamic) - categories for the user to manipulate for him/her-self
- - Favourites (Dynamic) - built slowly as the user starts to accept meals
- - Ordered (Dynamic) - Per day updated with the items that the user selects for his/her meals.

- <i>Frontend System Design</i>
- - <-will add later->

- <i>Backend System Design</i>
- - <-will add later->

### Shopper

<u>Description:</u>

- It will contain a list of sites and sites that you can add separately in your own user space. These sites will be tagged based on how often you accept recommendations from these sites.
- The items will have a buying date and an exit date. Based on the frequency of similar items brought in the shopping list categories you make we will put the items in a shopping cart ready to buy and this should in theory help in reducing the burden of you remembering what to buy and not buy and plan out everything on time.
- It will recommend items to you in your shopping list and is essencially a recommending algorithm which will predict when you need something based on when you buy something.
- We will also ask you to put a star rating of the product so that we can calculate how popular and useful it can be to everyone.

<u>Requirements:</u>

- <i>Database System</i>
- - Sites (static) - sites like amazon and their products which are popular and will be uploaded by admins.
- - User__-Sites (Dynamic)- sites which the user has verified themselves and wish to conduct buisness with.
- - Items (static)- contains the items that are provided by admins
- - User__-Items (Dynamic) - contains the items user adds by him/her-self
- - Categories (Static) - categories provided by the admins
- - User__-Categories (Dynamic)- categories added by the users.
- - Buying_Schedule (Dynamic)- contains the bought items, the buying cost, buying dates
- - Cart (Dynamic) - to monitor and store the various things the user might need eventually.

- <i>Frontend System Design</i>
- - <-will add later->

- <i>Backend System Design</i>
- - <-will add later->

### Music Jammer

<u>Description</u>

- <-will add later->

<u>Requirements</u>

- <i>Database Systems</i>
- - <-will add later->

- <i>Frontend System Design</i>
- - <-will add later->

- <i>Backend System Design</i>
- - <-will add later->

### Peak News

<u>Description</u>

- <-will add later->

<u>Requirements</u>

- <i>Database Systems</i>
- - <-will add later->

- <i>Frontend System Design</i>
- - <-will add later->

- <i>Backend System Design</i>
- - <-will add later->

### Financial Tracker

<u>Description</u>

- <-will add later->

<u>Requirements</u>

- <i>Database Systems</i>
- - <-will add later->

- <i>Frontend System Design</i>
- - <-will add later->

- <i>Backend System Design</i>
- - <-will add later->

### Vacation Recommender

<u>Description</u>

- <-will add later->

<u>Requirements</u>

- <i>Database Systems</i>
- - <-will add later->

- <i>Frontend System Design</i>
- - <-will add later->

- <i>Backend System Design</i>
- - <-will add later->

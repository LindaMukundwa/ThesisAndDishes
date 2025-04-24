# 🎓 Thesis & Dishes 🍝

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

Thesis & Dishes is an iOS app for college students to navigate meal prepping for those who want budget friendly and time crunch meals. The slogan is "No pHD in cooking required"

### Description

Thesis & Dishes is an app built for the experience that college students go through with choosing healthy meals on a budget and a time crunch so this app can help achieve all of that and more. Students can filter through meals, time and complexity to get the best experience and nurtritional value. 

### App Evaluation

[Evaluation of your app across the following attributes]
- **Mobile:**
- Real-time filtering: Users can adjust sliders (time/price/expertise) for instant recipe updates.
- Push notifications:  Reminders to meal-prep (e.g., *"Your saved ‘15-min pasta’ is perfect for tonight!"*).
- Camera integration: Possibility to scan pantry items (via OpenFoodFacts API) to suggest recipes.
- Location-based: Can possibly show nearby grocery deals on ingredients (if you add a grocery API like Kroger or Walmart).
- Offline mode for saved recipes (important for dorms with spotty Wi-Fi).

- **Story:**
- Clear audience for college students overwhelmed by cooking and budgeting.
- Differs from other apps because of my niche: student time/budget constraints.

- **Market:**
- Large user base
-  20M+ college students nationally and 254M+ globally
  
- **Habit:**
- Perfect for weekly meal-prep which is 3–5 uses/week
- Users can save recipes making them return
- Possibility for a streaj counter *"5 weeks of meal-prep—treat, yourself to ice cream!!!"*

- **Scope:**
- Stripped down version still works with the 4-screen app using Edamam API and basic filters.
- Edamam’s free use allows 10K calls/month which is more than enough for testing
- The real-time filtering needs clean API data structure as well as the other stretch features but I would like to continue this past this class.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can browse recipes filtered by time and skill level
* User can save/unsave recipes
* User's saved recipes can be accessed locally (no login needed for MVP)
* User can view full recipe details

**Optional Nice-to-have Stories**

* [fill in your required user stories here]
* User can scan pantry items
* User can plan weekly meals
* User can receive meal-prep reminders
* User can receive push notifications

### 2. Screen Archetypes

1. Login Screen
User can log in with email/password
Navigate to Registration Screen

2. Registration Screen
User can create a new account

3. Home Feed (Stream)
User can:
View recommended recipes (filtered by time/price/skill)
Tap a recipe card to view details
Save/unsave recipes (heart icon)

4. Recipe Details Screen
User can:
See full ingredients/instructions
Navigate back to Home Feed

5. Saved Recipes Screen
User can:
View all bookmarked recipes
Delete saved items
Tap to open Recipe Details

6. Search Screen
User can:
Filter recipes by:
Time, skill level, price range
View results as scrollable cards

7. Profile/Settings Screen
User can:
Adjust dietary restrictions
Log out

### 3. Navigation

**Tab Navigation and Flow Navigation** (Tab to Screen)

Login Screen

=> Home Feed (after successful login).

Registration Screen

=> Home Feed (after account creation).

Recipe Discovery Screen

=> Recipe Details Screen (when a user taps a recipe card).

Recipe Details Screen

No further nav (MVP), but future versions could include:

=> Comments/Reviews Screen

=> Favorites Screen (auto-generated from saved).

Settings Screen

=> Home Feed (after saving preferences).

**Flow Navigation** (Screen to Screen)

## Wireframes

[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>
![IMG_2934](https://github.com/user-attachments/assets/8fd4b539-fa7e-43dc-8810-6d1df2612a7e)

### [BONUS] Digital Wireframes & Mockups
Here are some additional wireframes I did using Figma and Looka!

![0 - B - Launch Welcome Screen](https://github.com/user-attachments/assets/0daa44b5-7741-4c0b-a01e-ff6c0c25f985)
![3 - A - Home Page](https://github.com/user-attachments/assets/02b7ebb7-6e96-4001-bf2d-b59c92a0da43)
![4 1 1 - F - My Orders - Completed Order](https://github.com/user-attachments/assets/8a5a0679-5d63-4714-a48e-6bc77e3713e5)
![4 1 1 - I - My profile](https://github.com/user-attachments/assets/4c3266e6-2fa8-4aa5-8a25-51cfaa1e5c07)
![6 - A - Best Seller](https://github.com/user-attachments/assets/1a5546e4-d5c0-4d7c-84e9-68fe1e675a6b)


### [BONUS] Interactive Prototype

Here is a link to a demo of the progress so far [https://imgur.com/a/8kvHlsW].

[This project is ongoing]

# Project Introduction

<font size=4>

Companies wants to know how people feel about their service, which could be helpful for their development.

We provide this web app, let companies could send questionnaires via emails (designed by themselves, but we also provide templates if they like) to all their cutomers. 

Then our server collect the feedback and provide related statitics data to these companies.


</font>

# Tech Stack

- User signs up via Google OAuth: Express server + MongoDB + PassportJS

- User pays for email credits via stripe: Stripe + MongoDB

- User creates a new survey: React + Redux

- User enters list of emails to send survey: React + Redux + Redux Form

- Surveyees click on link in email to provide feedback: Express + Mongo

- User see report of all survey responses: Mongo + React + Redux

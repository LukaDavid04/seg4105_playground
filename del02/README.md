| SEG 4105  | Deliverable 2                                                                      |
| --------- | ---------------------------------------------------------------------------------- |
| Student   | Luka David, 300134324, ldavi029@uottawa.ca                                         |
| TA        | Shabnam Hassaniahari, shass126@uottawa.ca <br> Ali Mirferdos , smirf045@uottawa.ca |
| Professor | Andrew Forward, aforward@hey.com                                                   |
| Course    | Software Project Management, Fall 2023                                             |

# Group Submission:

**This README is just to provide my notes for before and after the betting, My group member wasn't able to update the submission to include a link to this page.**

https://github.com/andyung17/seg4105_playground/blob/main/del02/README.md#seg4105---delierable-2

Our group submission is the link above. The group submission for Team 23 includes all the necessary information for this deliverable. Our Meeting minutes are below.

https://github.com/LukaDavid04/FitShare/blob/main/Minutes.md#meeting-date-2023-10-12

## FitShare - Overview

We want to create a gym web-application for those who are looking to start working out or share their own workouts. The application will function similar to how spotify users share playlists of their songs. Users will be able to follow their friends or other creators and view the various exercises within their workouts. Within the application, each workout will track the reps and sets of the different exercises. Over time users will be able to see their improvements such a new personal records or goals that have been accomplished. Workouts will also provide information such as the number of calories that have been burned. Exercises will also have a visual demonstration to ensure the client is following proper form. The product will be targeting all levels of fitness knowledge.

## Planning

### Location (Betting and Kick-Off)

Meeting will take place over discord, in a voice call where people will have the ability to share their screen.

### Time

Betting took place on Thursday, October 12th at 2:00 PM ET. Kick-off will take place on Thursday, October 19th.

### Expectation

All participants need a prepared pitch, as well as notes on each other members pitch. They need to be prepared to ask questions and pick a winning pitch.

## Feature - Social Interaction

This feature represents how users will interact by way of following one another. This will be initiated when users decide to follow each other accessed through the search page, they will then be able to see each other's workouts and routines (If they choose to make this data visible). Lastly they will be able to add their friends workouts to their own account for personal use.

![Social Feature Breadboarding](image1.png)
![Social Feature Fat Marker Sketch](image.png)

## Winning Pitch

One of the hardest challenges of a healthy lifestyle is having regular activity on a week to week basis. Most people struggle to find motivation to be active or lack the knowledge of what to do. It is difficult to hold yourself accountable, and most people don't want to invest the resources to have someone teach them the basics of exercising on a regular basis.

This feature needs to be completed within 4 weeks and should enable access for searching the database of users with the option of following accounts of choice. The search page needs to be simple enough to provide the user with a quick and easy method to find their friends. They will also be able to access who they follow and who follows them on another page. This feature needs to be implemented within the frontend and backend of our FitShare application.

Users should be able to view their friends accounts who are public through a search page and be able to follow them in one click. Once they are followed if the user has visible workouts or routines, they should be accessible to all of their followers. They should also be able to save their friends routines and workouts to their own account. Lastly, they should be able to view all their friends and followers within their account page.

It is important that the search results can easily provide accounts that the users are searching for. They should not be too strict or too loose. Time and resources should not be spent on adding additional features such as editing other people's workouts. Simply saving a workout to your own account will encompass the basic social aspects within this feature. Also, there should not be difficult backend logic considered when following or receiving followers. Both aspects of the feature should be simple for the user and relatively simple to implement.

Incorrect search results as well as bugs with following users will create significant issues for our application and would be considered incredibly detrimental. The following and follower mechanics should be well tested to prevent such issues. Also keeping private users data private, is a critically important aspect of this feature. If any unwanted data is made public it could be seriously detrimental for the project.

## Notes (Prior)

### Andy - Workout Generation

- Workout generation is targeted towards gym users
- Convenient and informative alternative to creating your own workouts
- How will the algorithm create these playlists?
  - Will it have a certain amount of randomness to provide variation?

### Khai - Sessions

- This be a modification to the old sessions we had implemented in our previous version
- This will primarily follow gym users
  - There won't be capabilites for other forms of exercise such as running or swimming
- How much resources will we spend on the user interface
- Backend, will need more resources to complete

### Avaneesh - Log in

- How does it compare to our current implementation of the log in page
- Seems very simple in principle
- Would this be just the UI?
  - Does this factor in backend
- Does not include whether they can create an account
- Does not use real emails or validation for emai;s

### Adhish - Calendar

- How far back would the calendar be able to go?
  - Seems like it would only show certain dates within the week
  - Showing far back information could cause a lot of data to be stored in the database
- How much of the screen would this widget take up
- Would this take the projected amount of time, if only one person can work on it
- How would we deal with the new types of data

## Notes (Post)

### Andy - Workout Generation

- Workout generation is a solution for people with little knowledge of the physical activity space
- Can create based on a survey from user input
- Will require an algorithm to generate the workouts, based of exercises within a database
  - Algorithm would not be complex, just use probabilites based on responses
  - Workout information will not be saved
  - Will address variability in changelog

### Khai - Sessions

- Sessions is a solution for users to interact with the application and easily follow workout
- This will be a UI that prompts the user with exercises they then scroll through
- Information will be tracked in real time, passing into the database
- The idea is that the data can also be more easily or accurately stored
- Would be an improved version of the previous implementation
- Would require more work from frontend and backend to complete

### Avaneesh - Log in

- Sign up or log in is a solution to individualize accounts to store information for workouts
- It's a fairly commmon feature that is standard among projects, howevever it is not as easy to implement
- One of the main difficulties will be saving and storing the data and making sure authentication is secure
- It does not currently support email verification

### Adhish - Calendar

- Calendar is a solution that implements tracking data through dates
- It would only show the most recent dates in the week
- This will allow information to be stored in a history like aspect for easy access and reuse
- This ties into features such as strat tracking as you can view progress with the new data being tracked over time
- this is mainly a challenge for the frontend as many pages are needed for saving workouts, selecting dates etc
  - Also would be a challenge for backend to store all this information efficiently

## Questions (For Andy)

What will happen when users provide the same parameters or want more variation? If a user goes through routines or workouts and uses the same parameters will there be variation?

## Answers

For more variations, there should be some sort of option to select certain workouts and ask/recieve similar workouts with some variations to it that follow similar criterion. If a user would to exactly answer the survery with the same parameter, it would indeed generate the same routine and workouts as it still is recieving the same criterion and does not generate based on randomness. Instead some sort of option should allow for filter or searching for similar workouts based on similar parameters.

## Group Members and Resources

|       Name        |        Email        | Student Number |       Current Role        |
| :---------------: | :-----------------: | :------------: | :-----------------------: |
|     Andy Ung      | aung015@uottawa.ca  |   300117710    |     Business Analyst      |
|    Luka David     | ldavi029@uottawa.ca |   300134324    |      Project Manager      |
|     Khai Tran     | ktran093@uottawa.ca |   300112587    |         Architect         |
| Avaneesh Madaram  | amada034@uottawa.ca |   300130329    |      Lead Developer       |
| Adhish Maheswaran | amahe023@uottawa.ca |   300133918    | Quality Assurance Manager |

- Andy: https://github.com/andyung17/seg4105_playground/tree/main/lab03
- Khai : https://github.com/khaiqtran13/seg4105_playground/tree/main/lab03
- Luka: https://github.com/LukaDavid04/seg4105_playground/tree/main/del01
- Adhish: https://github.com/adhish2001/seg4105_playground/tree/main/deliverable01
- Ava: https://github.com/AvaneeshM/seg4105_playground/tree/main/lab03

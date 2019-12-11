# Social Media Calendar App

 - [Project Abstract](#project-abstract)
 - [Project Description](#project-description)
 - [User Stories and Design Diagrams](#user-stories-and-design-diagrams)
    - [User Stories](#user-stories)
    - [Design Diagrams](#design-diagrams)
 - [Project Tasks and Timeline](#project-tasks-and-timeline)
    - [Task List](#task-list)
    - [Milestones](#milestones)
    - [Timeline](#timeline)
    - [Effort Matrix](#effort-matrix)
 - [PPT Slideshow](#ppt-slideshow)
 - [Self-Assessment Essays](#self-assessment-essays)
 - [Professional Biographies](#professional-biographies)
 - [Budget](#budget)
 - [Appendix](#appendix)
    - [Tim](#tim)
    - [Nick](#nick)

## Project Abstract

Nick Chonko - chonkona@mail.uc.edu

Tim Walsh - walshtt@mail.uc.edu

Advised by Professor Nan Niu - niunn@ucmail.uc.edu

Our application is for a user to be able to put scheduled events into a calendar as well as times when they would like to do social activities. The user then can add tasks that need to be completed during daily life and the user’s tasks will be added to the calendar during available time slots. Finally, the social aspect is that the user will be recommended things to do during their social times, such as concerts, restaurant deals, and fitness classes. In addition, the user will be able to add friends and recommend that they participate in activities with them.

## Project Description

The goal of our application is for a user to be able to put scheduled events into a calendar as well as times when they would like to do social activities. The user then can add tasks that need to be completed during daily life and the user’s tasks will be added to the calendar during available time slots. Finally, the social aspect is that the user will be recommended things to do during their social times, such as concerts, restaurant deals, and fitness classes. In addition, the user will be able to add friends and recommend that they participate in activities with them.

## User Stories and Design Diagrams

### User Stories
_See [this link](https://gitlab.com/jebidis93/cs5001/blob/master/InitialUserStories.md) to go to the file_

1. Create Month display

    As a user, I want to view my calendar for the current month or a selected upcoming month, so that I can plan ahead.

2. Create Day display

    As a user, I want to view my calendar for the current day or a selected upcoming day, so that I can know what I am going to be doing on a specific day.

3. User Login

    As a user, I want to login via google calendar, so that I can load all of my events from google.

4. Create Scheduling Algorithm

    As a user, I want to be able to put in the deadline of task, so that have my calendar schedule the task

5. Bulk Load Data From Google

    As a developer, I want to be able to bulk load a users calendar data for the coming 6 months, so we do not make continuous calls to google calendar


### Design Diagrams
_See [this link](https://gitlab.com/jebidis93/cs5001/tree/master/diagrams) to go to the directory_

![D0](uploads/97f223435d7b1cd384494d45a1856abf/D0.PNG)

D0: The basic concept for how the application will function

![D1](uploads/eaf05f68d1c45e44c3c824f3ad311059/D1.PNG)

D1: A more descriptive diagram of a user logging into the app

![D2](uploads/647323594a71411b2c4b8a7980a4e000/D2.PNG)

D2: Full diagram of login, and using the calendar

![wireframe](uploads/0667f73b1d2cfe9ec9d12448bb9aeaf4/wireframe.png)


Wireframe: A wireframe of the basic idea for the front end

## Project Tasks and Timeline

### Task List
_See [this link](https://gitlab.com/jebidis93/cs5001/blob/master/Tasks.md) to go to the file_

- Nick

  - Get back end running - The initial Django server should run

  - Google Calendar API - Ability for our backend to use Google Calendar API

  - Custom Users - Allow the creation of users in our DB

  - Scheduling Algorithm - the algorithm used to schedule users’ events around other events, within their free time

  - Yelp Services - Add yelp reviews of businesses in which events are taking place

  - Twitter - Ability to tweet about events

- Tim

  - Rough UI - Not necessarily fleshed out.  Just bare minimum needed

  - Rough UX - Not necessarily fleshed out.  Just bare minimum needed

  - Messaging Capabilities - Add the ability for users to message each other

  - Location Services - Add location services for location events

  - Concert Services - Add ways to automatically show nearby concerts available

  - Facebook - Ability to post to Facebook about events

- Nick and Tim

  - API planning - Thorough planning of our API in RAML so that both of us know exactly what

  - Hookup front end to back end - Make sure the front end and backend are communicating properly using the details from the API planning

### Milestones
_See [this link](https://gitlab.com/jebidis93/cs5001/blob/master/milestones.PNG) to go to the file_

![milestones](uploads/0e180cd57ede818283756036c8fee9b9/milestones.PNG)

### Timeline
_See [this link](https://gitlab.com/jebidis93/cs5001/blob/master/timeline.PNG) to go to the file_

![timeline](uploads/47132a6ca69cbbf552a4ddde6840081e/timeline.PNG)

We tried to plan out the remainder of Fall semester and the entire Spring semester in approximately 2 week increments.  No dates are permanent, but rather guidelines to keep us on track. 

### Effort Matrix
_See [this link](https://gitlab.com/jebidis93/cs5001/blob/master/effort-matrix.PNG) to go to the file_

![effort-matrix](uploads/9c441a867bd93bd48c770e4c4363c4e4/effort-matrix.PNG)

## PPT Slideshow
_See [this link](https://gitlab.com/jebidis93/cs5001/blob/master/final-presentation.pptx) to go to the file_

## Self-Assessment Essays
_[Nick's Self-Assessment Essay](https://gitlab.com/jebidis93/cs5001/blob/master/chonko-assignment-3.docx) and [Tim's Self-Assessment Essay](https://gitlab.com/jebidis93/cs5001/blob/master/walsh-assignment-3.md)_



## Professional Biographies
_[Nick's Professional Biography](https://gitlab.com/jebidis93/cs5001/blob/master/chonko-biography.md) and [Tim's Professional Biography](https://gitlab.com/jebidis93/cs5001/blob/master/walsh-biography.md)_

## Budget

At this point in the project, we have spent no money.  However, at some point during development, we will need to purchase the Apple, and we will have to run a cloud server, which can vary in price depending on how long we run it.

Apple developer kit - $100

Cloud server - $50+

## Appendix

#### Tim

- [repo](https://gitlab.com/walshts97/react-native-social-calendar/edit#js-shared-permissions) (this is unstable at the time this file was made)
- Researched Libraries
   - [React native calendars](https://github.com/wix/react-native-calendars)
   - [Google Calendar API](https://developers.google.com/calendar)
   - OAuth Authentication
- [Time worked](https://gitlab.com/jebidis93/cs5001/blob/master/Tim%20Work%20log.xlsx)

#### Nick

 - [repo](https://gitlab.com/jebidis93/senior-design-backend)
 - Researched
   - [Django](https://docs.djangoproject.com/en/2.2/)
   - [Celery](https://docs.celeryproject.org/en/latest/)
   - [Docker](https://docs.docker.com/)
   - [Google Calendar API](https://developers.google.com/calendar)
   - [RAML](https://raml.org/developers/document-your-api)
   - [Django rest framework](https://www.django-rest-framework.org/)
 - [Time worked](https://gitlab.com/jebidis93/cs5001/blob/master/chonko-fall-progress.xlsx)
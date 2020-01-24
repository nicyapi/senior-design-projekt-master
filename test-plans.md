# Description of overall test plan

In the backend, our main testing strategy is to make unit tests for almost
everything we write.  We have installed `pytest` as our testing framework. The
backend uses a test database that is used when tests are run and all artifacts
from testing are completely removed between every test.

In the frontend, our plan is to test core UI/UX functionality. This will mean 
simple front end navigation tests as well as in-def end to end test for getting results from the back end.

# Test Case Descriptions

## ES1
ES1.1 Event Saving Test 1

ES1.2 This test will ensure that calendar events can be saved properly

ES1.3 This test ensures that events cannot be saved if the end time comes before
      the start time

ES1.4 The input will be an event with the current time for the start time, and 1
      second before the current time for the end time

ES1.5 The output will be an error from the save function stating that the end
      time must come after the start time

ES1.6 Boundary

ES1.7 Whitebox

ES1.8 Functional

ES1.9 Unit

## ES2
ES2.1 Event Saving Test 2

ES2.2 This test will ensure that calendar events can be saved properly

ES2.3 This test ensures that events can be saved if the end time comes after
      the start time

ES2.4 The input will be an event with the current time for the start time, and 1
      second after the current time for the end time

ES2.5 The output will be confirmation that the `save` function returned properly

ES2.6 Normal

ES2.7 Whitebox

ES2.8 Functional

ES2.9 Unit

## ES3
ES3.1 Event Saving Test 3

ES3.2 This test will ensure that calendar events can be saved properly

ES3.3 This test ensures that events cannot be saved if the end time is the same
      as the start time

ES3.4 The input will be an event with the current time for the start time, and
      the current time for the end time

ES3.5 The output will be an error from the save function stating that the end
      time must come after the start time

ES3.6 Boundary

ES3.7 Whitebox

ES3.8 Functional

ES3.9 Unit

## ES4
ES4.1 Event Saving Test 4

ES4.2 This test will ensure that calendar events can be saved properly

ES4.3 This test ensures that events cannot be saved if the end time comes
      between the start time and end time of a user's other events

ES4.4 The inputs will an event with the current time for the start time, and 2
      seconds after the current time for the end time, and an event with 1
      second after the current time for the start time, and 3 seconds after the
      current time for the end time.

ES4.5 The output will be an error from the save function stating that the times
      of the new event conflict with another event

ES4.6 Boundary

ES4.7 Whitebox

ES4.8 Functional

ES4.9 Unit

## ES5
ES5.1 Event Saving Test 5

ES5.2 This test will ensure that calendar events can be saved properly

ES5.3 This test ensures that events cannot be saved if the start time comes
      between the start time and end time of a user's other events

ES5.4 The inputs will an event with the current time for the start time, and 2
      seconds after the current time for the end time, and an event with the
      current time for the start time, and 1 second after the current time for
      the end time.

ES5.5 The output will be an error from the save function stating that the times
      of the new event conflict with another event

ES5.6 Boundary

ES5.7 Whitebox

ES5.8 Functional

ES5.9 Unit

## ES6
ES6.1 Event Saving Test 6

ES6.2 This test will ensure that calendar events can be saved properly

ES6.3 This test ensures that events can be saved if there is no conflict in the
      times with other events that are already stored

ES6.4 The inputs will an event with the current time for the start time, and 1
      seconds after the current time for the end time, and an event with 2
      seconds after current time for the start time, and 3 seconds after the
      current time for the end time.

ES6.5 The output will be confirmation that the `save` function returned properly

ES6.6 Normal

ES6.7 Whitebox

ES6.8 Functional

ES6.9 Unit

# FE1
FE1.1 Front End Navigation test 

FE1.2 This test will assure that the main navigation of the front end is working

FE1.3 Select each page and ensure navigation occurs properly

# FE2
FE2.1 Front End Menu Navigation test 

FE2.2 This test will assure that the menu navigation of the front end is working

FE2.3 Select the menu and access account settings page

# FE3
FE3.1 Front End Calendar test 

FE3.2 This test will assure that the calendar view is working properly (this will probably get sub divided later)

FE3.3 Scroll up and down on day view, select new day and see all events of that day, select new month, select new week, open an event and see data propegate

# FE4
FE4.1 Front End Event Finder test 

FE4.2 This test will assure that the event view works properly

FE4.3 open a category, open a event, validate fields propegate

# E2E1
E2E1.1 End to End test retrieving calendar data from back end

E2E1.2 This test will assure that the front end can call the backend and render data properly

# Test Case Matrix

|  ID  | (N)ormal/<br>(A)bnormal/<br>(B)oundary | (B)lackBox/<br>(W)hitebox | (F)unctional/<br>(P)erformance | (U)nit/<br>(I)ntegration |
|------|-----------------------------------------|---------------------------|--------------------------------|:------------------------:|
| ES1  |                    B                    |              W            |              F                 |             U            |
| ES2  |                    N                    |              W            |              F                 |             U            |
| ES3  |                    B                    |              W            |              F                 |             U            |
| ES4  |                    B                    |              W            |              F                 |             U            |
| ES5  |                    B                    |              W            |              F                 |             U            |
| ES6  |                    N                    |              W            |              F                 |             U            |
|      |                                         |                           |                                |                          |
|      |                                         |                           |                                |                          |
|      |                                         |                           |                                |                          |
|      |                                         |                           |                                |                          |
|      |                                         |                           |                                |                          |
|      |                                         |                           |                                |                          |
# PEAK
PEAK for TT APP

### Objective
This document outlines a specification and UI design for implementation of PEAK content via the TimelessToday App.
Goals
Provide secure, convenient, trackable access to the nine chapters of PEAK via the TimelessToday App.
### Solution
Please refer to the steps below for details
### Assumptions
* PEAK will have its own top level menu entry
* Enrollment in PEAK requires ( at minimum ) a user sign-in to the app ( thereby capturing name and email
address)
* PEAK is available to all App users
* Confirmation of age etc. is only requested in the event that the user pursues the ‘Asking for Knowledge’ path at
the end of the last chapter
* The journey begins with a Welcome and / or initial message
* Chapters must be viewed in sequence. All chapters can appear in the chapter list menu but greyed out if not yet
watched
* Chapters contain mandatory segments and may contain optional segments
* Tracking of progress only consists of capturing the user start events and end events of segments from each
chapter
* Content is only available online
* Once completed, a chapter is available for repeated viewing
* At the conclusion of all nine PEAK chapters the app displays a data entry form for people requesting to receive
the techniques of Knowledge. If the person has previously received the techniques of Knowledge, a Knowledge Review option is available ( Please see the screens below).

## Process
A PEAK user will enter the process from a PEAK menu item at the top level of the APP ( See example opposite). The application checks to make sure that the user has signed into the app to capture the user’s email and name. From there the app directs the user to an ‘Enroll’ screen if not already enrolled.
At the point of Enrolling in PEAK, a progress record is created and updated as the user progresses through PEAK:
During the process, the application can collect the following data ( Note: afk=‘Asking for Knowledge’):

PEAK USER DATA:

name
email
over 18 signature
sign-up_date
last completed chapter
last completed segment
afk submitted
afk submit date
optional chapter tracking
received Knowledge
smart card number

￼ 

If the user has enrolled for the first time, the app takes the user to a Welcome screen. From there the user can progress to the list of chapters all of which are greyed out except for the first chapter. After consumption of the first chapter, any re-entry into the program directs the user to the list of completed chapters and segments.

Each chapter will contain mandatory and possible optional segments.
The data associated with each content item will comprise the fields shown on the right. When a user commences watching a segment the app logs a play/ start event for the current user to indicate that they have begun PEAK Chapter ‘X’ Segment ‘Y’. Similarly, when the user completes the segment, the app logs the completion.

## Next Steps

When the user has completed all chapters and segments the app presents options to the user allowing them to take the next steps in the process.
The app shows the name and email of the user
( extracted from their sign-in) along with three options depending on their status.
The first option is for those users who have not received the techniques of Knowledge. Selecting this option takes them to the ‘Readiness Statement’ from which they can confirm their eligibility to submit a request along with an agreement to the requests of Prem Rawat. (Please see below). It may be necessary from a legal perspective to separate these confirmations.
The second option is for those who have received the techniques of Knowledge from Prem Rawat in the past. Selecting this option takes the user to a ‘Knowledge Review’ request. In order to validate such users the app requests Smart Card Name and Smart Card Number, both of which are optional. Please see below.
Both of the above requests result in email generation. In the case of someone requesting Knowledge for the first time the email routes to both Prem Rawat and the KS team.
In the case of a Knowledge Review request, the email routes to the KS team only (for validation and further communication).
In both cases the KS team arrange scheduling of either a Knowledge session or Knowledge Review accordingly. The final option exits the PEAK content and puts the user back to the main menu of the App.

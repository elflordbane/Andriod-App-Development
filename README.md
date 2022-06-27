# Andriod-App-Development

The requirements of this app where to have a log-in tied to a database where a user could either
create a new a account for a first time user or log into their existing account.  The app would also
ask for permission to send SMS notifications via text messaging.  Each user can accept or decline if
they want the messaging but someone has to allow the messaging to happen in the second prompt.  The
needs the app is created to address is tracking the weight of the user and comparing it with their 
goal weight.  It is a weight tracking app.  The screens used were a log in screen, a notification 
questionnaire screen, a data gathering screen, and daily weight input screen.  The user was keep in mind
at all times giving them prompts and messages to cue them along and let them know what was needed from
them and if things were added successfully or not.  My designs were successful the app runs well and is 
user friendly.

When I started coding I started with building the database and then the log in then I moved to the
activities, originally I thought to build several databases but this gave me an error so I just added 
several tables to one database and this worked well.  My strategy was to keep building the app up on 
itself and it grew into completion, after much testing.  In the future I feel a similar starting point
should be found and design methodology should follow.

     To test that my code was functional I would run the app often as soon as I built a new feature into
it to make sure it would work as planned.  I often would run the debugging feature to see exactly what 
line of code was making the app fail.  The testing process is very important because it reveals where your
app is having problems so you can fix it, also it lets you know when your work is done when the app runs
error free.

One of the main areas I had to innovate was to make the app work for multiple users, it involved storing
the username with the data that was being inserted, and also having the username sent whenever the data was 
queried for.  The username had to be passed as a variable between all the activities so it was always available.
When I expanded the app to store the users notification preference their username was also stored with it.

I think I really show my skills throughout the app, but there are a few things that may stand out.  The 
app has been made not to crash.  Their were point in the app where the user could leave the app without them
having entered key data for the app to run and when they next entered the app it would crash because it did
not have the data it needed.  Why a user would do this is not clear but now the program checks for this 
strange occurrence and will shunt the user back to data entry  if it has not been done.  Also, the back button
standard function for android apps is to return to the previous page which is not how my program should 
navigate, often I want the user to not be able to leave the page they are on, so it is disabled.  The try
catch methods for the parsing to catch people from entering numbers that are too large was another thing that
demonstrates my experience as well.

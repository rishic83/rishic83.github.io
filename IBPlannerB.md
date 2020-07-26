# IB Planner (Android Application)

## Problem Analysis

### Use of Android Studio:

Following are the features of the Android Studio that I used to develop the software:

1. Classes known as “Activities” that determined the functionality of each specific
screen used. Activities contained inner classes and functions, and were linked to
XML files for the UI.
2. XML layout files to create the GUI using different kinds of system-defined layouts
such as ConstraintLayout (where each element’s position is constrained to the other
elements and the parent layout), and RelativeLayout (where each element’s
position is determined relative to the other elements).
3. The android.content.Intent class to pass data between different activities, refresh
activities, and start new activities.
4. The Calendar object from the java.util.Calendar class, to interact with Date objects;
set deadlines and scheduled task dates, get current date and time.
5. SQLite databases to store the tasks, test scores and suggestions since these
databases could easily work with structured data. Additionally, Android Studio
supported built-in SQLite implementation.
6. The android.widget.Toast class, to display small pop-up messages to the user.
7. The android.util.Log class, to log specific values. This was used for testing.
8. The android.widget.DatePicker class, to create a DatePicker object, which allows a
date to be selected from a roller-type UI object,
9. A third-party library called MaterialCalendarView to create a calendar display of
each month with interactive date selections.
10. A third-party library called GraphView to display the graphs of the client’s test
score trends.

I tried to think of alternatives to making an Android application as well:

* I thought of making a computer-based solution but that would be less convenient and
portable because the client couldn’t easily access it anywhere. Furthermore, he used a Macbook which ran OS X, for which I didn’t know how to write code, and probably
couldn’t, since I had a Windows computer.
* I also thought of having a web-application which could be accessed by all devices but the client would require constant internet connection for that, which would be more cumbersome than having a local solution.

### Product Structure:

![Product Structure](/images/IBPlanner_B_Structure.png)


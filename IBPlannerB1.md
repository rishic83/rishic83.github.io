# IB Planner (Android Application)

## UX Design

### Fig 1: Home Page

![Fig 1](/images/)

This is the home page, from where the client
can choose which module to go to. **Task Scheduler**
and **Performance Analyzer** are the two main
subsystems of the software. Tapping on the former
button takes the user to the Task Scheduler activity
(in Fig. 2), whereas tapping on the latter will go to the
Performance Analyzer activity (in Fig. 6.)

### Fig 2: Task Scheduler Calendar View

![Fig 2](/images/)

This is the main display of the Task
Scheduler module. The user can tap one of the
days on the Calendar view to open the **Task
List** activity and view the tasks scheduled for
that specific day (in Fig. 3). The user can also
tap on the search icon on the top right to search
the **Task Database** (further seen in Fig. 5) for
the tasks he has already entered in the past, and
add them easily to the Task List. Lastly, the
user can tap on the plus icon on the bottom
right of the screen to go to the **Edit Task**
activity (Fig. 4) and create a new task to be
added to the Task List.

### Fig 3: Task List

![Fig 3](/images/)

The Task List shows the user all the work
that’s scheduled to be completed on a given day.
The tasks are displayed in a “to-do list” format for
ease of use. The user can check the checkboxes
next to each task as he finishes each task. This
simply provides a visual cue to the user that the
task is complete. The user can tap it again to mark
it as incomplete. The “edit” button can be tapped
on to edit the task parameters. The user can tap the
“unschedule” button to remove the task from being
scheduled on a specific day (but it will still remain
in the database, so the user can use the search
function to find and schedule it again). The
“delete” button can be used to permanently remove
it from the schedule and the database.

### Fig 4: Edit Task Form

![Fig 4](/images/)

The user can define all the parameters for
each task he’d like to add to the Task List. The
input “Name of Task” would be taken in the String
format. For subject, there’d be a drop-down list of
all the subjects the client takes, from which he can
choose. The duration would have a drop-down list
from which the user can select between intervals
of half an hour (30 mins, 1 hour, etc.). The max
would be 4 hours; all tasks would be scheduled
between 5 PM and 9 PM every day since the client
works at his maximum efficiency then. The Deadline can be selected using
the DatePicker roller, which is a characteristic
feature of Android applications. The **Submit**
button essentially creates a new entry in the **Task
Database**, and according to the algorithm (which
schedules a task according to duration and
deadline), schedules the task for a specific day.

### Fig 5: Search Module

![Fig 5](/images/)

The user would enter the search term (input taken
in String format) in the search box, and can choose the
**Subject** filter, which will only display those results that
pertain to the specific subject selected. The search
query would be carried out on the Task Database, and
the results would be returned and displayed in a list
format. The user can tap the result they like, which will
take them to the **Edit Task** activity (in Fig. 4), where
they can edit the parameters of each task if they’d like
(like updating the deadline, or changing the duration),
and then add it to the task list. The purpose of the search
function is that, instead of creating new tasks over and
over again, which can take some time, the user can
simply add a previous task to the task list.

### Fig 6: Performance Analyzer Subject Graphs

![Fig 6](/images/)

This is the main display for the
Performance Analyzer module. The graphs in the
center show the academic performance trend of
all of the user’s difference subjects. The score for
each test is entered by tapping on the plus button
at the bottom-right of the screen (leading to Fig.
8), and it’s calculated to a percentage, which is
then plotted on the graph. The user can tap on any
of his 6 subjects to access the academic
performance graph and view all the test scores for
solely that subject (Fig. 7). The suggestions
button can be tapped on to view which subject
areas the user should focus on, to improve
academic performance (further discussed in Fig.
9).

### Fig 7: Subject View

![Fig 7](/images/)

This is the “hub” for each specific subject.
The display in the center shows the graph of the
academic performance trend in the given subject
so that he can see his performance over time
Below that, there’s a list view of each test that
he’s entered into the **Test Database** for that
specific subject (through the form shown in Fig.
7), where he can view the specifics of his
performance in the subject. The point of this
entire display is so that the client can easily
evaluate whether this is a strong or weak subject
for him, and how much effort he needs to put in
to achieve a good grade, according to his own
judgment.

### Fig 8: Edit Test Form

![Fig 8](/images/)

The user can define all parameters for each test
through this form. Date would be entered through a
DatePicker roller, Subject would be selected through
a drop-down menu, the test’s name would be entered
in String format, the score achieved and maximum
score would be entered in double format. Upon
tapping the submit button, this test would be added to
the **Test Database**, from where it is accessed
everywhere else.

### Fig 9: Suggestions Tab

![Fig 9](/images/)

The application analyzes the academic
performance in each subject from the **Test
Database**. If the score for a test is lower than the
previous one, it creates an entry in the **Suggestions
Database** for a study session in that specific
subject. This is displayed in a list form, where the
user can tap the suggestion he likes, which takes
him to the Edit Task form (Fig. 4), where he can
tweak the specific parameters of each suggested
task. By default, the software creates a generic task
labeled “Study Session” in for a set number of
times in a week determined by the algorithm. The
duration is always 30 mins, since the client studies
better in short bursts.

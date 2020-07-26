# IB Planner (Android Application)

## Problem Analysis

### Description of scenario:

As a student pursuing the IB Diploma, a high school curriculum notorious for its heavy workload, my friend - Angad Bhalla - faces a hectic schedule. (I will be referring to him as the **"client"** for the rest of the documentation). He often struggles to manage his time effectively and keep up with all his work. Since he doesn’t have a good memory (as claimed by himself!), he can’t keep track of all his assignments and their due dates. As a result, he isn't able to meet his academic expectations, but he doesn’t know what to specifically focus on to improve his performance.

Currently, Angad makes use of a physical planner, where he notes down his work, but usually forgets to look at it. He also uses a wall calendar, but he doesn’t wish to create a schedule for each day (**INSERT IMAGE**).

Angad mentions that these methods are not useful for his academic life; he wishes for a solution where he can be reminded about his pending work, but doesn’t have to go through the process of scheduling his work; he wants to immediately know when to do what in an organized manner so that his most important work is taken care of first. His desired solution should also help in keeping track of his academic record so that he knows which areas to concentrate his efforts on to achieve the best results. Learning about all of Angad's problems, and wanting to help out a friend, I decided to create a computerized solution. 


### Rationale for Product:

I decided to create an **IB Planner** Android application for Angad. Due to its portability, he can carry it anywhere and schedule his work on the go. The software is composed of two main modules: the **Task Scheduler**, which automatically schedules Angad’s tasks and creates an organized timetable, and the **Performance Analyzer**, which keeps track of his test scores and provides suggestions regarding which subjects to focus on, according to his academic performance. After conducting several interviews to understand Angad's problems and preferences, I personalized the product for him through the following features:

* Selectable subjects to enter a task/test are customized to client’s specific IB subjects.
* Task scheduling implemented in 30 minute sessions.
* Tasks scheduled only between 5 and 9 PM.
* Software developed to function optimally on client’s device.
* Scheduling engine schedules tasks to be finished as soon as possible.

I used Java in an IDE called Android Studio (**INSERT IMAGE**) to develop the application. The modular design of this object-oriented programming language meant that errors in the code could easily be identified, distinct functions could be developed concurrently, drag-and-drop GUI design was supported. Furthermore, SQLite database implementation was internally supported by default in Android Studio. I used third party libraries, like MaterialCalendarView and GraphView, to enhance the UI. Furthermore, the IDE was free, and only one version of the software needed to be developed; if the client decided to upgrade his OS version or change his phone (to another Android system), he’d still be able to access the software.

### Success Criteria for Product:

1. A user interface display which shows the days of the month in a calendar format.
2. Upon tapping a particular day, it displays the work to be finished on that day and its
corresponding timing.
3. Ability for user to define a task by adding its description, corresponding subject (choice
between his 6 IB subjects), duration (in increments of 30 minutes), and deadline of the task.
4. Ability for application to schedule tasks before a given task’s deadline, without overlapping
tasks, as soon as possible.
5. Ability to search for the tasks already entered into the tasks database.
6. Ability to filter search by ‘subject’.
7. Ability to add tasks directly from the search list to the task list.
8. Ability to edit and delete tasks from the search list.
9. A graph which shows the combined trend of performance in all subjects.
10. Ability for user to define a test by entering its description, its corresponding subject (choice
between his 6 IB subjects), score achieved, maximum score possible, and test date.
11. A graph which shows the trend of academic performance over time in each subject.
12. List view of all test scores in a specific subject.
13. ‘Suggestions’ tab through which software suggests more study sessions in subjects where
performance has been declining.
14. Ability for the client to directly add the suggested tasks from the aforementioned
‘Suggestions’ tab to the task list.
15. Ability for user to delete these suggestions.

#### Proceed to [Product Design](IBPlanner/pages/Page_B0)



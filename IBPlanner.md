# IB Planner (Android Application)

## Problem Analysis

### Context:

I decided to create an **IB Planner** Android application for my friend, Angad Bhalla. Due to its portability, he can carry it anywhere and schedule his work on the go. The software is composed of two main modules: the **Task Scheduler**, which automatically schedules Angad’s tasks and creates an organized timetable, and the **Performance Analyzer**, which keeps track of his test scores and provides suggestions regarding which subjects to focus on, according to his academic performance. After conducting several interviews to understand Angad's problems and preferences, I personalized the product for him through the following features:

* Selectable subjects to enter a task/test are customized to client’s specific IB subjects.
* Task scheduling implemented in 30 minute sessions.
* Tasks scheduled only between 5 and 9 PM.
* Software developed to function optimally on client’s device.
* Scheduling engine schedules tasks to be finished as soon as possible.

I used Java in an IDE called Android Studio to develop the application. The modular design of this object-oriented programming language meant that errors in the code could easily be identified, distinct functions could be developed concurrently, drag-and-drop GUI design was supported. Furthermore, SQLite database implementation was internally supported by default in Android Studio. I used third party libraries, like MaterialCalendarView and GraphView, to enhance the UI. Furthermore, the IDE was free, and only one version of the software needed to be developed; if the client decided to upgrade his OS version or change his phone (to another Android system), he’d still be able to access the software.

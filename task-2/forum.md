# Task 2

Observer Design Pattern: 
The observer is a behavioral design pattern that lets you define a subscription mechanism to notify multiple objects about any events that happen to the object they're "observing." 
In this case, the objects would be the piazza audience (students), who would be notified when there is an event taking place (notification when a post is announced). 
The problem that it solves would be the fact that students (observers) are loosely coupled to the post creator (subject) since the post creator (subject) knows nothing about them, other than that they view piazza (the observer interface). Here, the structure is more like passive listening. 

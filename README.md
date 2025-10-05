# DS-Final-Project-Proposal
Project build in C++.

What problem will your project solve/simulate?
Identify a class you will write to store data critical to the application.
What will be stored in a dynamic array?  A linked List?
What template class will you write?
How will you use a stack, queue or tree?
What will you search for?
What will you sort (put in order)?
How will you use an STL container class?  An STL function?


1. What problem will your project solve/simulate? This project will simulate the path of a college baseball player who wishes to reach the MLB. It will crosswalk the various stages of development, training and evaluation that a player goes through, estimating the time and effort required to improve specific skills and attributes. The simulation will consider factors such as talent level, dedication, training effectiveness and potential setbacks including injuries and plateaus. The goal is to provide a data-driven representation of an aspiring player's path to (MLB) goal. 

2. I chose (Player). This class will store all the necessary information about a baseball player. 

3. Dynamic Array: A dynamic array will store a list of "Player" objects currently in the simulation. This allows easy access to all players for training, evaluation, and classification. Linked List: This list will store a history of scouting reports for each player. Each node in the list will contain the player's current skill at a given point in time. This allows us to track their progress over time. 

4. Template Class: skillTracker
This template class will be used to track the progress of a player's specific skill (e.g., hitting, pitching) over time.

5. Data Structures (Stack, Queue, or Tree): Queue
A queue will be used to represent the "waiting list" of players waiting to be scouted by MLB teams. Players are added to the queue based on their overall skill level, and scouts evaluate them in the order they appear.

6. Scouting: We will search for players who meet specific criteria, such as: Players with hitting ability above a certain threshold. Players with the highest overall potential (combination of skills and talent). Players who are not injured.

7. Sorting: We will sort players by: Overall skill level (for scouting purposes). Specific skills (sort by batting ability to identify the best hitters). Talent level (to identify players with the most potential).

8. STL container class: std::map: This will be used to store the relationship between a player's name and their skillTracker objects. This allows us to easily access each player's skill-tracking data.

9.  std::transform: I will use this to apply a function to each element of a container, such as a vector of player names, and store the results in another container. For example, we could use it to convert a vector of Player objects into a vector of their names.

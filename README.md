# Project 1: Todo Basic Performance Testing

## Website Scenario
- Website 6 months after launch. Most users already have an account and are focused on editing todo items and subtasks.
- Most users prioritize editing/adding todo items over subtasks

### User Distribution - Load & Stress
- 10% - As a new user I can register an account to start tracking my todo tasks
    - 60% - Register successfully
    - 40% - Register incorrectly
- 20% - As a new user I can log in and out to securely access my todo items
    - 80% - Login Successfully and logout
    - 20% - Use Incorrect Password, then correct password, then logout
- 45% - As a user I can create and edit todo items to keep track of my work
    - 30% - Create todo task
    - 10% - Edit todo task
    - 20% - Delete todo task
    - 40% - Tick todo task on/off
- 25% - As a user I can create and edit subtask items to better organize my primary tasks
    - 40% - Create subtask
    - 50% - Tick subtask on/off
    - 10% - Delete subtask
> [!NOTE]
> Top level are user stories. Indented are tests. Story percentages are for load and stress only. Test percentages will be reused for spike tests.

### User Distribution - Spike (Registration)
- 35% - As a new user I can register an account to start tracking my todo tasks
- 35% - As a new user I can log in and out to securely access my todo items
- 20% - As a user I can create and edit todo items to keep track of my work
- 10% - As a user I can create and edit subtask items to better organize my primary tasks

### User Distribution - Spike (Login)
- 5% - As a new user I can register an account to start tracking my todo tasks
- 50% - As a new user I can log in and out to securely access my todo items 
- 35% - As a user I can create and edit todo items to keep track of my work
- 10% - As a user I can create and edit subtask items to better organize my primary tasks

### User Distribution - Spike (Todo)
- 5% - As a new user I can register an account to start tracking my todo tasks
- 10% - As a new user I can log in and out to securely access my todo items 
- 70% - As a user I can create and edit todo items to keep track of my work
- 15% - As a user I can create and edit subtask items to better organize my primary tasks

### User Distribution - Spike (Subtask)
- 5% - As a new user I can register an account to start tracking my todo tasks
- 10% - As a new user I can log in and out to securely access my todo items 
- 35% - As a user I can create and edit todo items to keep track of my work
- 50% - As a user I can create and edit subtask items to better organize my primary tasks

## Think Time and Pacing
- Register successfully
    - Think time: 15-60 sec
    - Pacing: 65 sec
- Register incorrectly
    - Think time: 15-60 sec
    - Pacing: 130 sec
- Login Successfully and logout
    - Think time: 1-10 sec
    - Pacing: 22 sec
- Use Incorrect Password, then correct password, then logout
    - Think time: 10-30 sec
    - Pacing: 95 sec
- Create todo task
    - Think time: 10–25 sec
    - Pacing: 30 sec
- Edit todo task
    - Think time: 10-20 sec
    - Pacing: 25 sec
- Delete todo task
    - Think time: 1 sec
    - Pacing: 5 sec
- Tick todo task on/off
    - Think time: 1 sec
    - Pacing: 5 sec
- Create subtask
    - Think time: 10 sec
    - Pacing: 12 sec
- Tick subtask on/off
    - Think time: 1 sec
    - Pacing: 5 sec
- Delete subtask
    - Think time: 2 sec
    - Pacing: 5 sec

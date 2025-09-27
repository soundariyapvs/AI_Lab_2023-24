# Ex.No: 11  Planning –  Block World Problem 
### DATE:  27/9/2025                                                                            
### REGISTER NUMBER : 212222060249
### AIM: 
To find the sequence of plan for Block word problem using PDDL  
###  Algorithm:
Step 1 :  Start the program <br>
Step 2 : Create a domain for Block world Problem <br>
Step 3 :  Create a domain by specifying predicates clear, on table, on, arm-empty, holding. <br>
Step 4 : Specify the actions pickup, putdown, stack and un-stack in Block world problem <br>
Step 5 :  In pickup action, Robot arm pick the block on table. Precondition is Block is on table and no other block on specified block and arm-hand empty.<br>
Step 6:  In putdown action, Robot arm place the block on table. Precondition is robot-arm holding the block.<br>
Step 7 : In un-stack action, Robot arm pick the block on some block. Precondition is Block is on another block and no other block on specified block and arm-hand empty.<br>
Step 8 : In stack action, Robot arm place the block on under block. Precondition is Block holded by robot arm and no other block on under block.<br>
Step 9 : Define a problem for block world problem.<br> 
Step 10 : Obtain the plan for given problem.<br> 
     
### Program:
<img width="921" height="686" alt="image" src="https://github.com/user-attachments/assets/0e6c4f55-de72-4082-a10b-df692ae57686" />


### Input 
<img width="926" height="216" alt="image" src="https://github.com/user-attachments/assets/9e6e08ff-a6b4-4234-a562-1e4c5fecd877" />


### Output/Plan:
<img width="675" height="791" alt="image" src="https://github.com/user-attachments/assets/63764e83-b01c-4786-990c-c176029cfa1b" />




### Result:
Thus the plan was found for the initial and goal state of block world problem.

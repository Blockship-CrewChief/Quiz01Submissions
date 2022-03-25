# Kindly submit seperate files for each task of the first quiz

## Challenge 1

### Airline Ticket Manager
_Let’s get started on building your very first solidity program_

We will be making a fun Airline Ticket Booking program. The rest of the challenges of this series will continue adding to this base. So let’s get started!
```
  Task 01: Make a function that takes input (name, destination and passport ID) from the user and stores it. 
  (Hint: Use mappings and structs)
```

```  
  Task 02: You also need to add the option for the user to choose one of the three classes (first class, business, and economy) 
  and store it with the previous information.  
  (Hint: There is a special data type you can use to solve this trick in a jiffy!)
```

  Do you know the difference between state and local variables? You’ll be using them next. 
```
  Task 03: Initialize the price of economy, business and first class seats as follows 
  (be careful with units!):
  Economy price: 0.005 ether
  Business price: 0.007 ether
  First class price: 0.01 ether
```

  Did you know that your contract can send and withdraw ethers? That’s what this task is all about. 
```
  Task 04: Make a function that receives ethers on a successful ticket booking. 
  (Hint: You’ll need to to add a certain modifier to the function)
```

### Modifiers and Factory Pattern
_Next up are modifiers._

  You need to make a custom modifier that allows certain addresses to call a function. 
```
  Task 05: Make the two functions that add and remove addresses from the allowed list of addresses. 
  (Here’s a catch, both functions should implement the modifier.)
```

  Next Did you know that there is a contract that can deploy contracts? That’s what you need to make.
```
  Task 06: Make a parent contract that has the ability to deploy child contracts 
  (This function should implement the modifier you made in ‘Task 05’).
```

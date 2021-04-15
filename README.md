# ENSF_409FinalProject



[Check out our video demonstartion!](https://www.example.com)


## Instructions for running and using our program:

Step 1:


Step 2:


Step 3:


## How the program is structured:

**The program has been divided into 3 key parts:**

**1. Front-End (GUI Development)**
**2. Cheapest Combination Algorithm**
**3. Back-End (DataBase)**

### Front-End:


>
>
>



### Cheapest Combination Algorithm:

**CheapestCombination.java**

> Represents a single combination class that is then implemented by the main `CalculateCombinations.java` program 
> to populate winning combinations!


**CalculateCombinations.java**

>`ArrayList<CheapestCombination> allCombinations` stores all combinations that satisfy the order item and quantity.
>However, this list then gets passed into `method bestCombination()` to return a single best combination!
>
>To actually find the `ArrayList allCombinations`, we use a recursive search algorithm `method bestLampCombination(){` and a driver `method findLampCombinations(){` that searches for all possible combinations and adds fullfilled combinations to the `ArrayList allCombinations` array!
>


### Back-End:

>
>
>




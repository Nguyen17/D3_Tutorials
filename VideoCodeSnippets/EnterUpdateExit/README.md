# Enter, Update, Exit Rules

## How Enter, Update, Exit Work
1. Enter uses the .enter() function and only enters that function if:
     - DOM Elements < Data Elements
          - For example, if you have an array of 3 elements, [20, 30, 40].
            And you don't have any objects of the type you selected, (0 < 3),
            therefore .enter() executes its' functions.
            
2. Update executes if you have:
     - DOM Elements == Data Elements

3. Exit uses the .exit() function and executes if you have:
     - DOM Elements > Data Elements
     
     
## Enter, Update, Exit Expected Output

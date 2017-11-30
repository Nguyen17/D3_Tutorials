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
<img width="101" alt="screen shot 2017-11-30 at 3 43 01 pm" src="https://user-images.githubusercontent.com/13631369/33461249-7488c178-d5e6-11e7-9f9e-1da57e148c77.png">

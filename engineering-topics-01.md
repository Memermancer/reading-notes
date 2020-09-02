***Quantity Always Trumps Quality

Main points
1) Stop Theorizing
    -Don't agonize over building the right thing
    -Over planning can create paralysis that prevents real learning from taking place

2) Write Lots of Software
    -Keep building until you find the solution
    -Set schedules
    -Commit yourself to projects

3) Learn From Your Mistakes
    -Use your experiences to refine your skills and discover new solutions
    -Revisit your old work and improve it later


***Clean Code Chapter 1
Main Points
1) Code cannot be replaced with models and requirements.
    -These models require specifications derived from code
    -Humans have never created successful systems from vague feelings

2) Good Code Matters
    -Bad code can bring a project down over time
    -Don't skip refactoring in favor of speed
    -Messy code is difficult for teammates to understand
    -Messy code stacks, and becomes impossible to unravel
    -Slowly reduces productivity over time
    -Communicate code needs to managers

3) Determining Clean Code
    -Writing clean code requires 'code-sense'
    -Pleasing to read
    -Efficient
    -Bad code spreads because it looks like people don't care about it
    -Runs all tests, contains no duplication, minimizes the number of entities
    -Clean code matches your expectations

***Red, Green, Refactor
Main Points
1) R, G, Refactor is a framework of TDD
    -Red: what you want to develop
    -Green: how do you make your tests pass
    -Refactor: how do you improve your existing implementation 

2) RED
    -The starting point of the cycle
    -Determine what you want your code to do

3) GREEN
    -The phase where the code is written and the tests pass
    -Don't worry about optimizing your solution

4) REFACTOR
    -The phase where you refactor your implementation
    -Efficiency phase
    -Refactoring might not be necessary, but it is necessary to think about it

***The Cycles of TDD
Main Points
1) The Three Laws of TDD
    -Write a failing test before any code
    -Do not write more of a test than is needed to fail
    -Do not write more production code than is needed for currently failing tests to pass

2) R-G-Refactor
    -Cycle that can be implemented once for every dozen or so iterations of the Three Laws
    -Create a failing unit test
    -Write production code to pass the test
    -Clean up the mess

3) Specific/Generic Cycle
    -Next level up, about every 10 R-G-Refactor cycles
    -As tests become more specific, code becomes more generic
    -To address more and more specific tests, the code base should be able to make the generic case work

4) Boundaries
    -Final primary cycle of TDD
    -Check to see if the project is crossing an architectural boundary
    -Make decisions about the scope of the project and re-access developer constraints

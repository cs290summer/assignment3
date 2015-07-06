Basic JavaScript Assignment
===========================

This part of the assignment will cover fundamental JavaScript topics outside the context of web development. Fully automated tests will be provided for all assignment components. These are a tool to help you assess if your code is working as intended. Passing the tests does not guarantee a good grade nor does failing them guarantee a poor grade. The grade will be based on the extent to which you meet the requirements for code in this class and the extent to which the requirements in the source files are met.

Instructions
------------
- Create a new repository called cs290-assignment3 (in your shared acount if you are in a group).
- Clone this repository and copy all of the contents to that repository (You can also fork this to your account using Github fork, both cloning and forking works fine)
  - The directory structure should look like this:
    - cs290-assignment3
      - log.txt
      - qunit_runner.html
      - qunit
      - src
      - tests
- **You are only allowed to modify the files in the src directory.**
  - There are some additional files, those are just a hook for us to eventually support a better testing system.
  - The comments in the files in the src directory describe the intended behavior of the functions that you need to fill in. Please ask on the discussion boards if you are confused about the intended functionality of any function.
  - Within those files, your code should go between the `//your code here` comments.
  - You should replace `return undefined;` with appropriate return statements.
- To test your code open the `qunit_runner.html` web page locally. Along with the red errors check for statements saying something like `Expected 4 assertions, but 2 were run`. This means that the test had to abort early due to a error it could not recover from. That means there are two additional tests that are not even getting run.
  - Given the nature of automated tests, it is easy to see what the expected values are and simply hard code those returns. If you do this for any portion of the assignment, you will get a 0 for the whole assignment. (For example, variableModification should work for any value, not just 42, but we are only testing the value 42. If you hardcode the values `47`, `'42'` and `'42foo'` that is a violation of this rule. )

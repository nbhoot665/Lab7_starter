Answers:


1. The best place to fit the automated tests in the Recipe project development pipeline is within a Github action that runs whenever code is pushed. Running automated tests within a Github action on every push helps to ensure that the codebase stays reliable and maintainable. It does this by preventing broken code inside pull requests from merging as it detects errors or bugs early. 

2. No, we should not use an end to end test to check if a function is returning the correct output. This is because end to end tests are meant to test the entire system and not individual functions. A better test to check individual functions would be a unit test.






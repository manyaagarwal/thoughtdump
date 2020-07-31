# RNTester

 - Refactoring of RNTesterApp files since  they are extremely big and should be sliced to make the development experience better as well 
 - Should we make issues for the e2e tests or create a .md file for the testing strategy and the smoke tests that should be there 
 - What about the Detox situation? Should we try to get the URL structure to work? 

Work to do 
 - Check if there are Red Boxes are there or not? Check Detox for it 
 - See why navigation is slow 
 - Consider the URL functionality for the navigation (Low priority, put it on backlog)
 - Check parent child implementation (Easier and faster : Minimum Viablle Approach)

- Purpose of RNTester: 
  - In the future make it all separate packages that will change the structure of the React Native repository 
  - Initialisation script that would clone RN master and link react native with RNTester 

Start from beginning
- Move all changes file by file to ensure that the app is running : Each of them will be its own PR 
- Linear history of commit upon commit 
- If we choose to, we can move the app to the packges folder and make sure all the links work (move git history along with it too)
- Native modules are broken on iOS, alternative or solution? - Keep async storage 's community package on iOS and move to native modules on android 
- We can revisit native modules in the end and leave a TODO for the meanwhile 

Meeting with Ricky on Thursday 
Have a merged branch for Ricky to test by Wednesday 
- [[ DesignSprint ]]

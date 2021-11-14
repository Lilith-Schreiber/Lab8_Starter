# Lab 8 - Starter
This lab is done **only** by ***Ting-Yun Yeh***

1. Where would you fit your automated tests in your Recipe project development pipeline?
   Ans: within a Github action that runs whenever code is pushed
2. Would you use an end to end test to check if a function is returning the correct output?
   Ans: No
3. Would you use a unit test to test the "message" feature of a messaging application? Why or why not? For this question, assume the "message" feature allows a user to write and send a message to another user.
   Ans: No, because it may be a very long message, and it does not have a specific type for a message.
4. Would you use a unit test to test the "max message length" feature of a messaging application? Why or why not? For this question, assume the "max message length" feature prevents the user from typing more than 80 characters.
   Ans: Yes, because it has a specific restriction, and we can fix it in the test case.
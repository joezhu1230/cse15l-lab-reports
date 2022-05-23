# Lab Report 4

> [The link to my markdown-parse](https://github.com/joezhu1230/markdown-parser)  
> [The link to the other group's markdown-parse]([https:](https://github.com/jemilparikh/markdown-parser))

> ### Snippet 1
* What it should produce:  
  ![Screenshot 2022-05-22 202240](https://user-images.githubusercontent.com/103288060/169737191-925cac57-396d-4172-9bd1-890cbca2192f.png)
* How I turned it into a test:
  ![Screenshot 2022-05-22 202617](https://user-images.githubusercontent.com/103288060/169737579-101e41f9-5950-45c9-8421-330e320e88bb.png)
* The implementation didn't pass the test, the JUnit output is:
  ![Screenshot 2022-05-22 203448](https://user-images.githubusercontent.com/103288060/169738430-9b1dc6da-fce4-4404-af43-42f2926a1601.png)
* The reviewed implementation didn't pass the test, the JUnit output is:
  ![Screenshot 2022-05-22 203448](https://user-images.githubusercontent.com/103288060/169738430-9b1dc6da-fce4-4404-af43-42f2926a1601.png)
  
  ---

> ### Snippet 2
* What it should produce:  
  ![Screenshot 2022-05-22 204053](https://user-images.githubusercontent.com/103288060/169738956-c4e171ca-ec5c-45b6-97b7-acfeeafb06bc.png)
* How I turned it into a test:
  ![Screenshot 2022-05-22 204503](https://user-images.githubusercontent.com/103288060/169739301-7eda615a-679b-4f5e-9475-1ac761592812.png)
* The implementation didn't pass the test, the JUnit output is:
  ![Screenshot 2022-05-22 204621](https://user-images.githubusercontent.com/103288060/169739420-fb722f2e-ca3a-487e-a3a8-92b80887822d.png)
* The reviewed implementation didn't pass the test, the JUnit output is:
  ![Screenshot 2022-05-22 204621](https://user-images.githubusercontent.com/103288060/169739420-fb722f2e-ca3a-487e-a3a8-92b80887822d.png)
  
  
  ---

> ### Snippet 3
* What it should produce:  
  ![Screenshot 2022-05-22 204900](https://user-images.githubusercontent.com/103288060/169739659-27078388-51ba-49c4-b13d-a2e9ee88f79e.png)
* How I turned it into a test:
  ![Screenshot 2022-05-22 205054](https://user-images.githubusercontent.com/103288060/169740007-9334e31c-4f4b-4f53-aab1-97a8540ef23a.png)
* The implementation didn't pass the test, the JUnit output is:
  ![Screenshot 2022-05-22 205148](https://user-images.githubusercontent.com/103288060/169740100-630bdd2c-16ce-4802-ab19-4f49212d63d0.png)
* The reviewed implementation didn't pass the test, the JUnit output is:
  ![Screenshot 2022-05-22 205148](https://user-images.githubusercontent.com/103288060/169740100-630bdd2c-16ce-4802-ab19-4f49212d63d0.png)


---
> ## Question 1
* There is a possibility that a small code change will make the program work for snippet 1 (and all related cases that use inline code with backtick). The implementation  would be to stop printing links if there are backticks in the file.

> ## Question 2
* It is not possible that a small code change will make my program work for snippet 2 (and all related cases that nest parentheses, brackets, and escaped brackets). This is due to the fact that determining whether the parentheses and brackets are nested correctly requires a big code change that checks the entire string. This cannot be done with a small code change.

> ## Question 3
* There is a possibility that a small code change will make the program work for snippet 3 (and all related cases that have newlines in brackets and parentheses). One way to implement it is to add a condition that if there are spaces between two parentheses the code will stop printing the link.



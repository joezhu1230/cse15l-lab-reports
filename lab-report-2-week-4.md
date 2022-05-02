# Lab Report 2 Week 4

### Code change 1
1. screenshot of the commited code change![Screenshot 2022-05-02 140707](https://user-images.githubusercontent.com/103288060/166327868-f5e6a53e-4d6e-42c5-a0b6-00018667cfb4.png)

2. link to the failure inducing input file: ![test-file2](https://github.com/joezhu1230/Lab-2-/blob/main/test-file2.md)
3. symptom of the failure inducing input
4. fixed bug in commit history: ![Screenshot 2022-05-02 140411](https://user-images.githubusercontent.com/103288060/166327762-7d7e7a34-a820-42dc-95fc-303c96c77fe3.png)

5. The failure inducing input is due to the test file having extra lines after the links, which caused the symptom shown above when running in command.
The symptom also shows that the code ran into an infinite loop, this is because the MarkdownParse did not handle the case where there are extra lines, which resulted in a bug that caused an infinite loop. 

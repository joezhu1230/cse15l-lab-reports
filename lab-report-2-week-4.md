# Lab Report 2 Week 4

## Code change 1
1. screenshot of the commited code change![Screenshot 2022-05-02 140707](https://user-images.githubusercontent.com/103288060/166327868-f5e6a53e-4d6e-42c5-a0b6-00018667cfb4.png)

2. link to the failure inducing input file: ![test-file2](https://github.com/joezhu1230/Lab-2-/blob/main/test-file2.md)

3. the bug in commit history: ![Screenshot 2022-05-02 140411](https://user-images.githubusercontent.com/103288060/166327762-7d7e7a34-a820-42dc-95fc-303c96c77fe3.png)

4. The failure inducing input is due to the test file having extra lines after the links, which caused the symptom shown above when running in command.
The symptom also shows that the code ran into an infinite loop, this is because the MarkdownParse did not handle the case where there are extra lines, which resulted in a bug that caused an infinite loop. 

## Code change 2
1. screenshot of the commited code change ![Screenshot 2022-05-02 142541](https://user-images.githubusercontent.com/103288060/166330291-8291f4e3-ba2a-4846-93cb-3d45fd9fed7a.png)


2. link to the failure inducing input file: ![test-file3](https://github.com/joezhu1230/Lab-2-/blob/main/test-file3.md)

3. the bug in commit history: ![Screenshot 2022-05-02 142243](https://user-images.githubusercontent.com/103288060/166329897-16c2ae7e-c6d5-4edc-b5f9-2360f486c461.png)

4. The failure inducing input is due to the test file not having parentheses before and after the links, which caused the symptom shown above when running in command.
The symptom also shows that the code ran an IndexOutOfBoundsException, this is because the MarkdownParse's getLinks method first looks for parentheses when looking for a link, in this case it was not able to find it and therefore it caused the bug. 

## Code change 3
1. screenshot of the commited code change ![Screenshot 2022-05-02 143205](https://user-images.githubusercontent.com/103288060/166331123-fe537e3d-7556-4228-bd11-2157dec6a595.png)

2. link to the failure inducing input file: ![test-file4](https://github.com/joezhu1230/Lab-2-/blob/main/test-file4.md)

3. the bug in commit history: ![Screenshot 2022-05-02 143146](https://user-images.githubusercontent.com/103288060/166331167-19d2b245-6157-44b8-903b-6cb186cba599.png)
4. The failure inducing input is due to the test file not having bracket before and after the link name, which caused the symptom shown above when running in command.
The symptom also shows that the code produced an incorrect output, this is because the MarkdownParse's getLinks method also looks for brackets when looking for a link, in this case it was not able to find it and therefore it caused the bug. 


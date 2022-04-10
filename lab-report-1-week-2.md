# Lab Report 1 Week 2

## **Installing VSCode** 

To install VSCode, go to  [https://code.visualstudio.com/](https://code.visualstudio.com/). Once installed, open VSCode and it should look like this:

![Screenshot 2022-04-08 154257](https://user-images.githubusercontent.com/103288060/162642187-b430df40-446c-4e92-9283-e64a547d577e.png)


## **Remote Connecting**

Open the terminal in VSCode and enter 

`$ ssh cs15lsp22ahv@ieng6.ucsd.edu`

(be sure to replace `ahv` with your own letters from your account). Once entered, your terminal should look like this:

![Screenshot 2022-04-08 154414](https://user-images.githubusercontent.com/103288060/162642155-0803a8ad-727d-4f16-a629-38b4d869b87e.png)

## **Trying Commands**

After logging in, try some commands. For example, try commands like: `cd` `ls` `cd ~` `pwd` `ls -a` `ls -lat`.

The commands should make your terminal look similar to this:

![Screenshot 2022-04-10 152222](https://user-images.githubusercontent.com/103288060/162642317-6d38d15e-a3bc-4d2e-b9cb-c15472839b1b.png)

## **Moving Files with `scp`**

In order to copy files from your computer to the remote computer, you can use the command `scp`. This command must be ran from you computer. To test this, make a java file on your computer. Then, type `scp (file name).java cs15lsp22ahz@ieng6.ucsd.edu:~/`  (Again, do not forget to change `ahv` with your own letters). 

Once completed, the terminal should look like this:
![Screenshot 2022-04-10 153021](https://user-images.githubusercontent.com/103288060/162642526-86369f34-38a4-45dc-bb66-3101d2541042.png)

(if you see the line where the file is not found, that is because you did  not download java on your computer).

## **Setting an SSH Key**

It is very time consuming to log into the remote computer everytime, therefore, we can skip the log in step by setting an `ssh` key. 

On your computer, type in `ssh-keygen`. 


It should look like this:
![Screenshot 2022-04-10 154103](https://user-images.githubusercontent.com/103288060/162642987-914dc67f-4801-4e58-a700-4d1691d33fbc.png)

Now we can log in again by typing `ssh cs15lsp22zz@ieng6.ucsd.edu` . Your terminal should look like this:

![Screenshot 2022-04-10 154349](https://user-images.githubusercontent.com/103288060/162643073-3357af9e-b2e1-4f15-a960-9bc5219544d8.png)

## **Optimizing Remote Running**

Try running commands in quotes at the end of an `ssh` comment. This will allow you to directly run the command on the remote server. For example, try running `ssh cs15lsp22ahv@ieng6.ucsd.edu "ls"`

It should look like this:

![Screenshot 2022-04-10 155121](https://user-images.githubusercontent.com/103288060/162643296-0bfbbaf9-f919-4830-a3f4-c1437b658291.png)


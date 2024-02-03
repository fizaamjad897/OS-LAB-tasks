# <u>Operating System **Lab 3 tasks**</u> 

# CS- 2022-172                                Fiza

# ⇒ TASK 1:

## 1- Adding the new ubuntu user named mrtom

▹First create a directory for mrtom in which all the relevant files are saved then change its permission. ▹After that add new user  using **adduser** command and name him mrtom.
![haha](.lab3/Screenshot (187).png)


## 2- Creating a new text file named 19f-XXXX.txt

▹Then create a new text file and open it using **nano** command followed by your file name **19f-XXXX.txt**.

![Screenshot (187)](D:/ostasks/lab3/Screenshot (188).png)

## 3- Opening the the file and writing 10 lines in it

▹ Now open the file and write 10 lines in it as mentioned in the manual and save it by **Ctrl+S.**

![](D:/ostasks/lab3/Screenshot (189).png)

## 4- Creating another text file named fizaamjad.txt

▹Go back by pressing **Ctrl+ X** . Then create a new text file and open it using **nano** command followed by your file name **fizaamjad.txt**.

![](D:/ostasks/lab3/Screenshot (190).png)

## 5- Write 10 lines and Save

▹Now open the file and write 10 lines in it as mentioned in the manual and save it by **Ctrl+S.**

![](D:/ostasks/lab3/Screenshot (191).png)

## 6- Concatenate the text of Both files

▹ Create a new text file named **concatenatedfile** and concatenate the text of both files using **cat command**.

▹ Use the same **cat command** to show the output on the screen.

![](D:/ostasks/lab3/Screenshot (192).png)

## 7- Display the first 2 lines of first file

▹ Display the first 2 lines using **head** command followed by **-** and the **number of lines** you want to display.

![](D:/ostasks/lab3/Screenshot (193).png)

## 8- Display the last 2 lines of second file

▹ Display the last 2 lines using **tail** command followed by **-** and the **number of lines** you want to display.

![](D:/ostasks/lab3/Screenshot (194).png)

## 9- Finding the string of Roll number from first file

▹ Find the roll number from the first file using **grep -r** followed by the **filename** and display it on the screen.

![](D:/ostasks/lab3/Screenshot (205).png)

## 10- Change the Permission of the file

▹ Grant the execute permission of the second file to the group using **chmod a + w** ***filename*** command. 

▹ Remove the write permission for the owner using **chmod o - w** ***filename*** command. 

![](D:/ostasks/lab3/Screenshot (196).png)

## 11- Show the current file path to mrtom

▹ Display the current file path to mrtom using **pwd** command.

![](D:/ostasks/lab3/Screenshot (197).png)

## 12- List all the files on the desktop directory

▹ Display all the files to mrtom using **ls** command.

![](D:/ostasks/lab3/Screenshot (197).png)

## 13- Create the folder of mrtom's personal stuff 

▹ Create a folder of mrtom's file using **mkdir** command and name it as rollnumber **172**.

![](D:/ostasks/lab3/Screenshot (199).png)

## 14- Display the date on the terminal for mrtom

▹  Show the date on terminal using **date** command.

![](D:/ostasks/lab3/Screenshot (199).png)

## 15- Display the "thankyou" on the terminal from mrtom

▹ Show the thank you message from tom using **echo** command.

![](D:/ostasks/lab3/Screenshot (200).png)

# ⇒ TASK 2:

## 1- Create a file and Write LAB rules 

▹ Create and open a file using **nano** command and name it **19f-XXXXoslabrules.txt**.

▹ Then mention the **lab rules** and save it using **Ctrl+S.**

![](D:/ostasks/lab3/Screenshot (202).png)

## 2- Set the rights and convert them accordingly

▹ Set the rights **(rwx, r-x, r--)** to its equivalent binary and then convert into decimal to get the required command. The working is as,

![](D:/ostasks/lab3/WhatsApp Image 2024-02-03 at 12.57.03 PM.jpeg)

## 3- Run the worked command on our created file

▹ Run the command **chmod** ***calculated rights(754 in this case) filename*** on the terminal.

![](D:/ostasks/lab3/Screenshot (203).png)

## 4- Append the Ls command to our created file

▹ To **append** the Ls command we use **>>** operator and write the **filename** afterwards.

![](D:/ostasks/lab3/Screenshot (204).png)

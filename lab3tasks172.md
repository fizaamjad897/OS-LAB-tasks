# <u>Operating System **Lab 3 tasks**</u> 

# CS-2022-172                                                Fiza

# ⇒ TASK 1:

## 1- Adding the new ubuntu user named mrtom

▹First create a directory for mrtom in which all the relevant files are saved then change its permission. 
▹After that add new user  using **adduser** command and name him mrtom.
![Screenshot (187)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/951a4fbc-4a07-4f7d-9f0d-ca3c146009fe)


## 2- Creating a new text file named 19f-XXXX.txt

▹Then create a new text file and open it using **nano** command followed by your file name **19f-XXXX.txt**.

![Screenshot (188)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/c92d7de6-135e-456a-b74a-7735ece80dcc)


## 3- Opening the the file and writing 10 lines in it

▹ Now open the file and write 10 lines in it as mentioned in the manual and save it by **Ctrl+S.**

![Screenshot (189)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/3121aca3-217a-4687-a159-a7fc858db6e0)

## 4- Creating another text file named fizaamjad.txt

▹Go back by pressing **Ctrl+ X** . Then create a new text file and open it using **nano** command followed by your file name **fizaamjad.txt**.


![Screenshot (190)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/eb225d7b-cf9e-4e2b-b46a-b6bd8cfa30cb)

## 5- Write 10 lines and Save

▹Now open the file and write 10 lines in it as mentioned in the manual and save it by **Ctrl+S.**


![Screenshot (191)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/021f5529-3df9-497c-b288-a94e997d0eb2)

## 6- Concatenate the text of Both files

▹ Create a new text file named **concatenatedfile** and concatenate the text of both files using **cat command**.

▹ Use the same **cat command** to show the output on the screen.


![Screenshot (192)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/16f9cca0-223e-4357-bbe3-e80a46a24906)

## 7- Display the first 2 lines of first file

▹ Display the first 2 lines using **head** command followed by **-** and the **number of lines** you want to display.

![Screenshot (193)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/31618f5d-e14b-409d-9703-ef48b8882387)


## 8- Display the last 2 lines of second file

▹ Display the last 2 lines using **tail** command followed by **-** and the **number of lines** you want to display.

![Screenshot (194)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/cc0bfe98-bce5-446b-9045-f762bb8f1069)


## 9- Finding the string of Roll number from first file

▹ Find the roll number from the first file using **grep -r** followed by the **filename** and display it on the screen.


![Screenshot (205)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/0993e3c2-bb95-49b3-8fa3-4cc60559bad9)

## 10- Change the Permission of the file

▹ Grant the execute permission of the second file to the group using **chmod a + w** ***filename*** command. 

▹ Remove the write permission for the owner using **chmod o - w** ***filename*** command. 
![Screenshot (196)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/7a71d303-6eec-407c-b534-ffe01e6375e5)



## 11- Show the current file path to mrtom

▹ Display the current file path to mrtom using **pwd** command.

![Screenshot (196)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/7a71d303-6eec-407c-b534-ffe01e6375e5)

## 12- List all the files on the desktop directory

▹ Display all the files to mrtom using **ls** command.

![Screenshot (197)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/702ee84b-e3d5-401f-9c6f-9a8f74375ec8)


## 13- Create the folder of mrtom's personal stuff 

▹ Create a folder of mrtom's file using **mkdir** command and name it as rollnumber **172**.
![Screenshot (199)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/8cf936ec-719d-48e0-a3b8-9635b4ed2bfc)

## 14- Display the date on the terminal for mrtom

▹  Show the date on terminal using **date** command.
![Screenshot (199)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/4bcee4f8-9ff5-4558-a42b-552e89e4f51d)



## 15- Display the "thankyou" on the terminal from mrtom

▹ Show the thank you message from tom using **echo** command.

![Screenshot (200)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/02c2212a-d2fc-4f55-a570-8b210b0c492a)


# ⇒ TASK 2:

## 1- Create a file and Write LAB rules 

▹ Create and open a file using **nano** command and name it **19f-XXXXoslabrules.txt**.

▹ Then mention the **lab rules** and save it using **Ctrl+S.**


![Screenshot (202)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/0f395503-a07f-4282-94e6-3e391b6fc8f4)

## 2- Set the rights and convert them accordingly

▹ Set the rights **(rwx, r-x, r--)** to its equivalent binary and then convert into decimal to get the required command. The working is as,


![WhatsApp Image 2024-02-03 at 12 57 03 PM](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/b93c2a03-421d-48ac-86b3-a8f1d7fa270f)

## 3- Run the worked command on our created file

▹ Run the command **chmod** ***calculated rights(754 in this case) filename*** on the terminal.


![Screenshot (203)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/ac84bcaa-4c4f-41cf-be2e-86825789d708)

## 4- Append the Ls command to our created file

▹ To **append** the Ls command we use **>>** operator and write the **filename** afterwards.

![Screenshot (204)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/412ff4e3-d43f-4a2d-9707-72c097cefcfd)


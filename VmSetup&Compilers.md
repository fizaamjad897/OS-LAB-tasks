# **Installing Ubuntu on Oracle VirtualBox**

------

**IMPORTANT!** Make sure you have internet access during all of these processes.

1. ## **Download VirtualBox:**

   - Visit the [**Oracle VirtualBox website**](https://www.virtualbox.org/).

   - Download the version of VirtualBox that is **compatible** with your operating system (Windows, macOS, or Linux).

     
 ![Screenshot (135)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/6aff176e-9e77-451a-ae4a-f97142ffc41a)

     

2. ## **Install VirtualBox:**

   - Run the installer, follow the on-screen instructions and wait for the installation to finish.

   ![Screenshot (137)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/ed589594-ea7c-4a73-8fba-6ad96ba1841d)


     

3. ## **Download Ubuntu ISO:**

   - Visit the [**Ubuntu website**](https://www.unbuntu.com) and download the latest **LTS version of Ubuntu**.

![WhatsApp Image 2024-02-03 at 4 06 21 PM](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/dcbd2da7-5cd9-4b10-8870-9a05207c66d0)

     

4. ## **Create a New Virtual Machine:**

   - Open VirtualBox and click on "**New**" to create a new virtual machine.

   - **Name** your virtual machine, **choose the directory** you want to install it in and **select the iso file** that you have previously downloaded.

    
![Screenshot (114)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/d53441ee-4fb4-452a-9c62-d6aeae7ecb5f)

     

   - check the "**Skip Unattended Installation**" box according to your requirements(the terminal that we will be needing later on during the installation of compilers **does not work sometimes if this is left unchecked**) and click next.

   
![Screenshot (116)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/a7a2be07-94ad-4892-8f35-6f83c3c37d13)

     
   - Set the **memory size** and processors according to your system specifications and click next.

 ![Screenshot (118)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/1f17906e-f889-42ba-8be5-237e73c98cc9)

     

   - Create a virtual hard disk and **allocate space** and click next.

   ![Screenshot (119)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/cd69f142-40eb-4775-9c99-80cfa27f2150)


   - Finally click on **finish** to finish creating a virtual machine.

     

5. ## **Install Ubuntu:**

   - Now **start** the virtual machine.

    
![Screenshot (120)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/7882e8d6-cde8-4cb0-9574-6142148db861)

     

   - Select "**Try or Install Ubuntu**" and follow the on-screen instructions to install Ubuntu on the virtual machine.

  ![Screenshot (121)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/bf9dbfbc-bb48-47f7-af9e-178120e5c131)


  
![Screenshot (122)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/55e55860-805c-4c7e-aa11-84d9dd120c6e)

     
- Congratulations! you have successfully installed the **Ubuntu virtual OS** on your computer.

# **Installing C and C++ Compilers on Ubuntu**

Before moving ahead **make sure you have internet access** and the virtual Ubuntu OS is working properly.

1. ## **Open Terminal:**

   - Press **`Ctrl + Alt + T`** to open the terminal or **Search** the terminal.

   - Or open the **Dock** and select the terminal icon.

![Screenshot (124)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/a7e94ae8-0b6d-467a-a5e4-ae76e6544a12)


     

2. ## **Install C Compiler (GCC):**

   - Enter the following command into the terminal.

     ```
     sudo apt install gcc
     ```

     
![Screenshot (147)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/0c68003e-13b5-4938-9f07-bd162a538f25)

      

   - After entering this command, enter the **password** for your Virtual OS if needed

   - If you have an internet connection the C compiler will start **downloading and installing** automatically.

  ![Screenshot (148)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/1a9ee326-00c9-44a9-a31b-c2362c30fee4)


     

3. ## **Install C++ Compiler (g++):**

   - **Repeat step 2** after making the following changes in the previous command.

     ```
     sudo apt install g++
     ```
![Screenshot (150)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/9d0f1bd7-8dee-4448-8bb2-1c608d52c0ac)



4. ## **Verify Installations:**

   - Check if the compilers have been successfully installed and their versions.

     ```
     gcc --version
     g++ --version
     ```

  ![Screenshot (149)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/0b6ab146-8d0c-4a50-b75e-d840c89f47b9)
     
-Now, you have a fully **functional Ubuntu virtual machine on Oracle VirtualBox** with **C and C++ compilers** installed. You can use the terminal to write and compile C and C++ programs on your virtual machine.

# **Testing C, C++ Compilers**



- ## Step 1:  **How to create a File**

  Note that when its your first time creating a file, **by default,** when we **right-click** inside anywhere in the Ubuntu file manager, it will not give us the “New document” option. We must do the following steps to achieve this.

  To get this **missing** option, we need to run a command.

  1. Open **Ubuntu command** terminal.

  2. Run commands
  mkdir -p ~/Templates/Text
  cd ~/Templates/Text
  touch document
![Screenshot (151)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/9d4de58f-6aa4-418a-b59d-670176d2a893)

  3. Now, go to your **Linux File Manager** or **Desktop** and **right-click** where you want to **create a new file** and the option will be available.

  4. Select **New Document** and then **Text Document**.
   
![Screenshot (152)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/2ee608a6-11b2-4bc1-b1bc-45b0ebb1b5ff)

    
  5. This will instantly create a new text file on your Linux OS.
   

- ## Step 2:  **Using C Language Compiler**

  1. **Create a new file** and rename it to **test.c**.


![Screenshot (153)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/430fb9d4-c5c2-49bc-b545-832b51584fe1)

    

  2. **Double-click** to open the file.

  3. **Write a sample C language code** in the file. For example:

  #include<stdio.h>
  
  void main() 
  {
  	printf("Hello! This is my first program ");
  	int a=3,b=7;
  	printf("%d is the sum of a and b", a+b);
  }
   

  ![Screenshot (154)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/aa06489c-3a87-4e18-9f7c-f717deefff73)

  4. Open the **Linux terminal**(**`Ctrl + Alt + T`**) and enter the following commands to compile and run this code (**You must first enter the directory where you have created the file** using the "**cd ~/**" command).
    **To Compile:**
     gcc -o obj test.c
    **To Run:**
      ./obj

  ![Screenshot (156)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/21537a0d-a5b3-480b-b364-6f89ed1d9921)   
- ## Step 3:  **Using C++ Language Compiler**

  1. **Repeat the same procedure as Step 2** with few changes.

  2. **Create a new file** and rename it to **test.cpp**.

  3. **Double-click** to open and **write a sample C++ language code** in the file. For example:
#include<iostream>
  using namespace std;

  int main()
  {
      cout << “Testing 123”;
      int a=1,b=2;
      cout << a+b;
  }
  ![Screenshot (157)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/5990d62d-0484-499b-843b-4fbffcc1bca7)

 
  
       
  
  4. Open the **Linux terminal**(**`Ctrl + Alt + T`**) and enter the following commands to compile and run this code (**You must first enter the directory where you have created the file** using the "**cd ~/**" command).
  
  **To Compile:**

  g++ -o obj test.c  
    **To Run:**
  ./obj
  
 ![Screenshot (158)](https://github.com/fizaamjad897/OS-LAB-tasks/assets/120313148/0481dc84-a1fa-4ba9-938f-b9895efa8851)
  We are now done with the **running** and **testing** of both the compilers and successfully executing **C and C++ programs**.






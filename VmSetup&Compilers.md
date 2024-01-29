# **Installing Ubuntu on Oracle VirtualBox**

------

**IMPORTANT!** Make sure you have internet access during all of these processes.

1. ## **Download VirtualBox:**

   - Visit the [**Oracle VirtualBox website**](https://www.virtualbox.org/).

   - Download the version of VirtualBox that is **compatible** with your operating system (Windows, macOS, or Linux).

     ![virtualBoxDownload](C:\Users\ifiza\Pictures\Screenshots\Screenshot (135).png)

     

2. ## **Install VirtualBox:**

   - Run the installer, follow the on-screen instructions and wait for the installation to finish.

     ![vbinstall](C:\Users\ifiza\Pictures\Screenshots\Screenshot (137).png)

     

3. ## **Download Ubuntu ISO:**

   - Visit the [**Ubuntu website**](https://www.unbuntu.com) and download the latest **LTS version of Ubuntu**.

     ![ubuntuinstall](C:\WhatsApp Image 2024-01-28 at 10.37.32 PM.jpeg)

     

4. ## **Create a New Virtual Machine:**

   - Open VirtualBox and click on "**New**" to create a new virtual machine.

   - **Name** your virtual machine, **choose the directory** you want to install it in and **select the iso file** that you have previously downloaded.

     ![machine](C:\Screenshot (114).png)

     

   - check the "**Skip Unattended Installation**" box according to your requirements(the terminal that we will be needing later on during the installation of compilers **does not work sometimes if this is left unchecked**) and click next.

     ![checkbox](C:\Screenshot (116).png)

     

   - Set the **memory size** and processors according to your system specifications and click next.

     ![AllocateMemory](C:\Screenshot (118).png)

     

   - Create a virtual hard disk and **allocate space** and click next.

     ![AllocateDisk](C:\Screenshot (119).png)

   - Finally click on **finish** to finish creating a virtual machine.

     

5. ## **Install Ubuntu:**

   - Now **start** the virtual machine.

     ![startMachine](C:\Screenshot (120).png)

     

   - Select "**Try or Install Ubuntu**" and follow the on-screen instructions to install Ubuntu on the virtual machine.

     ![commanPromptInstall](C:\Screenshot (121).png)

     ![Opened](C:\Screenshot (122).png)

     

     ------

     Congratulations! you have successfully installed the **Ubuntu virtual OS** on your computer.

# **Installing C and C++ Compilers on Ubuntu**

------

Before moving ahead **make sure you have internet access** and the virtual Ubuntu OS is working properly.

1. ## **Open Terminal:**

   - Press **`Ctrl + Alt + T`** to open the terminal or **Search** the terminal.

   - Or open the **Dock** and select the terminal icon.

     ![dock](C:\Screenshot (124).png)

     

2. ## **Install C Compiler (GCC):**

   - Enter the following command into the terminal.

     ```
     sudo apt install gcc
     ```

     

     ![terminalGCC](C:\Users\ifiza\Pictures\Screenshots\Screenshot (147).png)

     

   - After entering this command, enter the **password** for your Virtual OS if needed

   - If you have an internet connection the C compiler will start **downloading and installing** automatically.

     ![installingGCC](C:\Users\ifiza\Pictures\Screenshots\Screenshot (148).png)

     

3. ## **Install C++ Compiler (g++):**

   - **Repeat step 2** after making the following changes in the previous command.

     ```
     sudo apt install g++
     ```

     ![installing++](C:\Users\ifiza\Pictures\Screenshots\Screenshot (150).png)

4. ## **Verify Installations:**

   - Check if the compilers have been successfully installed and their versions.

     ```
     gcc --version
     g++ --version
     ```

     ![check](C:\Users\ifiza\Pictures\Screenshots\Screenshot (149).png)

     ------
     
     Now, you have a fully **functional Ubuntu virtual machine on Oracle VirtualBox** with **C and C++ compilers** installed. You can use the terminal to write and compile C and C++ programs on your virtual machine.

# **Testing C, C++ Compilers**



- ## Step 1:  **How to create a File**

  Note that when its your first time creating a file, **by default,** when we **right-click** inside anywhere in the Ubuntu file manager, it will not give us the “New document” option. We must do the following steps to achieve this.

  To get this **missing** option, we need to run a command.

  1. Open **Ubuntu command** terminal.

  2. Run commands

    ```
  mkdir -p ~/Templates/Text
  cd ~/Templates/Text
  touch document
    ```

    ![documentOption](C:\Users\ifiza\Pictures\Screenshots\Screenshot (151).png)

    

  3. Now, go to your **Linux File Manager** or **Desktop** and **right-click** where you want to **create a new file** and the option will be available.

  4. Select **New Document** and then **Text Document**.

    ![optionAvailable](C:\Users\ifiza\Pictures\Screenshots\Screenshot (152).png)

    

  5. This will instantly create a new text file on your Linux OS.

    

- ## Step 2:  **Using C Language Compiler**

  1. **Create a new file** and rename it to **test.c**.

  ![rename](C:\Users\ifiza\Pictures\Screenshots\Screenshot (153).png)

    

  2. **Double-click** to open the file.

  3. **Write a sample C language code** in the file. For example:

    ```
  #include<stdio.h>
  
  void main() 
  {
  	printf("Hello! This is my first program ");
  	int a=3,b=7;
  	printf("%d is the sum of a and b", a+b);
  }
    ```

    ![exampleCode](C:\Users\ifiza\Pictures\Screenshots\Screenshot (154).png)

    

  4. Open the **Linux terminal**(**`Ctrl + Alt + T`**) and enter the following commands to compile and run this code (**You must first enter the directory where you have created the file** using the "**cd ~/**" command).

    **To Compile:**

    ```
  gcc -o obj test.c
    ```

    **To Run:**

    ```
  ./obj
    ```

    ![runProgram](C:\Users\ifiza\Pictures\Screenshots\Screenshot (156).png)

    

- ## Step 3:  **Using C++ Language Compiler**

  1. **Repeat the same procedure as Step 2** with few changes.

  2. **Create a new file** and rename it to **test.cpp**.

  3. **Double-click** to open and **write a sample C++ language code** in the file. For example:

    ```
#include<iostream>
  using namespace std;

  int main()
  {
      cout << “Testing 123”;
      int a=1,b=2;
      cout << a+b;
  }
    ```
  
  4. ![cppRename](C:\Users\ifiza\Pictures\Screenshots\Screenshot (157).png)
  
       
  
  4. Open the **Linux terminal**(**`Ctrl + Alt + T`**) and enter the following commands to compile and run this code (**You must first enter the directory where you have created the file** using the "**cd ~/**" command).
  
  **To Compile:**
  
  ```
  g++ -o obj test.c
  ```
  
    **To Run:**
  
  ```
  ./obj
  ```
  
    ![runProgramC++](C:\Users\ifiza\Pictures\Screenshots\Screenshot (158).png)
  
------
  
  We are now done with the **running** and **testing** of both the compilers and successfully executing **C and C++ programs**.






# How to debug C++ code in Visual Studio
**Introduction:**
Welcome to instructions on how to install a debugger! A debugger is a software tool that allows you to test and debug your code to ensure that it functions correctly. In these instructions, we will guide you through the step-by-step process of installing a debugger on your computer. These instructions are designed for Computer Science students who may not have prior experience with debugger installation. We will use clear and concise language and provide visual aids to help you easily follow along. By the end of this instruction, you will be able to successfully install a debugger on your computer and begin debugging your code with confidence.

  **Prerequisites:**
  
    1. A C++ compiler: Before you can start debugging your C++ code, you need to have a compiler installed on your computer. There are many options available for C++ compilers, such as GCC, Clang, and Visual C++. You should choose a compiler that is compatible with the debugger you plan to use.
    2. A text editor or integrated development environment (IDE): You will need a program that allows you to write and edit C++ code. A text editor like Notepad++ or a full-featured IDE like Visual Studio Code or Eclipse can be used.
    3. A basic understanding of C++ programming: In order to effectively debug your C++ code, you should have a basic understanding of C++ programming concepts and syntax.
  
  **Definitions:**
  
    1. C++: a general-purpose programming language that supports object-oriented programming and is commonly used for developing system software, applications, and video games.
    2. Compiler: a computer program that translates source code written in a high-level programming language into machine code that can be executed by a computer.

**Step-by-step guide:**
  1.  Install Visual Studio Code: You can download and install Visual Studio Code from the official website (hyperlink this). Follow the installation prompts to install the software on your computer.
![photo_2023-02-19 23 28 23](https://user-images.githubusercontent.com/123377628/219964651-fd65a051-eca8-43b3-8deb-bddf1219b0a3.jpeg)
  2. Install the C++ extension: Open Visual Studio Code and click on the **Extensions** icon on the left-hand side of the window. In the search bar, type **C++** and select the **C++** extension from the list. Click the **Install** button to install the extension.

![photo_2023-02-19 23 27 53](https://user-images.githubusercontent.com/123377628/219964666-6eb41e19-51a2-47ad-a72b-e16b81a587f7.jpeg)![photo_2023-02-19 23 27 56](https://user-images.githubusercontent.com/123377628/219964667-f0b4743d-4a82-484d-9dba-0dbeeca23049.jpeg)
  3. Install a C++ compiler: Visual Studio Code does not come with a built-in C++ compiler, so you will need to download and install one separately. One option is to download the MinGW compiler from this website (hyperlinked?). Follow the installation prompts to install the compiler on your computer.

![photo_2023-02-19 23 32 30](https://user-images.githubusercontent.com/123377628/219964710-a16bc2d2-8cfb-46ff-bc3c-d4e50cc92d88.jpeg)
  4. Add MinGW to the PATH environment variable: To use the MinGW compiler in Visual Studio Code, you will need to add it to the PATH environment variable. To do this, follow the instructions below:
    
    a. Right-click on the **Computer** or **This PC** icon on your desktop and select **Properties.** This will open the System window.
    b. Click on **Advanced system settings** on the left-hand side of the window. This will open the System Properties window.
    
 ![photo_2023-02-19 23 33 17](https://user-images.githubusercontent.com/123377628/219964745-c452e57a-56a6-4264-a683-c7274655c105.jpeg)
    
    c. Click on the **Environment Variables** button at the bottom of the window. This will open the Environment Variables window.
    d. Under **System variables**, scroll down and find the **Path** variable. Select it and click on **Edit.**
    e. In the **Edit Environment Variable** window, click on **New** and type the path to the MinGW bin directory, using a semi-colon to separate it from other paths in the list. For example, if MinGW is installed in the default directory, the path to the bin directory would be “C:\MinGW\bin”.
    
 ![photo_2023-02-19 23 34 00](https://user-images.githubusercontent.com/123377628/219964777-b8404348-4134-4a10-a9e7-d679cad8faa6.jpeg)
    
    f. Click **OK** to close all the windows.
  5. Configure Visual Studio Code: Open Visual Studio Code and create a new folder where you will store your C++ projects. Then, create a new file in the folder with a .cpp file extension (for example, hello.cpp). In the top menu bar, click on **Terminal** and select **New Terminal** to open a new terminal window in Visual Studio Code.
![photo_2023-02-19 23 34 37](https://user-images.githubusercontent.com/123377628/219964808-85f1f7a4-75a1-44e1-9754-1b885f121258.jpeg)
  6. Compile and run your C++ code: In the terminal window, navigate to the folder where you saved your .cpp file using the cd command. Then, use the g++ command to compile your code (for example, g++ hello.cpp -o output). Once the compilation is complete, you can run the compiled program by typing **./output** in the terminal window.
![photo_2023-02-19 23 35 00](https://user-images.githubusercontent.com/123377628/219964846-ad71453f-707b-41e6-bb89-544bf3db4555.jpeg)

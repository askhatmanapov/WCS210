# How to compile C++ code in Visual Studio Code
## Group 4
### Introduction:
Welcome to this technical instruction on how to install a debugger! A debugger is a software tool that allows you to test and debug your code to ensure that it functions correctly. In this instruction, we will guide you through the step-by-step process of installing a debugger on your computer. This instruction is designed for Computer Science students who may not have prior experience with debugger installation. We will use clear and concise language and provide visual aids to help you easily follow along. By the end of this instruction, you will be able to successfully install a debugger on your computer and begin debugging your code with confidence. 
### Let's get started:
Prerequisites: 
1. A C++ compiler: Before you can start debugging your C++ code, you need to have a compiler installed on your computer. There are many options available for C++ compilers, such as GCC, Clang, and Visual C++. You should choose a compiler that is compatible with the debugger you plan to use.
2. You will need a program that allows you to write and edit C++ code. In our case it is a full-featured IDE like Visual Studio Code. You should know how to do basic things in VS Code (open folder, create new file).
3. A basic understanding of C++ programming: In order to effectively debug your C++ code, you should have a basic understanding of C++ programming concepts and syntax.

Definitions:
1. C++: a general-purpose programming language that supports object-oriented programming and is commonly used for developing system software, applications, and video games.
2. Compiler: a computer program that translates source code written in a high-level programming language into machine code that can be executed by a computer.
### Step by step guide:
1. Install the C++ extension: Open Visual Studio Code and click on the "Extensions" icon on the left-hand side of the window. In the search bar, type "C++" and select the "C++" extension from the list. Click the "Install" button to install the extension.

2. Install a C++ compiler: Visual Studio Code does not come with a built-in C++ compiler, so you will need to download and install one separately. One option is to download the MinGW compiler from this [website](https://sourceforge.net/projects/mingw/). Follow the installation prompts to install the compiler on your computer.

3. Add MinGW to the PATH environment variable: To use the MinGW compiler in Visual Studio Code, you will need to add it to the PATH environment variable. Right-click on the "Computer" or "This PC" icon on your desktop and select "Properties". This will open the System window. 
4. Click on **"Advanced system settings"** on the left-hand side of the window. This will open the System Properties window. Click on the **"Environment Variables"** button at the bottom of the window. This will open the Environment Variables window.
![photo_2023-02-28 23 12 59](https://user-images.githubusercontent.com/123377628/221929325-383aa685-13be-4842-ae80-f1dfdd32a0f9.jpeg)
5. Under "System variables", scroll down and find the "Path" variable. Select it and click on "Edit". In the "Edit Environment Variable" window, click on "New" and type the path to the MinGW bin directory, using a semicolon to separate it from other paths in the list. For example, if MinGW is installed in the default directory, the path to the bin directory would be “C:\MinGW\bin”.
![photo_2023-02-28 23 12 58](https://user-images.githubusercontent.com/123377628/221929440-cb26090f-cd61-4b95-b32d-28e9959ade12.jpeg)
6. Click "OK" to close all the windows. Now your Visual Studio Code is ready to compile C++ code.
### Let’s do a little check:
Configure Visual Studio Code: Open Visual Studio Code and create a new folder where you will store your C++ projects. Then, create a new file in the folder with a .cpp file extension (for example, hello.cpp). In the top menu bar, click on "Terminal" and select "New Terminal" to open a new terminal window in Visual Studio Code.
![photo_2023-02-28 23 12 57](https://user-images.githubusercontent.com/123377628/221929726-9457ea77-1a19-4a3d-bb7f-8507daeafd5d.jpeg)

Compile and run your C++ code: In the terminal window, navigate to the folder where you saved your .cpp file using the cd command. Then, use the g++ command to compile your code (for example, “g++ hello.cpp -o output”). Once the compilation is complete, you can run the compiled program by typing “./output” in the terminal window.
![photo_2023-02-28 23 26 22](https://user-images.githubusercontent.com/123377628/221930445-4a4d6dc2-8b38-4d62-9edb-b88b8750c442.jpeg)

### Troubleshooting:
![photo_2023-02-28 23 52 59](https://user-images.githubusercontent.com/123377628/221936742-023458cc-38a6-4449-be1d-448600c5d097.jpeg)

![photo_2023-02-28 23 52 57](https://user-images.githubusercontent.com/123377628/221936786-bca47800-d08f-4597-913c-37cc53ecaead.jpeg)

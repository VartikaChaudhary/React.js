# React on Linux (Ubuntu)
Hello guys,

Today, here I present you a step by step guide on how to install and work in React on Ubuntu (Linux). As the craze of React is growing in people day by day, to the extent that all want to join the world of React.  But there are always a few missing/confusing starting points, which made few people difficult to understand React on its starting stage.

So here, I want to point out all the issues, anyone can get in their journey to React World step by step. Working on React in Linux is very similar to working in Windows or Mac. Only the given difference is in the process of installing. The whole process of the installation and working is divided into 3 steps.

Let’s get it-

### <div align="center">VISUAL STUDIO CODE</div>
Visual Studio Code or VS Code is a lightweight-powerful source code editor, used by variety of programming languages like- JavaScript, C++, Node.js etc.

* To download VS code, go to the Ubuntu software application. It’s just like Play store where you can find any app you want. 
* After opening Ubuntu software, go in the search bar and type VISUAL STUDIO CODE and press enter.
* When the search result will appear go to the icon of VS code and click on it.
* After clicking, at the right side, will be the option of install click on that.
* When the installation will be complete, click on the open button or you can go to the Show Applications and from there open the visual studio code.

<ins>**WHY SHOULD WE USE VISUAL STUDIO CODE**</ins>
1. It can easily edit, build and debug our code.
2. It works on hundred of programming languages
3. It provides a in-built terminal.
4. It also has syntax highlighting, bracket-matching, auto-indention and many more.<br>


### <div align="center">NODE.JS</div>
Node.js is a free open-source JavaScript run-time environment that helps in writing JavaScript code outside the web browser. As JS is the run-time environment it let the user to decide how they wanna use it, whether font-end or back-end.

* To download node.js open the terminal, and at first install bash by
><div align="center">*‘$ sudo apt-get install bash’*</div>
    after installing bash write the following command:
><div align="center">*‘$curl -sL https:deb.nodesource.com/setup_12.x | sudo -E bash’*</div>
    when above command execute successfully then write another one which will finally install the node.js into your system:
><div align="center">*‘$ sudo apt-get install -y nodejs’*</div><br>

* After installing node.js, checks it’s version to see if its installed properly or not by:
><div align="center">*‘$ node -v’*</div>
    this will give the latest version of the node installed in our system.<br>

* Now install the npm into the system by:
><div align="center">*‘$ sudo npm install npm@latest -g’*</div>
    this will install the latest version of npm into the system.<br>

* Check the version of npm by:
><div align="center">*‘$ npm -v’*</div><br>


### <div align="center">CREATE REACT APP</div>
Before creating the react app, we will make a new folder at the selected location, in which all of our react projects will be saved that we’ll make throughout our journey of React.

* Change the position of the terminal to the folder that we created just now to store all our projects of react app.
* After changing the position of the terminal write the command by which react app will get created into our system.
><div align="center">*‘$ npx create-react-app app-name’*</div>
* Wait till the command is executing.
* After the command is executed. Change the terminal position to the newly created react app now by:
><div align="center">*‘$ cd app-name’*</div>
* When the terminal position comes inside the react app then write the command which will open up the react browser page:
><div align="center">*‘$ npm start’*</div>
<ins>Now your react app is ready to go.</ins>

### HOW TO WORK ON REACT
* Working on react is simple. Open the visual studio code. Then open the project that we just created. You will see the project and its components after opening at the left side of the editor.
* There open the *index.js* file from under the section of *src*. 
* We will do all the codes in this file in the JSX format.
* This file will be linked to the *index.html* file under the section *public*  through import and export commands.
* The file *index.html* is the final file which present us our output of all the codes by presenting it in the browser.


<br><ins>**NOW LET’S SEE A FEW PROBLEMS THAT CAN ARIES DURING INSTALLING/CREATING THE REACT APP**</ins>
* <ins>React won’t accept the name of your project:</ins> The latest version of React has some changes in it. One of them is that it won’t accept the name of the project if there are any Capital Letters present in it. So, from start only write the name of your React App without any Capital Letters.
      
* <ins>Bad Internet Connection:</ins> It is the most common error that anyone can get. So check your connection properly before starting the steps to install the React. As the bad connection can slow down the whole process or can even terminate the process by which you have to start from the starting again.
      
* <ins>Command won’t run in terminal:</ins> Well as you may be installing react first time in your system there are commands that won’t run like the *‘sudo bash’*. This command may won’t run as your system doesn’t have bash by default, for which you have to install the bash before proceeding to the *sudo bash* command.
      
* <ins>React won’t accept the name *‘myreactapp’*:</ins> The name *‘myreactapp’* may be refused to be accepted for the react app name by the react as it will conflict with the files that the app will include once it installed. So, it’s better to give another name to your app before it produces any error.


### <br>HOW TO OPEN REACT APP AGAIN FOR WORKING
Once you complete the steps, your react app will open by itself in the browser. But what if you shut down the computer / laptop and when you open it again, how to open the react app browser page again. 

Will we have to go through all those processes again? But what about our previous saved work? Cause going though all those processes it will result in a new project of react not the old saved one.

So, will we never shut down our computer and just put it to sleep? But that’s not safe for our all work and documents present in the computer.

So what so we do? **Well all you have to do is nothing like these all crazy things. You just have to open the terminal again after login back to your computer / laptop, and go to the location where you have saved the folder which stores all our project. Then open the project folder though *‘cd’* command. And then at last write *‘npm start’* command. Just same what we did at last when creating the react app at the starting.**


<br>*<ins>That’s it. Hope all the above mentions steps and solutions will be useful to you all. Welcome to the React and enjoy it well.</ins>*

<br><ins>*Happy Coding...*</ins>

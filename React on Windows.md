# React on Windows
Hello guys,

Today, here I present you a step by step guide on how to install and work in React on Windows. As the craze of React is growing in people day by day, to the extent that all want to join the world of React.  But there are always a few missing/confusing starting points, which made few people difficult to understand React on its starting stage.

So here, I want to point out all the issues, anyone can get in their journey to React World step by step. The whole process of the installation and working is divided into 4 steps.

Let’s get it-

### <div align="center">VISUAL STUDIO CODE</div>
Visual Studio Code or VS Code is a lightweight-powerful source code editor, used by variety of programming languages like- JavaScript, C++, Node.js etc.

* The first step is to download the visual studio code. For that write download visual studio code in Google Search Bar and click on the first link that appear on the search list. From there choose the bit-size of your computer (64-bit/32-bit) and click on download.
* Once the software is downloaded install it on your working platform (PC/laptop) and open it.

<ins>**WHY SHOULD WE USE VISUAL STUDIO CODE**</ins>
1. It can easily edit, build and debug our code.
2. It works on hundred of programming languages
3. It provides a in-built terminal.
4. It also has syntax highlighting, bracket-matching, auto-indention and many more.

### <div align="center">NODE.JS</div>
Node.js is a free open-source JavaScript run-time environment that helps in writing JavaScript code outside the web browser. As JS is the run-time environment it let the user to decide how they wanna use it, whether font-end or back-end.

* To download node.js, go to Google Search Bar and write download node.js.
* Click on the first link that the Search List shows.
* Choose one from LTS or Current version of node.js.
* After it chooses the bit-size (64-bit/32-bit) under *windows installer (.msi)* section and click on download.
* After downloading node.js, install it on your working platform (PC/laptop).

### <div align="center">CHECKING VERSION</div>
* Once node.js is installed on your working platform, open terminal to check if its installed properly or not.
* Write <ins>**node -v**</ins> in terminal and if it shows the version, then its installed properly.
* Next write <ins>**npm -v**</ins> to check to version of npm. While installing node.js, npm got install by itself.
<br>OR
* You can open visual studio code’s terminal, by going into the menu bar and opening the terminal, and write the above command over there.

### <div align="center">CREATE REACT APP</div>
Before creating the react app, we will make a new folder at the selected location, in which all of our react projects will be saved that we’ll make throughout our journey of React.

* Create the folder at the selected location of your choice.
* Open the folder in visual studio code. The folder will store all of our projects.
* Now open the terminal to perform further codes.
* Write <ins>**npx create-react-app app-name**</ins> press enter and wait till the process is completing.
* When the process will complete, write <ins>**cd app-name**</ins>, to move the location to the app now.
* After that write <ins>**npm start**</ins> and a browser page will open, which will contain React logo with a Welcome to React line.
* After all these steps will complete look at the left side of the VS code. There will be our project name written under the folder. Click on the app-name and it will show all of the files that it contains.
* Now open the *index.js* file from *src* section, where we will work.
* Now we are finally ready to work in React through Windows. The work will be done in the *index.js* file which will link to the *index.html* file under *public* section through import and export properties.
* The file *index.html* is the final file through which our result will be display in browser and to the user or outer world.

### <br><ins>**NOW LET’S SEE A FEW PROBLEMS THAT CAN ARIES DURING INSTALLING/CREATING THE REACT APP**</ins>
* <ins>React won’t accept the name of your project:</ins> The latest version of React has some changes in it. One of them is that it won’t accept the name of the project if there are any Capital Letters present in it. So, from start only write the name of your React App without any Capital Letters.
* <ins>Bad Internet Connection:</ins> It is the most common error that anyone can get. So check your connection properly before starting the steps to install the React. As the bad connection can slow down the whole process or can even terminate the process by which you have to start from the starting again.
* The process of create react app may stop at the middle by itself and doesn’t process further even after waiting for few minutes. Here, two reasons can be found-
  - Bad Internet Connection
  - Problems in cmd terminal.
* For the Bad Connection you just have to check your internet.
* <ins>For the cmd terminal Problem-</ins> Sometimes the cmd terminal applications stop working by its own, which results in freezing all the work that’s going inside the terminal. To check whether its running or stopped-
  - Open the *RESOURCE MONITOR* application in your computer.
  - Go to the Overview Section of the application.
  - There you can see all the applications/software that's runs inside the computer.
  - Search for cmd terminal.
  - When you found cmd terminal checks its status. 
  - If the status is in running then the problem maybe from Internet Connection.
  - If the status is in stop then right click on the cmd terminal name and click on start/run the program. It may ask for permission from admin.
  - Once the application starts to run and the status goes back to running. The work that is freezes inside the terminal will start again by itself.

### <ins>HOW TO OPEN REACT APP AGAIN FOR WORKING</ins>
Once you complete the steps, your react app will open by itself in the browser. But what if you shut down the computer / laptop and when you open it again, how to open the react app browser page again. 
Will we have to go through all those processes again? But what about our previous saved work? Cause going though all those processes it will result in a new project of react not the old saved one.

So, will we never shut down our computer and just put it to sleep? But that’s not safe for our all work and documents present in the computer.

So what so we do? **Well all you have to do is nothing like these all crazy things. You just have to open the terminal again after login back to your computer / laptop, and go to the location where you have saved the folder which stores all our project. Then open the project folder though *‘cd’* command. And then at last write *‘npm start’* command. Just same what we did at last when creating the react app at the starting.**

<br>*<ins>That’s it. Hope all the above mentions steps and solutions will be useful to you all. Welcome to the React and enjoy it well.</ins>*

<br><ins>*Happy Coding...*</ins>

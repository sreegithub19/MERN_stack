Steps to run MERN_stack (M:MongoDB, E:Express, R:React, N:Node.js):<br>
(1) Commands to run the app:<br>
    &nbsp;&nbsp;&nbsp;&nbsp;(i) npm install express-generator -g<br>
    &nbsp;&nbsp;&nbsp;&nbsp;(ii) npm install -g express<br>
    &nbsp;&nbsp;&nbsp;&nbsp;(iii) express myapp<br>
    &nbsp;&nbsp;&nbsp;&nbsp;(iv) cd myapp<br>
(2) Replace the contents in <u>app.js</u> file with the content given here.<br>
(3) I have renamed the index.html file (in the public folder) to <u>jetpunk.html</u>. Replace the code in that file with the content given here.<br>
(4) This is the site I referred to for getting the webpage: https://www.jetpunk.com/<br>
(5) To store the "jetpunk" folder in your system and run the express app, it should be stored in public/images folder.<br>
(6) The jetpunk_github_files folder need not be downloaded. It consists of files that do not generate CORS issues. Hence, we can use them directly from the folder here in github.<br>
(7) Next set of commands to be run (in the myapp folder):<br>
    &nbsp;&nbsp;&nbsp;&nbsp;(i) npm init<br>
    &nbsp;&nbsp;&nbsp;&nbsp;(ii) npm install<br>
    &nbsp;&nbsp;&nbsp;&nbsp;(iii) npm start<br>
(8) The app starts running at: http://localhost:3000/jetpunk.html<br>
(9) The links of the files belonging to the "jetpunk_github_files" folder have been used directly from the "jetpunk_github_files" folder uploaded here in github, which enables Github to act as a database for some of our code files(All the files belonging to the jetpunk webpage cannot be used in a similar way due to CORS issues. The files producing CORS issues should be saved in our system under the folder name "jetpunk"). This github project is synced with MongoDB, hence covering all the 4 technologies of MERN stack.<br>

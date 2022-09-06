# Iakzhanova Irina
## Contact information:
**Mobile:** +996 777 208842

**E-mail:** irina.isakjanova@gmail.com

[Linkedin](https://www.linkedin.com/in/irina-isakzhanova-613a5a228)

[Github](https://github.com/iisakjanova)
******
## About myself:
I am a beginner programmer with excellent theoretical knowledge of web development and hands-on experience gained while working on course tasks. The best student on the course who constantly received the highest marks for assignments and performed exceptionally on the exams. I aim to grow my experience and am excited to implement my skills in real-world projects.
******
## Skills:
### Javascript
For a year, I have been studying javascript. During this period, I have built a decent amount of interactive web applications and got hands-on experience in software development. For my projects, I used pure javascript as well as various frameworks and libraries, among them
* jQuery
* React
* Redux
* Axios
* React Router

I worked with web API, implemented client-server communications, user authentication and authorization.
### HTML, CSS
I developed responsive, cross-browser adaptive web pages using HTML, CSS (including BEM methodology), sass and scss. Also, I have experience using open-source ui libraries such as Bootstrap, React Bootstrap, Material-UI, React Toastify etc. 
### Node.js
I have experience developing backend REST API using node.js, express.js, bcrypt, CORS, mongoDB, mongoose, postgreSQL. 
### Git
While working on my projects, I used Git for storing and managing my code.
******
## Code example:
Write a function to find the longest common prefix string amongst an array of strings.

If there is no common prefix, return an empty string "".
```
const longestCommonPrefix = function(strs) {
    if (strs.length === 1) {
        return strs[0];
    }
    
    let prefix = '';
    const firstWord = strs[0];
    
    for (let i = 0; i < firstWord.length; i++) {
        for (let j = 1; j < strs.length; j++ ) {
            const currentWord = strs[j];
            
            if (firstWord[i] !== currentWord[i]) {
                return prefix;
            }
        }
        
        prefix = prefix + firstWord[i];
    }
    
    return prefix;
};
```
******
## Experience:
### Some of my course tasks:
* [An application for selling things (like Lalafo, etc.).](https://github.com/iisakjanova/js_group_10_exam_11_irina_isakzhanova.git
) On home page items are divided into categories.  Page with detailed info about the item and seller opens by clicking on the item card. Implemented authorization and adding new items for authorized users.
* [A forum app](https://github.com/iisakjanova/js_group_10_homework_87_irina_isakzhanova.git) with an authorization where users can attach images and comment on posts.
* [A phone book application (contact list).](https://github.com/iisakjanova/js_group_10_exam_9_irina_isakzhanova.git) On home page contacts are shown. Page with a form for adding a new contact is opened by clicking the "add" button. The modal with "edit" and "remove" options is opened by clicking on the contact.
* [Todo list.](https://github.com/iisakjanova/TodoList.git) An application for creating a list of things are to be done throughout the day. Adding new, editing, removing and showing tasks is implemented.
******
## Education:
* January 2021 - November 2021. Attractor School Bishkek. Web-developer JavaScript (React + Node.js) courses with the highest current and exam grades among the group students
* 2005 - 2010. Bishkek Financial and Economic Academy. Diploma: Bachelor in Accounting, Analysis and Auditing
******
## Languages:
* Russian - Native
* English - Intermediate
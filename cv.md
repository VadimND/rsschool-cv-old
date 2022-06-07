My full name is Vadim Dyshlevich.

## Contact Info
__Email:__ webzorka24@gmail.com  
__Phone:__ +375 29 870-39-14  
__Nickname on Github:__ VadimND  
__Telegram Username:__ @javadimus  
__Website:__ vk.com/javadimus  

## Summary
I work as a programmer in a government Agency and strive to expand my skills in webdevelopment.  
I am particularly interested in front-end and related technologies: Javascript, HTML&CSS, web design and back-end a bit (PHP, NodeJS). 
Before I got a job as a programmer, I was engaged in freelancing for almost five years. Now I'm trying to get a deep knowledge of JavaScript and teamwork.  

## Skills
The main programming language is Javascript. I have a solid body of practical knowledge: how to make a modal window, how to check the feedback form, how to make a menu, etc. 
I have a Good command of the JQuery framework. Worked with many jQuery plugins.  
In addition, I have been working with CMS platforms for quite a long time. The most favorite of them is Wordpress.  
I understand PHP code, I have experience in building SQL queries.  
The knowledge and skills base that allowed me to engage in web development, I received during training as a web programmer at IBMT BSU.  
In this educational institution, we were taught not only the basics of programming, but also working with graphics. In the course of training, I mastered such programs as Notepad++, Atom, PHPStorm, Visual Studio Code, Photoshop, Corel, 3DS Max, Adobe Animate.

## Code examples
* Replacing styles based on date attributes (JS)
* Class for form validation, calculating the cost of services and sending to the server (ASP, JS, Ajax)
* Sending a form with an attachment (ASP, JS, Ajax)
* Solving tasks on Codewars

### Prefill an Array
```
function prefill(n, v) {  
    if (isNaN(n)) {
        throw new TypeError(n + " is invalid");
    }
    if (n === Infinity || n === -Infinity) {
        throw new TypeError(n + " is invalid");
    }
    if (n < 0) {
        throw new TypeError(n + " is invalid");
    }
    if (typeof n === 'boolean') {
        throw new TypeError(n + " is invalid");
    }
    if (!isNaN(n) && n.toString().indexOf('.') != -1) {
        throw new TypeError(n + " is invalid");
    }
    let arr = [];
    
    for(let i = 0; i < n; i++) {
        arr.push(v);
    }                            
    return arr;                           
    
}
``` 
### Count words
```
function countWords(str) {  
    let res; 
    let arr = [];
    if(str !== "" && !str.includes(" ") && !str.includes("")) {    
        res = 1;
    }
    if(str !== "" && !str.includes(" ") && str.includes("")) {    
        res = 0;
    }
    if(str !== "" && str.includes(" ")) {
        res = str.trim().split(" ");
        for (let i = 0; i < res.length; i++) {
        if (res[i] !== "") {
            arr.push(res[i]);
        }
        }
        res = arr.length;
    }      
    if(str === "" || str === "") {
        res = 0;
    } 
    if (str.indexOf("") === 0 && str.includes(" ")) {
        str = str.replace(str.charAt(0), "")
        res = str.match(//g).length + 1;
    }   
    if (str.indexOf("") > 0 ) {
        res = str.match(//g).length + 1;
    }                           
    return res;  
}
``` 
## Experience 
I presented my first project in 2015 during the defense of my thesis. This work included creating a website from scratch for a beauty Studio. As a result, I successfully defended my work. After studying at the Institute, I also have a lot of practical work related to creating web pages.  
I have created several websites that are still working. In addition to creating, I also support several online projects. My current job is related to website development. I am creating a website for a large state library.

## Education 
* Institute of business and management of technology of Belarusian state University (specialty "Web-design and computer graphics")
* RssSchool (Js, 2020)
* GeekBrains (JavaScript JavaScript, HTML, PHP, English)* 
* Codecademy (JS, React, Angular)
* HTMLAcademy (html, css)
* Codewars (JS)

## English
I regularly read literature in English, not only professional, but also artistic.  
For example, the book "Three in a boat, not counting the dog", "Three Musketeers".  
I listen to English-language radio stations, translate popular songs from English to Russian.
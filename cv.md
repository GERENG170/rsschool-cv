# Artur Herenh
![my-photo](/photo.png "my photo")
### Junior Frontend Developer
********* 
### Contacts :
* **Phone:** +375 (29) 538-34-05
* **E-mail:** artur.herenh2000@gmail.com
* **LinkedIn:** www.linkedin.com/in/artur-gereng
* **GitHub:** www.github.com/GERENG170
* **Discord:** Artur Herenh(@GERENG170)

********* 
### About Me
Hello. I am 22 years old. I've been programming for 4 years now. The first 3 years there was no result, because I did not exercise regularly. I just studied something and decided for the soul. Before front-end I studied java and after python. Touching them, I realized that this is not mine yet.I have been studying front-end for the last year. And it seems to me that I succeeded in this. I am currently learning react and typescript. It used to be my hobby. But my dream is to make programming my profession.
Currently I am writing my educational projects on react, typescript. I have them on github

********* 
### Skills
* HTML5
* CSS3,SCSS,SASS 
* Bootstrap, Adaptive design, Grid, Flexbox
* JavaScript (ES5 – ES11), Node.js platform
* Typescript
* React.js
* Webpack, Babel
* Git
* Figma
* JSON server

********* 
### Last projects
* github.com/GERENG170/reactHooksTD **(react,hooks,ts,webpack,babel,json-server)**
* github.com/GERENG170/SKBoocks  **(react,ts,webpack,babel,scss)**

********* 
### Code Examples
#### Human readable duration format from CODEWARS:
```
function formatDuration (seconds) {
    let year = 31536000;
    let day = 86400;
    let hour = 3600;
    let minute = 60;
    let second = 1; 
    let str = "";
    let x;
    let arr = [];
    if(seconds >= year){
        x = parseInt((seconds/year));
        seconds = seconds%year;
        x > 1 && seconds > 0 ? str+=`${x} years, ` : 
        x > 1 && seconds == 0 ? str+=`${x} years` : 
        x == 1 && seconds == 0 ? str+=`${x} year` : 
        str+=`${x} year, `;
    }
    if(seconds >= day){
        x = parseInt((seconds/day));
        seconds = seconds%day;
        x > 1 && seconds > 0 ? str+=`${x} days, ` : 
        x == 1 && seconds > 0 ? str+=`${x} day, ` :
        x > 1 && seconds == 0 && str!= false ? str+=`and ${x} days` :
        x > 1 && seconds == 0 && str == false ? str+=`${x} day, ` :  
        x == 1 && seconds == 0 && str != false ? str+=`and ${x} days` :
        str+=`${x} days, `;
    }
    if(seconds >= hour){
        x = parseInt((seconds/hour));
        seconds = seconds%hour;
        let hz = seconds%minute;
        x > 1 && seconds > 0 && hz > 0? str+=`${x} hours, ` : 
        x == 1 && seconds > 0 && hz > 0? str+=`${x} hour, ` :
        x > 1 && seconds > 0 && hz == 0? str+=`${x} hours ` : 
        x == 1 && seconds > 0 && hz == 0? str+=`${x} hour ` :
        x > 1 && seconds > 0 && hz == 0? str+=`${x} hours ` : 
        x == 1 && seconds > 0 && hz == 0? str+=`${x} hour ` :
        x == 1 && seconds == 0 ? str+=`${x} hour` :
        x > 1 && seconds == 0 && str!= false ? str+=`and ${x} hours` :
        x > 1 && seconds == 0 && str == false ? str+=`${x} hours` :  
        x == 1 && seconds == 0 && str != false ? str+=`and ${x} hour` :
        str+=`${x} hour, `;
    }
    if(seconds >= minute){
        x = parseInt((seconds/minute));
        seconds = seconds%minute;
        x > 1 && seconds > 0 ? str+=`${x} minutes and` : 
        x == 1 && seconds > 0 ? str+=`${x} minute and` :
        x > 1 && seconds == 0 && str!= false ? str+=`and ${x} minutes` :
        // x > 1 && seconds == 0 && str == false ? str+=`${x} minutes,` :  
        x == 1 && seconds == 0 && str != false ? str+=`and ${x} minute` :
        str+=`${x} minutes`;
    }
    if(seconds >= 1){
        seconds > 1 && str == false ? str+=`and ${seconds} seconds` : 
        seconds > 1 && str != false ? str+=` ${seconds} seconds` : 
        seconds > 1 && str == false ? str+=`${seconds} seconds` : 
        seconds = 1 && str != false ? str+=` ${seconds} second` : 
        str+=`${seconds} second`;
    }
    str == false ? str += "now" : null;
    return str; 
}
```
********* 
### Experience
* **Itransition** trainee ROR developer

********* 
### Education
* **BSUIR - Minsk Radio Engineering College** 
* **Itransition - trainee ROR developer**
* **Underground language club - english**
* **Udemy - JavaScript + React**

********* 
### Languages
* **Russian** - Native
* **Belorussian** - Native
* **English** - В1 (Underground language club)
* **Polish** - A2
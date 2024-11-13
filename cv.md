# __Putyrski Pavel__

***
## Navigation
[Contacts](#Contacts) - [About Me](#About-Me) - [Skills](#Skills) - [Code example](#Code-example) -
[Education](#Education) - [English](#English)
***
## Contacts
+ location: Minsk
+ email: gitarist.pasha@gmail.com
+ telegram: [@smile_soul](https://telegram.org/)
+ Discord: [@Pavel](https://discordapp.com/users/1284812557756006450/)
+ GitHub: [PrivatePython](https://github.com/PrivatePython)

***

## About Me
Hi, I'm Pavel. I'm 28 years old.I graduated from the
university as a civil engineer. I was working for a building company  
and for the last five years I've worked as an international transportation driver.
I've been learning JavaScript programming for a year and a half.  
I enjoy programming and am determined to become a high-level programmer.

On these jobs I had to take into account many things:
1. to know:
    + the rules of transportation of different countries
    + the rules of transportation of different cargoes
    + the customs regulations of different countries
    + the port regulations
2. to make schedules and routes of transportation
3. as well as to communicate with logisticians, consignees,
   customs authorities and other services
4. maintain working documentation

These jobs have taught me:
+ time management
+ teamwork
+ learning new things under tight deadlines
+ do work with quality and on time
+ optimize workflows
***

## Skills
+ Markdown
+ HTML
+ CSS
+ JavaScript
+ JQuery(basics)
+ React(basics)
+ AntDesign(basics)
+ Git
+ Figma

## Code example
> Example of solving a problem with CodeWars
>
> Write a function, which takes a non-negative integer (seconds) as input and returns the time in a human-readable format (HH:MM:SS)
>
> HH = hours, padded to 2 digits, range: 00 - 99  
> MM = minutes, padded to 2 digits, range: 00 - 59  
> SS = seconds, padded to 2 digits, range: 00 - 59
>
> The maximum time never exceeds 359999 (99:59:59)  
>You can find some examples in the test fixtures.
```js
function humanReadable (seconds) {
    if(seconds >= 0 && seconds <= 359999){
        let hour = Math.trunc(seconds / 3600)
        let minute = Math.trunc(seconds % 3600 / 60)
        let second = Math.trunc(seconds % 3600 % 60)
        const arrDate = [hour, minute, second]
        let dateString = '';
    
        arrDate.forEach((el,index)=>{
            if(el === 0){
                dateString += '00'
            }else if(el > 0 && el < 10){
                dateString += '0' + el
            }else dateString += el;
            arrDate.length - 1 === index ? dateString += '': dateString += ':';
        })
        return dateString
    }
    return '';
} 
```

## Education
+ [Yanka Kupala State University of Grodno (civil engineer)](https://en.grsu.by/en/)
+ BelhardAcademy (JS Advanced)
+ RSSchool(Currently studying)
+ Self-study

## English
My level of English is now elementary([my sertificate](https://cert.efset.org/zmSUUr)), but I am now actively learning  
the language with a teacher.
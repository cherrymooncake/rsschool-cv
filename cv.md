
# **Anastasia Isakova**
## ***Junior Frontend Developer***
===

### About myself


I'm a beginner frontend developer and first-year student of the Faculty of Information Technology.
I have been interested in design and 3D modeling for a long time, but a year ago I started to try my
hand at programming. This was a big (and pleasant) surprise for me, because I previously thought that
this sphere was not suitable for me, but after practice I changed my mind.


I like to face various kinds of problems and find solutions for them. In programming, which is developing
rapidly every day, it is impossible to learn everything, and I am attracted by this opportunity to 
constantly develop myself and discover something new.


I enjoy creating websites and making them look aesthetically pleasing and user-friendly. Now I try to 
devote my free time to the practical application of things already studied, as well as to the study  of
JS frameworks and TypeScript.


---

### Contacts

   e-mail: an.isakovaa@gmail.com
   github: [cherrymooncake] (https://github.com/cherrymooncake)
   discord: cherrymooncake

----
### LANGUAGES
 * English
     + Intermediate
 * Russian
     + Native
 * Belarusian
     + Native
 * German
     + Elementary

---

### HARD SKILLS

  * HTML5, CSS3, SASS, XML
  * JavaScript
  * Responsive design
  * Cross Browser testing
  * BEM methodology
  * Git, GitHub
  * VS Code, Adobe Photoshop, Figma
  * UI/UX design basics
  * Backend basics (C, C++)
---

### EDUCATION

BSTU, Information technology software, Bachelor's degree

----

### COURSES
* HTML and CSS Tutorials on w3schools
* JavaScript Manual on learnjavascript.ru
* RS Schools «JavaScript/Front-end. Stage 0»
* Web developing on Coursera

----

### CODE EXAMPLE

> Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the
> elements to the right of that index  equals the sum of the elements to the left of that index. If there
> is no such index, return -1. If there is more than one such index, return the left-most index

```
    function peak(arr) {
          
            for (let i = 1; i < arr.length - 1; i++) {
              let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
              let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
          
              if (leftSum === rightSum) return i;
            }
            return -1;
          }
```


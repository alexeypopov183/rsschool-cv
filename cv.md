# Alexey Popov
***
## My contact info:
* **Phone:** +7-929-434-5769
* **E-mail:** alexeypopov183@gmail.com
* *GitHub:* [click me](https://github.com/alexeypopov183)
* *CodeWars:* [click me](https://www.codewars.com/users/alexeypopov183)
***
## About me
I`m 23 years old. Interest in the field of IT arose during school years, but did not know exactly where to go. Now I have learned about Frontend and I am ready to go towards my goal.
***
## Skills and Proficiency:
* HTML, CSS
* JS
* Git
* Figma, PS
* Vim, VS Code
***
## Code examples:
* 6 kyu kata. Your order, please. 
*Your task is to sort a given string. Each word in the string will contain a single number. This number is the position the word should have in the result.*
### First solution:
```
 function order(words){
    let result = words.match(/[0-9]/g);
    let arr = words.split(' ');
    if(words === null || words === '') {
      return '';
    }
    let newArr = result.reduce((acc, item, i) => {
      acc[item] = arr[i]
      return acc
    }, {})
    return Object.values(newArr).join(' ')
  }
```
### After refactor
```
function order(words){
 return words.split(' ').sort((a, b) => a.match(/\d/) - b.match(/\d/)).join(' ')
}
```
***
## Education
* Baikal State University
    + Management 5 course






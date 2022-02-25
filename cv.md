# **Makhotkina Angelina**
### Junior Front-end Developer

## **About me**
Upcoming developing specialist in the field of computer science, student with large dreams about future. 

## **Skills**
* multitask
* assertive
* fast learner
* competitive

## **Code examples**
JavaScript examples from CodeWars (*6 kyu*)

Given a lottery ticket (ticket), represented by an array of 2-value arrays, you must find out if you've won the jackpot.
```
function bingo(ticket, win){
let miniWins = 0;
let stringCodes = ticket.map( subarray => Array.from(subarray[0]).map(letter => letter.charCodeAt()));
for (let i = 0; stringCodes[i]; i++) {
if(stringCodes[i].includes(ticket[i][1])) {
miniWins++;
}
}
return miniWins >= win ? "Winner!" : "Loser!";
}
```

Write a function that takes an integer as input, and returns the number of bits that are equal to one in the binary representation of that number. You can guarantee that input is non-negative.
```
let countBits = function(num){
let oneInBinary = 0;
let n = num;
while (n) {
if (n % 2 === 1) oneInBinary++;
n = Math.floor(n / 2);
}
return oneInBinary;
};
/* one more solution
const countBits = (num) => {
let numInBinary = Array.from(num.toString(2));
let i;
i = numInBinary.filter(char => char === "1");
return i.length;
} */

```
## **Experience**

[Eco-sounds](https://angelmakh.github.io/eco-sounds/)
Thanks to [Rolling Scopes Schools](https://rs.school/js-stage0/)

Also I have basic c++ knowlenge.

## **Education**
* 2019 - 2021 BSUIR Lyceum (Lyceum №1)

math and physics extracurricular classes



* 2021 - current time bachelor's degree

Belarusian State University of Informatics and Radioelectronics (BSUIR)

Faculty of Information Technologies and Control, major in Automated information processing systems

## **Languages**
* English B1+
* Russian native
* Belarusian native

## **Contacts**
Belarus, Minsk
[inst](https://www.instagram.com/makhotkinaangelina/?utm_medium=copy_link)
[github](https://github.com/AngelMakh)
# CV
## Name
ALIAKSANDR SAS
## Contacts

* Email: a.sass@tut.by
* Skype: live:.cid.caa06d5130796232
* Mobile: +375 (29) 823 79 19
* Discord: aleksadr-sass#4199

## About myself

Mogilev (Belarus). PreJunior FrontEnd Developer. I have no IT experience, but I can fast learn new technologies.

## Technical skills
Git, MySQL, HTML, CSS, JavaScript, Visual Studio Code

## Code samples
[Multiples of 3 or 5](https://www.codewars.com/kata/multiples-of-3-or-5)

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

The task was to write a function that returns the sum of all the multiples of 3 or 5 below the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them).

```
function solution(number){
    if(number<=0) return 0;
    let n = (a) =>Math.floor((number-1)/a);
    let sum = (b, c) =>(1+b)*b/2*c;    
    return sum(n(3), 3)+sum(n(5), 5)-sum(n(15), 15);    
}
```
## Education
* BNTU, Powerengineering faculty, Electrical networks (2010-2015, Minsk)
* BRU, Institute of Advanced Studies, Software Engineer (2018-2019, Mogilev)
* Courses:
    * Software Development (12.2020-02.2021, [Itransition](https://itransition.by/training-dev), Online)
    * Node.js Development (05.2021-07.2021, [RSSchool](https://rs.school/nodejs/), Online)

## English skills
B1
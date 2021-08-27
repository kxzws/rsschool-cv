# Aliona Bulanava #

## My contact info ##
- __location:__ Minsk, Belarus
- __phone:__ +375 (29) 642-63-34
- __e-mail:__ kxzws54@gmail.com
- __github:__ [kxzws](https://github.com/kxzws/ "github")

## About me ##
I would like to participate in projects, which will allow me to show my skills. I always take feedback positively. My time-management helps me pay attention to essential details enough and follow to always-learning attitude.

## Skills ##
- HTML, CSS (Bootstrap)
- JavaScipt (Fundamentals, ES6+, DOM)
- C++ (basic knowledge)
- OOP (basic knowledge)
- Git (GitHub)
- Visual Studio Code, Visual Studio
- Figma

## Code example ##
_kata_ from [codewars](https://www.codewars.com/ "codewars"): 
> write a function, persistence, that takes in a positive parameter num
> and returns its multiplicative persistence, which is the number of times
> you must multiply the digits in num until you reach a single digit.

```javascript
function persistence(num) {
  let count = 0, compNum = 1;
  while (num > 9) {
    while (num !== 0) {
      compNum *= num % 10;
      num = (num - (num % 10)) / 10;
    }
    num = compNum;
    compNum = 1;
    count++;
  }
  
  return count;
}
```

## Education ##
- __University__:
  - Belarusian State University of Informatics and Radioelectronics, Information Technologies in Automated Systems
- __Courses__:
  - [CS50](https://www.youtube.com/playlist?list=PLawfWYMUziZqyUL5QDLVbe3j5BKWj42E5) youtube lectures (in proccess..)
  - [Stepik](https://stepik.org/course/38218/syllabus?auth=login)
  - [Glo Academy](https://glo-academy.org/)
  - [HTML Academy](https://htmlacademy.ru/)
  - [Codecademy](https://www.codecademy.com/)

## Languages ##
- __Russian__ - native
- __English__ - intermediate/advanced (according to the online test at [https://www.efset.org](https://www.efset.org/quick-check))

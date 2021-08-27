# Aliona Bulanava
## My contact info
- __location:__ Minsk, Belarus
- __phone:__ +375 (29) 642-63-34
- __e-mail:__ kxzws54@gmail.com
- __github:__ [kxzws](https://github.com/kxzws/ "github")
## About me

## Skills

## Code example
kata from [codewars](https://www.codewars.com/ "codewars"): 
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
## Education

## Languages
- __Russian__ - native
- __English__ - intermediate/advanced (according to the online test at [https://www.efset.org](https://www.efset.org/quick-check))

# Aliona Bulanava
## My contact info
- __location:__ Minsk, Belarus
- __phone:__ +375 (29) 642-63-34
- __e-mail:__ kxzws54@gmail.com
- __github:__ [kxzws](https://github.com/kxzws/ "github")
## About me

## Skills

## Code example
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

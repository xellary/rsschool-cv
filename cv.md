# Evgeniy Birukov
## Junior Frontend Developer

## Contacts 
* Email: eugenebiruk1@gmail.com
* Telegram: @ev_geniusb
* Github: [xellary](https://github.com/xellary)
* Discord: gus__fring

## About Me
I study computer science and engineering. I’m responsible, work well in a team, and love learning new things, especially in frontend development. I hope my effort will help me succeed in this course!

## Skills
* HTML5
* CSS3/SASS
* JavaScript Basics
* Git
* Java Basics

## Code Example
Persistent Bugger Kata from Codewars: Write a function, `persistence`, that takes in a positive parameter `num` and returns its multiplicative persistence, which is the number of times you must multiply the digits in `num` until you reach a single digit.

```javascript
function persistence(num) {
  let persist = 0;
  while (num.toString().length != 1) {
    let mul = 1;
    for (let i = 0; i < num.toString().length; i++) {
      mul *= num.toString()[i];
    }
    num = mul;
    persist++;
  }
  return persist;
}
```

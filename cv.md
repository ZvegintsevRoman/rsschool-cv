# *Zvegintsev Roman*

## *Contact Info*

- Email: *zvegintsev.roma@yandex.by*
- Phone / Viber: *+375 (29) 368-74-58*
- Skype: *live:romaquid*
- Telegram: [*@ZvegintsevRoman*](https://t.me/ZvegintsevRoman)

## *Summary*

At my first job as an electronics engineer at Belarusian Railways I was frequently dealing with various information systems and web-based applications that help people in their daily tasks, and thus it was natural for me to get interested in web development. It was owing to this interest that I started exploring front end.

## *Skills*

**HTML 5**, **CSS 3**, **JavaScript ES6**, **Git**, **Angular**, **Mercurial**, **Ionic**, **Scss**, **TypeScript**

## *Code Example*

[*6 kyu. Shortest steps to a number CodeWars kata solution*](https://www.codewars.com/kata/5cd4aec6abc7260028dcd942)

```javascript
function shortestStepsToNum(num) {
  let count = 0;
  while (num !== 1) {
    if (num % 2 === 0) {
    num /= 2;
    count++;
    } else {
    num -= 1;
    count++;
    }
  }
  return count;
}
```

[*6 kyu. Count characters in your string CodeWars kata solution*](https://www.codewars.com/kata/52efefcbcdf57161d4000091)

```javascript
function count (string) {  
   let result = {};
   string.split('').forEach(letter => {
     result.hasOwnProperty(letter)
       ? result[letter]++
       : result[letter] = 1;
   });
   return result;
}
```
## Viktar Harbachou 

## Contact Info

- **City:** Gomel, Belarus
- **Phone:** +37529 7329680
- **Telegram / Skype:** Viktar Harbachou
- **Email:** victor.gorbachew@gmail.com

## Summary

10 years of experience on the Belarusian railway as a communications engineer gave me the necessary skills in engineering, an extremely responsible approach to work and stress resistance. The desire for self-development and moving forward pushed to the study of web development. Now - this is the main goal, the motivation to learn new technologies every day more and more. I look forward to new challenges in order to become better at programming.

## Skills

- **Programming languages:** JavaScript(ES5, ES6)
- **Web technology:** HTML5, CSS3
- **IDE:** VS Code, Brackets
- **Version control:** Git

## Code examples

**Calculator program**
___
**JavaScript code:**
```
function plus(){
    let num1, num2, result;
    num1 = document.getElementById('n1').value;
    num1 = parseInt(num1);
    num2 = document.getElementById('n2').value;
    num2 = parseInt(num2);
    result = num1 + num2;
    document.getElementById('out').innerHTML = result;
}
function minus(){
    let num1, num2, result;
    num1 = document.getElementById('n1').value;
    num1 = parseInt(num1);
    num2 = document.getElementById('n2').value;
    num2 = parseInt(num2);
    result = num1 - num2;
    document.getElementById('out').innerHTML = result;
}
function multiply(){
    let num1, num2, result;
    num1 = document.getElementById('n1').value;
    num1 = parseInt(num1);
    num2 = document.getElementById('n2').value;
    num2 = parseInt(num2);
    result = num1 * num2;
    document.getElementById('out').innerHTML = result;
}
function divide(){
    let num1, num2, result;
    num1 = document.getElementById('n1').value;
    num1 = parseInt(num1);
    num2 = document.getElementById('n2').value;
    num2 = parseInt(num2);
    result = num1 / num2;
    document.getElementById('out').innerHTML = result;
}
```
**HTML code:**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <script src="js/main2.js" defer></script>
</head>
<body>
     <p>Число1: <input type="text" id="n1"></p>
     <p>Число2: <input type="text" id="n2"></p>
     <button onclick="plus()">+</button>
     <button onclick="minus()">-</button>
     <button onclick="multiply()">*</button>
     <button onclick="divide()">/</button>
     <hr>
     <p id="out">Результат:</p>
</body>
</html>
```
___

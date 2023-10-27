<h1 align="center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="center">Лабораторная работа №4</p>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="right">Выполнил: Морошкин Максим Александрович</p>
<p align="right">Проверил: Соболев Е. И.</p>
<br>
<br>
<br>
<br>
<br>
<br>

<p align="center">г. Южно-Сахалинск <br> 2023 год</p>

<h2 align="center">Введение</h2>
<p align="justify">Основы языка JavaScript</p>

<h2>Цели и задачи</h2>
1.	Рассчитать значение у при заданном значении х
<br>
2.	Дано натуральное число n (n<=9999). Выяснить, является ли оно палиндромом
("перевертышем") с учетом четырех цифр, как, например, числа 7777, 8338, 0330 и т. п. (Палиндромом называется число, десятичная запись которого читается одинаково слева направо и справа налево.)
<br>
3.	Год является високосным, если его номер кратен 4, однако из кратных 100 високосными являются лишь кратные 400, например, 1700, 1800 и 1900 — невисокосные года, 2000 — високосный. Дано натуральное число n. Определить, является ли високосным год с таким номером.
<br>
4.	Составить программу для вычисления значения функции y(x): 
<br>
5.	Составить программу, которая в зависимости от порядкового номера дня месяца (1, 2, ..., 12) выводит на экран время года, к которому относится этот месяц.
<br>
6.	Мастям игральных карт условно присвоены следующие порядковые номера: масти "пики" — 1, масти "трефы" — 2, масти "бубны" — 3, масти "червы" — 4, а достоинству карт: "валету" — 11, "даме" — 12, "королю" — 13, "тузу" — 14 (порядковые номера карт остальных достоинств соответствуют их названиям: "шестерка", "девятка" и т. п.). По заданным номеру масти m (1 m 4) и номеру достоинства карты k (6 k 14) определить полное название (масть и достоинство) соответствующей карты в виде "Дама пик", "Шестерка бубен" и т. п.
<br>
7.	В некоторых странах Дальнего Востока (Китае, Японии и др.) использовался (и неофициально используется в настоящее время) календарь, отличающийся от применяемого нами. Этот календарь представляет собой 60-летнюю циклическую систему. Каждый 60-летний цикл состоит из пяти 12-летних подциклов. В каждом подцикле года носят названия животных: Крыса, Корова, Тигр, Заяц, Дракон, Змея, Лошадь, Овца, Обезьяна, Петух, Собака и Свинья. Кроме того, в названии года фигурируют цвета животных, которые связаны с пятью элементами природы — Деревом (зеленый), Огнем (красный), Землей (желтый), Металлом (белый) и Водой (черный). В результате каждое животное (и его год) имеет символический цвет, причем цвет этот часто совершенно не совпадает с его "естественной" окраской — Тигр может быть черным, Свинья — красной, а Лошадь — зеленой. Например, 1984 год — год начала очередного цикла — назывался годом Зеленой Крысы. Каждый цвет в цикле (начиная с зеленого) "действует" два года, поэтому через каждые 60 лет имя года (животное и его цвет) повторяется. Составить программу, которая по заданному номеру года нашей эры n печатает его название по описанному календарю в виде: "Крыса, Зеленый". Рассмотреть два случая: а) значение n 1984; б) значение n может быть любым натуральным числом.
<br>
8.	Напечатать таблицу умножения на 9.
<br>
9.	Напечатать "столбиком" значения sin 2 , sin 3 , ..., sin 20 .
<br>
10.	Найти: а) сумму всех целых чисел от 100 до 500; б) сумму всех целых чисел от a до 500 (значение a вводится с клавиатуры; a<=500); в) сумму всех целых чисел от –10 до b (значение b вводится с клавиатуры; b=>–10); г) сумму всех целых чисел от a до b (значения a и b вводятся с клавиатуры; b=>a).
<br>
11.	Вычислить сумму
 <br>
12.	Даны натуральные числа х и у. Вычислить произведение x и y, используя лишь операцию сложения. Задачу решить двумя способами.
<br>
13.	Составить программу возведения натурального числа в квадрат, учитывая следующую закономерность
<br>
14.	Вычислить сумму
<br>
15.	Дана непустая последовательность целых чисел, оканчивающаяся нулем. Найти: а) сумму всех чисел последовательности; б) количество всех чисел последовательности.
<br>
16.	Дана непустая последовательность неотрицательных целых чисел, оканчивающаяся отрицательным числом. Найти среднее арифметическое всех чисел последовательности (без учета отрицательного числа).
<br>
17.	Дано натуральное число. Определить: а) количество цифр 3 в нем; б) сколько раз в нем встречается последняя цифра; в) количество четных цифр в нем. Составное условие и более одного неполного условного оператора не использовать; г) сумму его цифр, больших пяти; д) произведение его цифр, больших семи; е) сколько раз в нем встречаются цифры 0 и 5 (всего).
<br>
18.	Дано натуральное число, в котором все цифры различны. Определить: а) порядковый номер его максимальной цифры, считая номера: от конца числа; от начала числа; б) порядковый номер его минимальной цифры, считая номера: от конца числа; от начала числа.
<br>
19.	Дано натуральное число. Выяснить, является ли оно простым (простым называется натуральное число, большее 1, не имеющее других делителей, кроме единицы и самого себя). Оператор цикла с параметром не использовать.
<br>
20.	Дано натуральное число. Установить, является ли последовательность его цифр при просмотре их слева направо упорядоченной по возрастанию. Например, для числа 1478 ответ положительный, для чисел 1782 и 1668 — отрицательный и т. п.
<br>
21.	Дана непустая и упорядоченная по возрастанию последовательность целых чисел, оканчивающаяся числом 10 000. Определить порядковый номер первого числа, большего заданного n. Если таких чисел в последовательности нет, то на экран должно быть выведено соответствующее сообщение.
<br>
22.	Дано натуральное число. Верно ли, что цифра a встречается в нем реже, чем цифра b?
<br>
23.	Имеется фрагмент программы в виде оператора цикла с параметром, обеспечивающий вывод на экран "столбиком" всех целых чисел от 10 до 30. Оформить этот фрагмент в виде: а) оператора цикла с предусловием; б) оператора цикла с постусловием.
<br>
Задачи CodeWars:
<br>
1.	https://www.codewars.com/kata/head-tail-init-and-last
<br>
2.	https://www.codewars.com/kata/array-deep-count
<br>
3.	https://www.codewars.com/kata/length-of-missing-array
<br>
4.	https://www.codewars.com/kata/pair-of-gloves
<br>
5.	https://www.codewars.com/kata/sorting-by-bits
<br>
6.	https://www.codewars.com/kata/lets-recycle
<br>

<h2>Решение задач</h2>

```js

//задача 1
function task1() {
    let x = prompt("Введите значение x: ", "2")
    let result;
    if (x > 0) {
        result = Math.pow(Math.sin(x), 2);
    }
    else {
        result = 1 - 2 * Math.pow(Math.sin(x), 2);
    }
    alert(result);
}

//задача 2 
function task2() {
    let n = prompt("Введите значение n: ", "0880")
    // Преобразуем число в строку для более удобной работы с цифрами
    const numStr = n.toString();
    // Проверяем, имеет ли число 4 цифры
    if (numStr.length !== 4) {
        alert("Число n<=9999")
    }
    // Проверяем, является ли строка палиндромом
    if (numStr === numStr.split('').reverse().join('')) {
        alert("Число палидром")
    }
    else {
        alert("Число не палидром")
    }
}

//задача 3
function task3() {
    let year = prompt("Введите год ", "2002")
    if ((year % 4 === 0 && year % 100 !== 0) || year % 400 === 0) {
        alert(year + " - високосный год.");
    } else {
        alert(year + " - не високосный год.");
    }
}

//задача 4
function task4() {
    let x = prompt("Введите значение x: ", "2")
    let result;
    if (x < -1) {
        result = -1;
    }
    else {
        if (x > -1) {
            result = x;
        }
        else {
            if (x == -1) {
                result = 1;
            }
        }
    }
    alert(result);
}

//задача 5
function task5() {
    let month = prompt("Введите месяц: ", "5")
    let season;

    if (month >= 1 && month <= 2 || month === 12) {
        season = "Зима";
    } else if (month >= 3 && month <= 5) {
        season = "Весна";
    } else if (month >= 6 && month <= 8) {
        season = "Лето";
    } else if (month >= 9 && month <= 11) {
        season = "Осень";
    } else {
        season = "Некорректный номер месяца";
    }
    alert("Этот месяц относится к времени года: " + season);
}

//задача 6
function task6() {
    let m = parseInt(prompt("Введите m: ", "5"))
    let k = parseInt(prompt("Введите k: ", "7"))
    let suit;
    let rank;

    switch (m) {
        case 1:
            suit = "пики";
            break;
        case 2:
            suit = "трефы";
            break;
        case 3:
            suit = "бубны";
            break;
        case 4:
            suit = "червы";
            break;
        default:
            suit = "неизвестная масть";
    }

    switch (k) {
        case 6:
            rank = "шестерка";
            break;
        case 7:
            rank = "семерка";
            break;
        case 8:
            rank = "восьмерка";
            break;
        case 9:
            rank = "девятка";
            break;
        case 10:
            rank = "десятка";
            break;
        case 11:
            rank = "валет";
            break;
        case 12:
            rank = "дама";
            break;
        case 13:
            rank = "король";
            break;
        case 14:
            rank = "туз";
            break;
        default:
            rank = "неизвестное достоинство";
    }
    alert(rank + " " + suit);
}

//задача 7
function task7() {
    let n = prompt("Введите значение n: ", "1984")
    const animals = ["Крыса", "Корова", "Тигр", "Заяц", "Дракон", "Змея", "Лошадь", "Овца", "Обезьяна", "Петух", "Собака", "Свинья"];
    const colors = ["Зеленый", "Красный", "Желтый", "Белый", "Черный"];

    const startYear = 1984; // Год, с которого начинается цикл
    const animalIndex = (n - startYear) % 12;
    const colorIndex = Math.floor((n - startYear) / 2) % 5;

    const animalName = animals[animalIndex];
    const colorName = colors[colorIndex];

    alert(animalName + " " + colorName);
}

//задача 8
function task8() {
    let result = ""
    for (let i = 1; i <= 10; i++) {
        const x = 9 * i;
        result += `9 x ${i} = ${x}` + "\n";
    }
    alert(result);
}

//задача 9 
function task9() {
    let result = '';
    for (let i = 2; i <= 20; i++) {
        result += Math.sin(i) + '\n';
    }
    alert(result);
}

//задача 10
function task10() {
    let result = "";
    let a = parseInt(prompt("Введите число а: ", "100"));
    let b = parseInt(prompt("Введите число b: ", "500"));
    let sum = 0;
    for (let i = 100; i <= 500; i++) {
        sum += i;
    }
    result += "а)" + sum + "\n";
    sum = 0

    for (let i = a; i <= 500; i++) {
        sum += i;
    }
    result += "б)" + sum + "\n";
    sum = 0

    for (let i = -10; i <= b; i++) {
        sum += i;
    }
    result += "в)" + sum + "\n";
    sum = 0

    for (let i = a; i <= b; i++) {
        sum += i;
    }
    result += "г)" + sum + "\n";
    alert(result);
}

//задача 11
function task11() {
    const n = parseInt(prompt("Введите значение n:", "10"));

    if (isNaN(n) || n <= 0) {
        alert("Пожалуйста, введите положительное число.");
        return;
    }

    let sum = 0;
    for (let i = 1; i <= n; i++) {
        sum += 1 / i;
    }

    alert("Сумма ряда: " + sum);
}

//задача 12 - повторное сложение
function task12v1() {
    let x = parseInt(prompt("Введите число x: ", "5"));
    let y = parseInt(prompt("Введите число y: ", "4"));
    let result = 0;
    if (x === 0 || y === 0) {
        result = 0;
    }

    for (let i = 0; i < y; i++) {
        result += x;
    }

    alert(x + "*" + y + "=" + result)
}

//задача 12 - метод рекурсии
function task12v2r(x, y) {
    if (x === 0 || y === 0) {
        return 0;
    }

    if (y === 1) {
        return x;
    }
    return x + task12v2r(x, y - 1);
}

function task12v2() {
    let x = parseInt(prompt("Введите число x: ", "5"));
    let y = parseInt(prompt("Введите число y: ", "4"));
    if (isNaN(x) || isNaN(y) || x < 1 || y < 1) {
        alert("Введите натуральные числа:");
        return;
    }
    const result = task12v2r(x, y);
    alert(x + "*" + y + "=" + result)
}

//задача 13
function task13() {
    const n = parseInt(prompt("Введите число n:", "4"));
    if (isNaN(n) || n <= 0) {
        alert("Введите положительное натуральное число");
        return;
    }

    let square = 0;
    for (let i = 1; i <= n; i++) {
        square += 2 * i - 1;
    }
    alert("Квадрат числа: " + n + " равен: " + square);
}

//задача 14
function task14r(n) {
    if (n <= 0) {
      return 0;
    }
  
    if (n === 1) {
      return Math.sqrt(1);
    }
  
    return Math.sqrt(n + task14r(n - 1));
  }
  
  function task14() {
    const n = parseInt(prompt("Введите значение n (не более 50):"));
    if (isNaN(n) || n < 1 || n > 50) {
      alert("введите натуральное число от 1 до 50.");
      return;
    }
    const result = task14r(n);
    alert("Сумма Sqrt(1 + Sqrt(2 + Sqrt(3 + ... + Sqrt(n))) = " + result);
  }
  
  // Задача 15
 function task15() {
    let sum = 0;
    let count = 0;
  
    while (true) {
      const number = parseInt(prompt("Введите число (0 для завершения):"));
      if (number === 0) break;
      sum += number;
      count++;
    }

    alert("a)Сумма чисел:" + sum +"\n"+ "б)Количество чисел: " + count);
  }
  
  // Задача 16
  function task16() {
    let sum = 0;
    let count = 0;
  
    while (true) {
      const number = parseInt(prompt("Введите неотрицательное число (отрицательное для завершения):"));
      if (number < 0) break; 
      sum += number;
      count++;
    }
    if (count > 0) {
      const average = sum / count;
      alert("Среднее арифметическое: " + average);
    } else {
      alert("Последовательность не содержит неотрицательных чисел");
    }
  }
  
  // Задача 17
  function task17() {
    const number = parseInt(prompt("Введите натуральное число:"));
    const numberStr = number.toString();
    const lastDigit = number % 10;
    let a = 0;
    let b= 0;
    let v = 0;
    let g = 0;
    let d = 1;
    let e = 0;
  
    for (let i = 0; i < numberStr.length; i++) {
      const digit = parseInt(numberStr[i]);
      
      if (digit === 3) a++;
      if (digit === lastDigit) b++;
      if (digit % 2 === 0) v++;
      if (digit > 5) g += digit;
      if (digit > 7) d *= digit;
      if (digit === 0 || digit === 5) e++;
    }
    let result = "";
    result += "а)Количество цифр 3: " + a + '\n';
    result += "б) Количество раз, когда последняя цифра встречается: " + b + '\n';
    result += "в) Количество четных цифр: " + v + '\n';
    result += "г) Сумма цифр, больших 5: " + g + '\n';
    result += "д) Произведение цифр, больших 7: " + d + '\n';
    result += "е) Количество цифр 0 и 5: " + e + '\n';   
    alert(result);
  }

  // Задача 18
function task18() {
    const number = parseInt(prompt("Введите натуральное число, в котором все цифры различны:"));
    const numberStr = number.toString();
    const digits = numberStr.split('').map(Number);
    
    const maxDigit = Math.max(...digits);
    const minDigit = Math.min(...digits);
    
    const maxIndexFromEnd = numberStr.length - digits.indexOf(maxDigit);
    const maxIndexFromStart = digits.indexOf(maxDigit) + 1;
    const minIndexFromEnd = numberStr.length - digits.indexOf(minDigit);
    const minIndexFromStart = digits.indexOf(minDigit) + 1;
    
    alert("а)Порядковый номер максимальной цифры (с конца)" + maxIndexFromEnd + "\n" +"б)Порядковый номер минимальной цифры (с начала): " + minIndexFromStart);
  }
  
  // Задача 19
  function task19() {
    const number = parseInt(prompt("Введите натуральное число больше 1:"));
    let isPrime = true;
    
    if (number <= 1) {
      isPrime = false;
    } else {
      for (let i = 2; i < number; i++) {
        if (number % i === 0) {
          isPrime = false;
          break;
        }
      }
    }

    if (isPrime) {
      alert("Число является простым.");
    } else {
      alert("Число не является простым.");
    }
  }
  
  // Задача 20
  function task20() {
    const number = parseInt(prompt("Введите натуральное число:"));
    const numberStr = number.toString();
    
    let isOrdered = true;
    
    for (let i = 0; i < numberStr.length - 1; i++) {
      if (numberStr[i] > numberStr[i + 1]) {
        isOrdered = false;
        break;
      }
    }
    
    if (isOrdered) {
      alert("Цифры в числе упорядочены по возрастанию.");
    } else {
      alert("Цифры в числе не упорядочены по возрастанию.");
    }
  }
  
  // Задача 21
  function task21() {
    const n = parseInt(prompt("Введите число n:"));
    let number;
    let index = 0;
    
    do {
      number = parseInt(prompt("Введите следующее число (окончание - 10000):"));
      index++;
    } while (number !== 10000 && number <= n);
    
    if (number === 10000) {
      alert("В последовательности нет чисел, больших заданного n.");
    } else {
      alert("Порядковый номер первого числа, большего " + n +  ", составляет: " + index);
    }
  }
  
  // Задача 22
  function task22() {
    const number = parseInt(prompt("Введите натуральное число:"));
    const numberStr = number.toString();
    const a = parseInt(prompt("Введите цифру a:"));
    const b = parseInt(prompt("Введите цифру b:"));
    
    let countA = 0;
    let countB = 0;
    
    for (let i = 0; i < numberStr.length; i++) {
      const digit = parseInt(numberStr[i]);
      if (digit === a) {
        countA++;
      }
      if (digit === b) {
        countB++;
      }
    }
    
    if (countA < countB) {
      alert(`Цифра ${a} встречается реже, чем цифра ${b}.`);
    } else {
      alert(`Цифра ${a} встречается не реже, чем цифра ${b}.`);
    }
  }
  
  // Задача 23
  function task23v1() {
    let number = 10;
    
    while (number <= 30) {
      alert(number);
      number++;
    }
  }
  
  // Задача 23
  function task23v2() {
    let number = 10;
    
    do {
      alert(number);
      number++;
    } while (number <= 30);
  }
  
```

<h2>Запуска веб-страницы с использованием Node.js и фреймворка Express</h2>
1.Установить node.js<br>
2.Создать папку проекта, и выполнить команду npm install express, для создания package.json<br>
3.Создать файл server.js и прописать в нём минимальный сервер для запуска страницы по адресу http://localhost:3000 и дальнейшее выполнее всех файлов в корне проекта(например index.html и script.js)<br>

```js
const express = require('express');
const app = express();
const port = 3000;

//обслуживать все файлы из корня проекта, включая index.html, server.js и другие статические файлы.
app.use(express.static(__dirname)); 

// Запуск сервера
//app.listen(port, callback) - метод используется для запуска HTTP-сервера на указанном порту
app.listen(port, () => {
  console.log(`Сервер запущен на порту ${port}`);
});

```

<h2>Вывод</h2>
Я научился создавать веб-сервер с помощью Node.js и Express, изучил возможности функции, класса, циклов, операторов, встроенных функций, операторов прерывания и условий в языке JS


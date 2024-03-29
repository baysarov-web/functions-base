# Задачи по основам функций

Выполни следующие задания в файле `functions.js`.

⚠️ Во время выполнения весь код пиши от руки, без копипаста!

Для каждой строки обязательно прописывай комментарий о том, что эта строка делает.

**Задача 1**. Создай функции с именами:
- `removeUser`;
- `createPost`;
- `addItem`;
- `readFile`;
- `getElements`;
- `createParentElement`;
- `startGame`;
- `sendMessage`;

Сразу после создания каждую из функций нужно вызвать.

**Задача 2**. Создай десять функций с любыми названиями (более или менее логичными).
Каждая из созданных функций должна принимать по одному параметру.
Выводить что-то или возвращать из функции не нужно.
   
**Задача 3**. Создай еще 10 функций с любыми названиями. Каждая из функций должна получать параметр и просто возвращать его. Давай этим функциям и их параметрам правдоподобные названия.

**Задача 4**. Создай пять разных функций, каждая из которых принимает один параметр. Затем функция должна вернуть значение этого параметра, умноженное на два. Выведи результат работы функции в консоль.

**Задача 5**. Создай функцию, которая принимает в качестве параметра массив и возвращает первый элемент этого массива. Вызови функцию в консоль.

**Задача 6**. Создай функцию, которая принимает в качестве параметра массив и возвращает последний элемент этого массива. Вызови функцию в консоль.

**Задача 7**. Добавь комментарии к каждой строке следующего кода:

```
function printMyFullName(firstname, secondname) {
  const fullname = `${firstname} ${secondname}`;
  
  return fullname;
}

console.log(printMyFullName('into', 'code'));


function getSumOfFirstAndLastElement(arr) {
  if(arr.length < 2) {
    return 'леее, минимум два элемента нужно жи есть';
  } else {
    const lastIndex = arr.length - 1;
    
    return arr[0] + arr[lastIndex];
  }
}

console.log(getSumOfFirstAndLastElement([]);

console.log(getSumOfFirstAndLastElement([3, 7, 12, 8]);
```

**Задача 8**. Напиши к следующему коду комментарий, объясняющий почему функция возвращает "html" вместо "css".

```
let text = "css";

function testVariableScope() {
  let text = "html";
  
  return text;
}

console.log(testVariableScope());
```

**Задача 9**: Погугли и узнай почему следующий код выполняется несмотря на то, что функция объявлена после того, как используется (то есть вызывается).

```
console.log(addToNumbers(4, 8))

function addToNumbers(x, y) {
  return x + y;
}
```

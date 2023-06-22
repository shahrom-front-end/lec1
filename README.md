# lec1

# JavaScript — популярное программирование язык, имеющий широкий спектр Приложения.

## Brendan Eich (создатель языка JavaScript) между делом пишет о том, как язык создавался, и почему он такой, какой есть. JS был обязан «выглядеть как Java», только поменьше, быть эдаким младшим братом-тупицей для Java. Кроме того, он должен был быть написан за 10 дней, а иначе мы бы имели что-то похуже JS.

### В Javascript есть два типа инициализирующих переменных: var и let. Вы можете использовать оба из них.Однако между ними есть некоторые различия.В программировании переменная — это контейнер (область хранения) для хранения данных.Если вы уверены, что значение переменной не изменится на протяжении всей программы, рекомендуется использовать константу.

# OBJECTS AND PRIMITIVES


#  PRIMITIVES
## 1.Number
## 2.String
## 3.Boolean
## 4.Undefined
## 5.Null
## 6.Symbol
## 7.Bigint

## 8.OBJECTS 


# LOGICal OPERATORS
## В JavaScript есть четыре логических оператора: || (ИЛИ), && (И) и ! (НЕ), ?? (Оператор нулевого слияния). Здесь мы рассмотрим первые три, оператор ?? будет в следующей статье.Несмотря на своё название, данные операторы могут применяться к значениям любых типов. Полученные результаты также могут иметь различный тип

# CONDITION If/else Statement
```js
    let number = -2
    if (number>0) {
        console.log(number);
    }
    else{
        console.log(12);
    }
```    

### Оператор switch оценивает выражение, соответствующее значение выражения против серии пунктов case и выполняетзаявления после первого случая предложение с соответствующим значением,пока оператор break не будетстолкнулся. Предложение по умолчаниюоператора switch будетперешел к, если ни один регистр не соответствует  значение выражения

# for
```js
    let sum= " "
    let cnt=0
    for(let i=1;i<=9;i++){
        sum=sum+i
        cnt+=i
    }
    console.log(sum);
    // 0123456789
    console.log(cnt);
    // 45
```
# while
```js
    let n = 0
    let x = 0
    while (n < 3) {
        n++
        x += n
    }
    console.log(n);
    // 3
    console.log(x);
    // 6
```

# Do/whil
```js
    let result=''
    let i=0
    do{
        i=i+1
        result=result+i
    }while(i<5)
    console.log(result);
    // 12345
```

# functions Javascript
# 1 Function declaration
# 2 Funtion Expression
# 3 Immediately Invoked Function Expression(IIFE)

# 1 Function declaration
```js
    function get(num1,num2){
        return num1+num2
    }
    console.log(get(3,5));
    // 8
```

## Функциональное выражение очень похож на и имеет почти тот же синтаксис, что и у функции декларация.Основное отличие афункциональное выражение и объявление функции имя функции, которое может быть опущен в функциональных выраженияхсоздавать анонимные и стрелочные функции

# 1 fuction anonymous
```js
    let anonymous=function(num1){
        return num1
    }
    console.log(anonymous("Umed"));
    // Umed
```

# 2 fucntion arrow
```js
    let arrow=(num1)=>{
        return num1
    }
    console.log(arrow("Navruz"));
    // Navruz
```

# 3 Function (Immediately Invoked Function Expression)IIFE

```js
var name = 'Navruz';
(function(){
    var name = 'Umed'
    console.log(name);
})()
console.log(name);
// Navruz
```
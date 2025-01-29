# Подготовка к собеседованию

## Содержание

### Ручное тестирование.

1. QA QC Тестирование 
2. Что такое тестирование
3. Принципы тестирования
4. Цели тестирования
5. Виды тестирования (функциональные/нефункциональные/ по изменениям, по подходам)
6. Уровни тестирования. Пирамида тестирования
7. Отличие чек-листа от тест-кейса (правила написания)
8. Баг репорт
9. Методологии аджайл и скрам 
10. Виды требований 
11. Характеристик требований
12. Техники тест-дизайна (черный ящик)
13. Апи (Rest/SOAP)
14. Принципы REST
15. SQL (команды для выборки данных ), какие бывают БД И СУБД
16. Монолит / микросераис, двухзвенная и многозаенная архитектура
17. Мобилки: ANR , Жизненный цикл активности, разница в подходах в тестировании, прерывания , эмуляторы, симуляторы
18. Веб: инструмент девтулс, разница в походных в тестировании
19. Командные строки винды и линукс, основные команды, разница ОС
20. Десктоп: разница в тестировании десктоп прил

### Автоматизированное тестирование

#### Основы Java
1. [ссылка](#auto-1) Что такое Java?
2. Что такое JVM и JRE, JDK? В чём разница между ними?
3. Что такое класс и объект в Java? Приведите примеры.
4. Как создать класс в Java и как создать объект класса?
5. Какие типы переменных существуют в Java?
6. Как выделяется память для разных типов переменных?
7. Модификаторы доступа к классам/ методам/ переменным
8. Final, finally и finalize()
9. Что такое метод в Java? Как его создать?
10. Что такое массив в Java? Какие виды массивов бывают?
11. Что такое цикл в Java? Назовите виды циклов.
12. Что такое оператор if-else в Java? Для чего он используется?
13. Что такое наследование в Java? Объясните на примере.
14. Что такое полиморфизм в Java? Поясните на примере.
15. Статический и динамический полиморфизм
16. Что такое инкапсуляция в Java? Приведите пример.
17. Что такое Абстракция в Java? Приведите примеры ее реализации
18. Класс Object, какие методы есть?
19. Метод equals и hashCode?

#### Коллекции

20. Что такое коллекции в Java?
21. Какие виды коллекций существуют в Java и чем они отличаются друг от друга?
22. Как создать коллекцию в Java? Приведите примеры.
23. В чём разница между списком (List), множеством (Set) и картой (Map)?
24. Что такое ArrayList и LinkedList? В каких случаях следует использовать каждый из них?
25. Что такое HashSet и TreeSet? В чём их отличие?
26. Что такое HashMap и TreeMap? В чём их различие?
27. Что такое итератор в Java и как его использовать?
28. Что такое сортировка в коллекциях и какие методы сортировки существуют?

#### Компараторы

29. Что такое компаратор (comparator) в Java?
30. В чём разница между использованием метода compareTo и реализацией интерфейса Comparator?
31. Как реализовать интерфейс Comparator для сравнения объектов определённого класса?
32. Какие методы есть у интерфейса Comparator и как они используются?
33. Можно ли использовать один и тот же компаратор для разных классов?
34. Может ли компаратор быть статическим методом?
35. Может ли класс реализовать более одного компаратора?

#### Исключения

36. Что такое исключение (exception) в Java?
37. Какие виды исключений существуют в Java и чем они отличаются друг от друга?
38. Как создать собственное исключение в Java? Приведите примеры.
39. В чём разница между проверяемыми (checked) и непроверяемыми (unchecked) исключениями?
40. Как обработать исключение в коде? Приведите пример.
41. Что такое try-catch-finally блок и как он работает?
42. Может ли быть несколько блоков catch для одного try блока?
43. Можно ли использовать несколько исключений в одном блоке catch?
44. Что такое иерархия исключений и как она связана с обработкой исключений?

#### Дженерики 

45. Что такое дженерики (generics) в Java?
46. Какие преимущества дают дженерики при разработке программ?
47. Как создать класс с использованием дженериков? Приведите примеры.
48. В чём разница между сырыми типами (raw types) и обобщёнными типами (generic types)?
49. Что такое подстановочные типы (wildcards) и как они используются?
50. Может ли класс иметь несколько параметров типа?
51. Можно ли создавать массивы с использованием дженериков?
52. Могут ли дженерики использоваться с примитивными типами данных?
53. Что такое стирание типов (type erasure) и как оно влияет на использование дженериков во время выполнения программы?
54. Какие ограничения накладываются на использование обобщённых методов и классов?

#### Инструменты тестирования 

55. Сборщики проектов, какие знаете?
56. Maven - какие фазы
57. Gradle - какие таски
58. Как подключать зависимости в проект
59. Назовите основные библиотеки для тестирования на Java.
60. RestAssured, Selenium, JBDC
61. Библиотека Selenium - из каких компонентов стоит?
62. Как работать с webdriver
63. Как можно обращаться к элементам в Selenium
64. RestAssured - для чего предназначена, как настроить спецификации запросов и ответов?
65. Что такое Pojo?
66. Как сокращать код в использовании классов оболочек? (Lombok - его аннотации)
67. Какая констуркция используется для формирования запросов? (given - when - then)
68. Какая часть конструкции не обзятельна (then)
69. Библиотека для формирования отчетов Allure
70. Какие аннотации алюр вы знаете?
71. JBDC
72. Как формировать запросы в JBDC?
73. В чём разница между JUnit, TestNG и другими библиотеками для тестирования? (это фреймворки)
74. Как настроить и запустить тест с использованием JUnit или другой библиотеки?
75. Что такое аннотации @Test, @Before, @After и как они используются?
76. Параметризованные тесты как использовать? (@DataProvider)

## Ручное тестирование
## Автоматизированное тестирование

### <span id="auto_1"> 1. Что такое Java? </span>

**Java** - высокоуровневый (не нужно работать с памятью и процессами напрямую) язык программирования, построенный на основе парадигмы ООП (объектно-ориентированное программирование). 

#### Где используется

Чаще всего java используется для мобильной разработки (часто используют и kotlin вместо него), разработки десктопных, серверных приложений и микросервисов, в Enterprise разработке (сложных больших программ для удовлетворения бизнес-потребностей). Ну и для тестирования.

#### Платформы

При разработке необходимо выбрать пакет (платформу). В Java доступны следующие платформы: *Java Enterprise Edition* (Java EE) (для Enterprise), *Java Standard Edition* (Java SE) (для общего назначения) и *Java Mobile Edition* (Java ME) (для мобилок).
___
### 2. Что такое JVM и JRE, JDK? В чём разница между ними?

#### JVM

**JVM** (Java Virtual Machine) - платформа на которой запускаются java программы. Она управляет и оптимизирует память, используемую приложением. Также включает в себя сборщик мусора (очищает из памяти элементы, к которым нет доступа в программе), загрузчик классов (загружает классы в контекст). Также отвечает за распределение и поддержание ссылочной структуры. 
По сути JVM это платформа, с помощью которой обеспечивается кроссплатформенность программ на Java. Независимо от ОС и аппаратной платформы java-программы будут работать одинаково благодаря JVM.

#### JDK

**JDK** (Java Development Kit) представляет собой пакет инструментов для _разработки_ программного обеспечения. Это программный пакет, который вы загружаете для создания Java-приложений. Включает в себя компилятор и стандартные библиотеки классов.  

#### JRE
**JRE** (среда выполнения Java) представляет собой пакет инструментов для _запуска_ Java-кода. JRE может использоваться, как отдельный компонент для простого запуска Java-программ, либо быть частью JDK.  JRE содержит библиотеки классов, загрузчик классов и виртуальную машину Java. 
По сути JRE является контейнером для компонентов и отвечает за организацию их деятельности. Она берет Java-код, объединяет его с необходимыми библиотеками и запускает JVM для его выполнения. 
___

### 3. Что такое класс и объект в Java? Приведите примеры.

Java - объектно-ориентированный язык программирования. Это значит, что программы на Java построены вокруг классов и объектов. 

**Класс** — это шаблон для создания объектов, которые представляют собой некоторую сущность в рамках системы. Классы содержат состояние (данные) в виде полей и поведение в виде [[Подготовка к собеседованию#9. Что такое метод в Java? Как его создать?|методов]].

**Объект** (экземпляр класса) - это конкретная реализация класса (то есть по сути шаблона), которая занимает память и имеет своё состояние (значения полей). 

Примеры: 
+ Класс автомобиль. Он будет содержать поля для хранения информации о марке, цвете и других характеристиках автомобиля, а также методы для взаимодействия с ним. Таким образом  создаётся шаблон для создания объектов, которые являются абстрактным представлением сущности автомобиля в программе. Сами экземпляры будут конкретными реализациями этого класса со своим состоянием. 
+ Класс человек. Будет содержать имя, пол, возраст и т.д. По аналогии с автомобилем представляет шаблон для реализации конкретных представлений сущности в программе.

___

### 4. Как создать класс в Java и как создать объект класса?

Для создания класса используется ключевое слово `Class`. Внутри фигурных скобок определяются поля и [[Подготовка к собеседованию#9. Что такое метод в Java? Как его создать?|методы]] этого класса, в том числе и конструктор, который является методом для инициализации данных экземпляра класса. 


> Если мы не задаём конструктор, то неявно создаётся конструктор по умолчанию без параметров. Конструкторов может быть несколько и они могут вызывать друг друга.


Продолжая пример с автомобилем:

```Java
public class Car {
    // Поля 
    String brand; // марка автомобиля
    String color; // цвет
    int speed;    // текущая скорость

    // Конструктор (для создания объекта)
    public Car(String brand, String color) {
        this.brand = brand;
        this.color = color;
        this.speed = 0; // начальная скорость
    }

    // Методы (действия)
    public void accelerate(int increment) {
        speed += increment; // увеличиваем скорость
    }

    public void brake(int decrement) {
        speed -= decrement; // уменьшаем скорость
    }

    public void displayInfo() {
        System.out.println("Brand: " + brand + ", Color: " + color + ", Speed: " + speed + " km/h");
    }
}
```

Для создания объекта необходимо вызвать его конструктор с помощью оператора `new` (оператор `new` выделяет память под объект):
```java
public class Main {
    public static void main(String[] args) {
        // Создаём объект класса Car
        Car myCar = new Car("Toyota", "Red");
	}
}
```
___
### 5. Какие типы переменных существуют в Java?

Java - статически типизированный язык программирования. Это значит, что для каждой переменной тип жёстко фиксируется и задаётся один раз при объявлении. Поэтому тип нужно всегда указывать. (В питоне, например, можно написать a = 5, а потом a = "Привет". Тут так нельзя) 

```
Ключевое слово var просто определяет тип данных по значению. Поэтому статическая типизация не нарушается.
```

#### Примитивы

В Java существует 8 примитивных типов данных:
1. `byte` - содержит целые числа (от -128 до 127). Занимает 1 байт в памяти. (Используется для оптимизации памяти, когда не нужно использовать большие числа)
2. `short` - содержит целые числа. Занимает 2 байта в памяти. (Используется для оптимизации памяти, когда не нужно использовать большие числа)
3. `int` - содержит целые числа. Занимает 4 байта в памяти. (Чаще всего используется для целых чисел)
4. `long` - содержит целые числа. Занимает 8 байт в памяти. (Используется, когда не хватает размеров `int`)
5. `float` - содержит числа с плавающей точкой (дробные числа). Занимает 4 байта в памяти. (Используется для оптимизации памяти, когда не нужно использовать большие числа или числа где много знаков после запятой)
6. `double` - содержит числа с плавающей точкой (дробные числа). Занимает 8 байт в памяти. (Чаще всего используется для чисел с плавающей точкой)
7. `char` -  содержит один строчный символ в кодировке UTF-16. Занимает 2 байта в памяти. (Задаётся печатным символом в одинарных кавычках или числом, соответствующим номеру символа в таблице кодировки)
8. `boolean` - содержит логическое значение *true* либо *false*. Занимает 1 байт в памяти.

Все остальные типы, в том числе `String` - являются ссылочными.

```
Для примитивов есть специальные классы-оболочки Integet, Float, Double и т.д. С помщью которых примитив можно создать как ссылочный объект. Например, это нужно в дженериках, т.к. они работают только с ссылочными типами.
```

#### Преобразования примитивных типов

Примитивные типы без потери данных можно преобразовывать только если это расширяющее преобразования. То есть тип которому нужно меньше памяти преобразуется в тип которому нужно больше памяти. (Маленький горшок можно положить в большой, а вот в большой в маленький не залезет, хотя есть и другая интерпретация... Осёл из Шрека может создать дракосликов, а вот если были бы дракон и ослица...).

Расширяющее преобразование называется неявным и происходит автоматически без потери точности:
```java
byte a = 0;
int b = a; // 0
```

В обратном случае используется явное преобразования с указанием типа:
```java
int a = 128;
byte b = (byte)a; // 0
```

При этом если данные "не помещаются" в переменную, то происходит потеря данных (старшие биты в двоичном представлении обрезаются).

___

### 6. Как выделяется память для разных типов переменных?

Отличие ссылочных типов от примитивов в том, что примитивы хранят своё значение в области памяти, называемой *стеком*. А ссылочные типы хранят свои значения в области памяти называемой *кучей* (heap). В стеке лишь создаётся ссылка на расположение этих значений в куче. Поэтому мы можем присвоить разным переменным (ссылкам на объект) одни и те же данные из памяти. Это происходит в том числе когда мы передаём объекты в методы (приравниваем локальной переменной метода ссылку на данные в куче). Поэтому есть такие приколы:

```java
public class Main {
    public static void main(String[] args) {
        Car myCar = new Car("Toyota", "Red"); // получили ссылку на // данные в куче
        Car myCar2 = myCar; // ссылается на те же данные
        myCar2.color = "Blue"; // изменили сами данные
        System.out.println(myCar.color); // Blue
	}
}
```

```
Со строками отдельная тема. Они хранятся в куче в специальной области String pool. Если не вдваваться в подробности, то там возможны свои приколы. Поэтому, например, строки всегда нужно сравнивать через equals  
```

___
### 7. Модификаторы доступа к классам/ методам/ переменным

В Java есть 4 **модификатора доступа**:
+ `public` - доступ к элементам в любом месте программы. В других классах пакетах и т.д.
+ `private` - доступ к элементам только внутри данного класса.
+ `protected` - доступ к элементам в самом классе, в пакете и в [[Подготовка к собеседованию#13. Что такое наследование в Java? Объясните на примере.|цепочке наследования.]]
+ `default` - когда не указывается никакого ключевого слова. Доступ к элементам в рамках пакета. (отличается от `protected` тем, что если класс-наследник будет в другом пакете, то он доступ к элементу не получит)

Модификаторы доступа обеспечивают принцип ООП - [[Подготовка к собеседованию#Что такое инкапсуляция в Java? Приведите пример.|инкапсуляцию]]. 

___
### 8. Final, finally и finalize()

#### final

`final` - ключевое слово, у которого несколько назначений:
+ Задаёт константу. При этом значение переменной  должно задаваться сразу (или в конструкторе если это поле класса) и не может изменяться:
```java
final int a = 5;
a = 4; // ошибка
final int b; // тоже ошибка, нужно указать значение
```
+ Запрещает [[Подготовка к собеседованию#13. Что такое наследование в Java? Объясните на примере.|наследование классов]]. Ставится перед ключевым словом `class`
+ Запрещает [[Подготовка к собеседованию#Динамический полиморфизм|переопределение методов]]. Ставится в объявлении метода.

#### finally
**`finally`** используется в конструкции [[|try-catch-finally]] для выполнения кода, который должен быть выполнен вне зависимости от того, произошло исключение или нет (и даже после `return`). Блок `finally` гарантирует, что определённый код будет выполнен не зависимо от того, произошло ли исключение и было ли оно обработано. Важно использовать когда, например, нужно закрыть какие-то потоки или просто нужно залоггировать и т.п.

#### finalize()
Метод **`finalize()`** в Java — это метод класса [[|Object]], который может быть переопределён. Он вызывается перед тем, как объект будет удалён сборщиком мусора (когда объект в куче лежит, а ссылки в стеке на него нет). Однако его использование не рекомендуется, так как он имеет ряд серьёзных недостатков и не гарантирует своевременного выполнения.

___
### 9. Что такое метод в Java? Как его создать?

**Метод** в Java — это именованный блок кода, который выполняет определённую задачу. Методы используются для организации кода программы и для повторного использования кода. Они могут принимать входные параметры и возвращать значение (но это необязательно).

Создание метода:
<модификатор доступа> <тип\_возвращаемого\_значения> <имя\_метода>(<параметры>) { 
	// Тело метода 
}

Примеры:
```java
public void sayHello() { 
	System.out.println("Привет, мир!"); 
}

public int sum(int a, int b) {
	return a + b; 
}
```

Вызов:
```java
object.sayHello();
int sum = object.sum(2, 3);
```
Оператор `return` возвращает значение указанного типа из метода. Если тип `void` то оператор просто выходит из метода.

#### Методы с переменным числом параметров
В Java можно создавать методы с переменным числом параметров:

```java
static void sum(int ...nums){
    int result = 0;
    for(int n: nums)
		result += n;
	    System.out.println(result);
    }
}

sum(2, 3, 5, 7); // 7
sum(2, 2); // 4
```

Все передаваемые данные засовываются в [[Подготовка к собеседованию#10. Что такое массив в Java? Какие виды массивов бывают?|массив]]. 

`static` обозначает, что метод вызывается на уровне класса, а не конкретного объекта. То есть не нужно создавать объект, чтобы использовать метод. Статический метод вызывается по имени класса и не может получить доступ к нестатическим полям объекта (логично, он не знает о каком конкретно объекте идёт речь). Пример вызова статического метода: `Math.max()`;

___ 
### 10. Что такое массив в Java? Какие виды массивов бывают?

**Массив** в Java — это структура данных, которая позволяет хранить набор значений одного типа. Массивы в Java имеют фиксированный размер, который задаётся при создании. Массивы не имеют встроенных методов добавления/удаления элементов.

Примеры создания массивов:
```java
int[] array = new int[4]; // одномерный
int arr[] = {1, 2, 3, 4}; // одномерный
int[][] matrix = new int[3][3]; // двумерный
int[][] mat = {{1, 2, 3}; {4, 5, 6}; {7, 8, 9}}; // двумерный
int[][] zub = new int[2][]; // зубчатый
```

Доступ к элементам массива осуществляется с помощью индекса, начиная с 0. Например, `arr[0]`. Для получения количества элементов в массиве используется поле `length`. Например, `arr.length`;

```
После объявления массива, если мы явно не задаём значения в нём с помощью {}, то в нём хранятся дефолтные значения для типа данных элементов массива. Для целочисленных типов это 0, для чисел с плавающей точкой 0.0, для char - нулевой символ, для boolean - false, а для ссылочных типов - null
```

#### Виды массивов
+ Одномерные массивы - набор элементов одного типа, выстроенных в ряд.
+ Многомерные массивы - массивы, содержащие несколько других массивов (или массивов массивов) одинаковой длинны. Как правило используются двумерные массивы. 
+ Зубчатые (нерегулярные, рваные) массивы - массив, в котором каждый элемент является массивом. При этом внутренние массивы могут иметь разную длину. 

___
### 11. Что такое цикл в Java? Назовите виды циклов.

**Цикл** в Java — это конструкция, которая позволяет многократно выполнять блок кода, пока выполняется определённое условие.

#### Виды циклов
+ `while` - используется, когда количество итераций (запусков тела цикла) заранее неизвестно, но зависит от выполнения условия. 
```java
int i = 0; 
while (i < 5) { 
	System.out.println("Итерация: " + i); 
	i++; 
}

// Часто можно встретить такую штуку:
while(true) { // бесконечный цикл
	i++;
	if(i > 100) {
		break; // выход из цикла 
	}
}
```
+ `do-while` - Используется, когда тело цикла должно быть выполнено *хотя бы один раз*, независимо от условия.
```java
int i = 0; 
do { 
	System.out.println("Итерация: " + i); 
	i++; 
} while (i > 5); // цикл запустится 1 раз
```
+ `for` - Используется, когда заранее известно количество итераций.
```java
for (int i = 0; i < 5; i++) { 
	System.out.println("Итерация: " + i); 
}

int i = 10;
for(;i<20;) { // каждый из составляющих цикла можно пропустить
	i++;
}
```
+ `for-each` - Применяется для перебора элементов [[Подготовка к собеседованию#10. Что такое массив в Java? Какие виды массивов бывают?|массивов]] или [[|коллекций]].
```java
int[] numbers = {1, 2, 3, 4, 5}; 
for (int num : numbers) { 
	System.out.println("Элемент: " + num); 
}
```

#### break и continue

`break` и `continue` - ключевые слова для управления ходом управления цикла.
+ `break` — завершает выполнение цикла, не выполняя до конца всё тело цикла.
+ `continue` — пропускает текущую итерацию и переходит к следующей, не выполняя до конца всё тело цикла.

___
### 12. Что такое оператор if-else в Java? Для чего он используется?

**Оператор `if-else`** в Java — это конструкция, которая позволяет выполнять разные блоки кода в зависимости от выполнения заданного условия.

Пример:
```java
if (age < 18 && age > 0) { 
	System.out.println("Доступ запрещён."); 
} else if(age < 100) { // если предыдущее условие не выполнилось 
	System.out.println("Доступ разрешён."); 
} else { //  если все предыдущие условия не выполнились
	System.out.println("Ошибка. Неправильный возраст"); 
}
```

Блоки `else-if` и `else` необязательные. Также можно вкладывать `if-else` друг в друга:
```java
if (number > 0) { 
	if (number % 2 == 0) { 
		System.out.println("Положительное чётное число."); 
	} else { 
		System.out.println("Положительное нечётное число."); 
	}
} else { 
	System.out.println("Число не положительное."); 
}
```

#### Тернарный оператор

Для простых проверок можно использовать тернарный оператор `? :`

```java
String access = (age >= 18) ? "Доступ разрешён" : "Доступ запрещён";
```

Если условие в скобках выполняется то возвращается значение после `?`, иначе - значение после `:`. То есть аналогично:
```java
String access;
if(age >= 18) {
	access = "Доступ разрешён";
} else {
	access = "Доступ запрещён";
}
```

___

### 13. Что такое наследование в Java? Объясните на примере.

**Наследование** — это один из принципов (парадигм) объектно-ориентированного программирования. Он позволяет создавать новый класс (называемый *производным*, *дочерним* или *подклассом*) на основе уже существующего класса (называемого _базовым_, _родительским_ или _суперклассом_).

Подкласс наследует поля (переменные) и методы родительского класса, а также может добавлять свои собственные или переопределять унаследованные методы.

Класс может наследоваться только от одного класса.

Пример.
Автомобиль является транспортом. Он обладает свойствами транспорта (марка, цвет, скорость и т.д.) и обладает таким же поведением (он может поехать куда-то, остановиться и т.п.). Однако у него может быть свои собственные уникальные свойства (количество дверей, тип двигателя и т.д.) и своё собственное поведение (прогреть движок, включить кондиционер и т.п.). В таком случае автомобиль как экземпляр класса *Car* будет наследовать данные и поведение класса *Vehicle*. Потому что сущность автомобиля более расширенное, дополненное представление сущности транспорта.

Реализация наследования:

```java
class Vehicle { 
	String brand; 
	int speed;
	 
	public Vehicle(String brand, int speed) { 
		this.brand = brand; 
		this.speed = speed; 
	} 
	
	public void displayInfo() { 
		System.out.println("Марка: " + brand);
		System.out.println("Скорость: " + speed + " км/ч"); 
	} 
}

class Car extends Vehicle { 
	int doors; 
	
	public Car(String brand, int speed, int doors) { 
		super(brand, speed); // Вызов конструктора базового класса
		this.doors = doors; 
	} 
}

public class Main { 
	public static void main(String[] args) { 
		// Создаём объект автомобиля 
		Car car = new Car("Toyota", 180, 4); 
		car.brand; // Наследуется от класса Vehicle
		car.speed; // Наследуется от класса Vehicle
		car.doorsl // Определено в классе Car
		car.displayInfo(); // Переопределено в классе Car
	}
}
```

Для того чтобы наследовать класс необходимо использовать ключевое слово `extends` в его объявлении. 
С помощью ключевого слова `super` можно обращаться к элементам родительского класса. В примере вызывается конструктор базового класса. При этом вызов конструктора базового класса должен идти в самом начале в конструкторе производного класса.

___

### 14. Что такое полиморфизм в Java? Поясните на примере.

**Полиморфизм** — это один из принципов (парадигм) объектно-ориентированного программирования. Он заключается в способности одного и того же метода или объекта работать по-разному в зависимости от того, с каким типом данных он используется. Это делает код более гибким, расширяемым и удобным для работы с иерархиями классов.

В качестве примера полиморфизма можно привести [[Подготовка к собеседованию#Динамический полиморфизм|переопределение метода]]. Переопределяя метод, мы изменяем его поведение в классе-потомке. Таким образом один и тот же метод ведёт себя по-разному в зависимости от того, объект какого класса его вызывает.
___
### 15. Статический и динамический полиморфизм

#### Статический полиморфизм

Статический полиморфизм определяется на этапе компиляции. К статическому полиморфизму относится **перегрузка методов**. 

**Перегрузка методов** (method overloading) в Java — это возможность создавать в одном классе несколько методов с одним и тем же именем, но с разными наборами параметров (типами, количеством, порядком), т.е. с разными сигнатурами методов.

Пример:
```java
public int add(int a, int b) { 
	return a + b; 
} 

public int add(int a, int b, int c) { 
	return a + b + c;
}
```

Java определяет, какой именно метод вызвать, на основе списка параметров (их типа, количества и порядка). Возвращаемый тип не участвует в сигнатуре метода.

Также к статическому полиморфизму относятся [[|шаблоны функций]]. (вроде как)
#### Динамический полиморфизм

Динамический полиморфизм определяется на этапе выполнения программы (в рантайме). К динамическому полиморфизму относится переопределение методов. 

**Переопределение методов** (Method Overriding) — это механизм, позволяющий подклассу предоставить свою реализацию метода, который уже определён в его родительском классе. Метод в подклассе должен иметь ту же сигнатуру, такой же или менее строгий модификатор доступа, тот же возвращаемый тип, как и у метода из родительского класса.

Также переопределяемый метод в классе-потомке помечается аннотацией \@Override. (Фактически, это необязательно, но так принято)

Пример:
```java
class Animal {
    // Метод в родительском классе
    public void sound() {
        System.out.println("Животное издаёт звук.");
    }
}

class Dog extends Animal {
    // Переопределение метода sound()
    @Override
    public void sound() {
        System.out.println("Собака лает: Гав-гав!");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal myAnimal = new Animal();
        Animal myDog = new Dog(); // Ссылка на Animal, но объект Dog

        myAnimal.sound(); // Животное издаёт звук.
        myDog.sound(); // Собака лает: Гав-гав!
    }
}
```

```
Переопределяемые методы из родительского класса часто называют виртуальными
```
___

### Что такое инкапсуляция в Java? Приведите пример.

**Инкапсуляция** — это один из принципов (парадигм) ООП, который заключается в скрытии деталей реализации и предоставлении доступа к данным только через определенные методы. Это также называют принципом чёрного ящика: мы запрашиваем какое-то поведение или информацию из класса и получаем результат, не взаимодействуя с конкретной реализацией поведения в классе.

Аналогия из реальной жизни (чисто для понимания теории): для того, чтобы заварить кофе с помощью автоматической кофемашины, необходимо взаимодействовать с её интерфейсом (выбрать режим, нажать кнопки и т.п.). При этом нам не нужно разбирать кофемашину и запускать её отдельные компоненты или что-то в ней шаманить. Это и есть принцип чёрного ящика - мы не знаем что происходит внутри кофемашины, поэтому она для нас как чёрный ящик.

В Java инкапсуляция реализуется с помощью [[Подготовка к собеседованию#7. Модификаторы доступа к классам/ методам/ переменным|модификаторов доступа]], *геттеров* и *сеттеров*. Мы должны правильно прописывать модификаторы доступа, чтобы у нас был доступ только к тому, что нам нужно для взаимодействия с объектом класса и не более.

#### Геттеры и сеттеры

**Геттеры** и **сеттеры** — это методы, которые позволяют получать и изменять значения приватных полей класса. 





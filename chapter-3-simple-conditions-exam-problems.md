# Глава 3. Прости проверки - изпитни задачи

## Цена за транспорт

Студент трябва да пропътува n километра. Той има избор измежду три вида транспорт:
Такси. Начална такса: 0.70 лв. Дневна тарифа: 0.79 лв. / км. Нощна тарифа: 0.90 лв. / км.
Автобус. Дневна / нощна тарифа: 0.09 лв. / км. Може да се използва за разстояния минимум 20 км.
Влак. Дневна / нощна тарифа: 0.06 лв. / км. Може да се използва за разстояния минимум 100 км.
Напишете програма, която въвежда броя километри n и период от деня (ден или нощ) и изчислява цената на най-евтиния транспорт.
//TODO: some words need to be bolded

TODO: картинка


### Входни данни

От конзолата се четат два реда:
Първият ред съдържа числото n – брой километри – цяло число в интервала [1…5000].
Вторият ред съдържа дума “day” или “night” – пътуване през деня или през нощта.
//TODO: some words need to be bolded and bullet menu


### Изходни данни

Да се отпечата на конзолата най-ниската цена за посочения брой километри.


### Примерен вход и изход
//TODO table


### Насоки и подсказки
//TODO


### Тестване в Judge системата
https://judge.softuni.bg/Contests/Practice/Index/169#1


## Тръби в басейн

Басейн с обем V има две тръби от които се пълни. Всяка тръба има определен дебит (литрите вода минаващи през една тръба за един час). Работникът пуска тръбите едновременно и излиза за N часа. Напишете програма, която изкарва състоянието на басейна, в момента, когато работникът се върне. 
//TODO: some words need to be bolded

TODO: картинка


### Входни данни

От конзолата се четат четири реда:
Първият ред съдържа числото V – Обем на басейна в литри – цяло число в интервала [1…10000].
Вторият ред съдържа числото P1 – дебит на първата тръба за час – цяло число в интервала [1…5000].
Третият ред съдържа числото P2 – дебит на втората тръба за час– цяло число в интервала [1…5000].
Четвъртият ред съдържа числото H – часовете които работникът отсъства – число с плаваща запетая в интервала [1.0…24.00].
//TODO: some words need to be bolded and bullet menu


### Изходни данни

Да се отпечата на конзолата едно от двете възможни състояния:
До колко се е запълнил басейна и коя тръба с колко процента е допринесла. Всички проценти се свеждат до цяло число (без закръгляне).
"The pool is [x]% full. Pipe 1: [y]%. Pipe 2: [z]%."
Aко басейнът се е препълнил – с колко литра е прелял за даденото време, число с плаваща запетая
"For [x] hours the pool overflows with [y] liters."
Имайте предвид, че поради свеждането до цяло число се губят данни и нормално сборът на процентите да е 99%, а не 100%.
// star, bolded words and bullet menu


### Примерен вход и изход
//TODO


### Насоки и подсказки



### Тестване в Judge системата
https://judge.softuni.bg/Contests/Compete/Index/179#1


## Поспаливата котка Том

Котката Том обича по цял ден да спи, за негово съжаление стопанинът му си играе с него винаги когато  има свободно време. За да се наспи добре, нормата за игра на Том е 30 000  минути в година. Времето за игра на Том зависи от почивните дни на стопанина му:
Когато е на работа, стопанинът му си играе с него по 63 минути на ден.
Когато почива, стопанинът му си играе с него  по 127 минути на ден.
Напишете програма, която въвежда броя почивни дни и отпечатва дали Том може да се наспи добре и колко е разликата от нормата за текущата година, като приемем че годината има 365 дни.
Пример: 20 почивни дни -> работните дни са 345 (365 – 20 = 245). Реалното време за игра е 24 275 минути (345 * 63 + 20 * 127).  Разликата от нормата е 5 725 минути (30 000 – 24 275 = 5 725) или 95 часа и 25 минути.
TODO: bullet menu and bolded words

TODO: картинка


### Входни данни

Входът се чете от конзолата и се състои от едно число – броят почивни дни – цяло число в интервала [0...365]
//TODO: bold


### Изходни данни

На конзолата трябва да се отпечатат два реда.
Ако времето за игра на Том е над нормата за текущата година:
На първия ред отпечатайте: “Tom will run away”
На втория ред отпечатайте разликата от нормата във формат:
“{H} hours and {M} minutes more for play”
Ако времето за игра на Том е под нормата за текущата година:
На първия ред отпечатайте: “Tom sleeps well”
 На втория ред отпечатайте разликата от нормата във формат:
“{H} hours and {M} minutes less for play”
//TODO: bullet and bold

### Примерен вход и изход

### Насоки и подсказки

### Тестване в Judge системата


## Реколта

От лозе с площ X квадратни метри се заделя 40% от реколтата за производство на вино. От 1 кв.м лозе се изкарват Y килограма грозде. За 1 литър вино са нужни 2,5 кг. грозде. Желаното количество вино за продан е Z литра.
Напишете програма, която пресмята колко вино може да се произведе и дали това количество е достатъчно. Ако е достатъчно, остатъкът се разделя по равно между работниците на лозето.
//TODO: woooords

TODO: картинка

### Входни данни

Входът се чете от конзолата и се състои от точно 4 реда:
1ви ред: X кв.м е лозето – цяло число в интервала [10 … 5000];
2ри ред: Y грозде за един кв.м – реално число в интервала [0.00 … 10.00];
3ти ред: Z нужни литри вино – цяло число в интервала [10 … 600];
4ти ред: брой работници – цяло число в интервала [1 … 20];


### Изходни данни

На конзолата трябва да се отпечата следното:
Ако произведеното вино е по-малко от нужното:
“It will be a tough winter! More {недостигащо вино} liters wine needed.”
Резултатът трябва да е закръглен към по-ниско цяло число
Ако произведеното вино е повече от нужното:
“Good harvest this year! Total wine: {общо вино} liters.”
Резултатът трябва да е закръглен към по-ниско цяло число
“{Оставащо вино} liters left -> {вино за 1 работник} liters per person.”
И двата резултата трябва да са закръглени към по-високото цяло число


### Примерен вход и изход

### Насоки и подсказки

### Тестване в Judge системата
https://judge.softuni.bg/Contests/Compete/Index/233#1 


## Фирма

Фирма получава заявка за изработването на проект, за който са необходими определен брой часове. Фирмата разполага с определен брой дни. През 10% от дните служителите са на обучение и не могат да работят по проекта. Един нормален работен ден във фирмата е 8 часа. Всеки служител може да работи по проекта в извънработно време по 2 часа на ден.
Часовете трябва да са закръглени към по-ниско цяло число (Например –> 6.98 часа се закръглят на 6 часа).
Напишете програма, която изчислява дали фирмата може да завърши проекта навреме и колко часа не достигат или остават.
//TODO: woooords

TODO: картинка

### Входни данни

Входът се чете от конзолата и съдържа точно 3 реда:
На първия ред са необходимите часовете – цяло число в интервала [0 ... 200 000]
На втория ред са дните, с които фирмата разполага – цяло число в интервала [0 ... 20 000]
На третия ред е броят на служителите, работещи извънредно – цяло число в интервала [0 ... 200]
//TODO: words and bullets


### Изходни данни

Да се отпечата на конзолата един ред:
Ако времето е достатъчно:
"Yes!{оставащите часове} hours left.”
Ако  времето НЕ Е достатъчно:
“Not enough time!{недостигащите часове} hours needed.“


### Примерен вход и изход

### Насоки и подсказки

### Тестване в Judge системата


# Завдання 3
## Кравченко Ярослав
### Загальне завдання
Як основа використовувати вихідний текст проекту попередньої роботи.
Забезпечити розміщення результатів обчислень у колекції з можливістю
збереження/відновлення.
Використовуючи шаблон проектування Factory Method (Virtual
Constructor), розробити ієрархію, що передбачає розширення за рахунок
додавання нових класів, що відображаються.
Розширити ієрархію інтерфейсом об'єктів, що "фабрикуються", що
представляють набір методів для відображення результатів обчислень.
Реалізувати ці методи виведення результатів у текстовому вигляді. Розробити
та реалізувати інтерфейс для "фабрикуючого" методу.
Забезпечити діалоговий інтерфейс із користувачем.
Розробити клас для тестування основної функціональності.
Використати коментарі для автоматичного створення документації
засобами javadoc.

#### Скріншоти завдання

AppMain - Головний клас, діалоговий інтерфейс

![Код](https://github.com/Yarickkk/zav3/blob/main/AppMain1.png)
![Код](https://github.com/Yarickkk/zav3/blob/main/AppMain2.png)
![Код](https://github.com/Yarickkk/zav3/blob/main/AppMain3.png)

CalculationData

![Код](https://github.com/Yarickkk/zav3/blob/main/SerD1.png)
![Код](https://github.com/Yarickkk/zav3/blob/main/SerD2.png)

CalculationHistory - клас для управління колекцією

![Код](https://github.com/Yarickkk/zav3/blob/main/CalHis1.png)
![Код](https://github.com/Yarickkk/zav3/blob/main/CalHis2.png)

ResultView - інтерфейс продукту

![Код](https://github.com/Yarickkk/zav3/blob/main/ResView1.png)

TextResultView - реалізація текстового відображення

![Код](https://github.com/Yarickkk/zav3/blob/main/TextRes1.png)

ViewFactory - інтерфейс

![Код](https://github.com/Yarickkk/zav3/blob/main/ViewFac1.png)

TextViewFactory - конкретна фабрика

![Код](https://github.com/Yarickkk/zav3/blob/main/TextView1.png)

FactoryPatternTest - клас тестування

![Код](https://github.com/Yarickkk/zav3/blob/main/FactoryPat1.png)

### Приклад роботи

![Приклад](https://github.com/Yarickkk/zav3/blob/main/priklad1.png)
![Приклад](https://github.com/Yarickkk/zav3/blob/main/priklad2.png)

Приклад роботи FactoryPetternTest

![Приклад](https://github.com/Yarickkk/zav3/blob/main/prikladtest1.png)

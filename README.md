1. За допомогою Visual Studio створіть проект за шаблоном Console Application.
Потрібно: Створити клас із ім'ям Rectangle.
У тілі класу створити два поля, що описують довжини сторін double side1, side2.
Створити власний конструктор Rectangle(double side1, double side2), в тілі якого поля side1 і side2 ініціалізуються значеннями аргументів.
Створити два методи, що обчислюють площу прямокутника - double AreaCalculator() та периметр. Прямокутник - double PerimeterCalculator().
Створити дві властивості double Area та double Perimeter з одним методом доступу get.
Написати програму, яка приймає від користувача довжини двох сторін прямокутника і виводить на екран периметр та площу.

2. За допомогою Visual Studio створіть проект за шаблоном Console Application.
Потрібно:
Створити клас Book. Створити класи Title, Author та Content, кожен з яких повинен містити одне рядкове поле та метод void Show().
Реалізуйте можливість додавання до книги назви книги, імені автора та змісту.
Виведіть на екран різними кольорами за допомогою методу Show() назву книги, ім'я автора та зміст.


3. За допомогою Visual Studio створіть проект за шаблоном Console Application.
Потрібно:
Створити класи Point та Figure.
Клас Point повинен містити два цілих поля і одне рядкове поле.
Створити три властивості одним методом доступу get.
Створити власний конструктор, у тілі якого проініціалізуйте поля значеннями аргументів. Клас Figure повинен містити конструктори, які приймають від 3 до 5 аргументів типу Point.
Створити два методи: double LengthSide(Point A, Point B), що розраховує довжину сторони багатокутника; void PerimeterCalculator(), що розраховує периметр багатокутника. Написати програму, яка виводить на екран назву та периметр багатокутника.

4. Створити клас Invoice.
У тілі класу створити три поля int account, string customer, string provider, які мають бути проініціалізовані один раз (при створенні екземпляра даного класу) без можливості їхньої подальшої зміни.
У тілі класу створити два закриті поля string article, int quantity
Створити метод розрахунку вартості замовлення з ПДВ та без ПДВ.
Написати програму, яка виводить на екран суму оплати замовленого товару із ПДВ або без ПДВ.
# Beginner Java Developer
Привет! 👋
Я начинающий Java-разработчик, изучающий и практикующий основы языка и технологии. В процессе обучения освоил ключевые концепции и инструменты, необходимые для дальнейшего роста в области Java-разработки.

<img src="https://img.icons8.com/?size=100&id=KnTSVNcE6p13&format=png&color=000000" alt="Java" width="40" height="40" style="vertical-align:middle;" /> <img src="https://img.icons8.com/?size=100&id=6eTRpgF0TFTj&format=png&color=000000" alt="JavaScript" width="40" height="40" style="vertical-align:middle;" />


## Технические знания и навыки

**1. Основы языка Java:**
- -[x] Типы данных, переменные, операторы
+ -[x] Условные конструкции (`if`, `switch`)
- -[x] Циклы (`for`, `while`, `do-while`, `for (for-each loop)`)
+ -[x] Методы и параметры:
  + -[x] Статические и нестатические методы
  + -[x] Методы экземпляра (Instance Methods)
  + -[x] Конструкторы (Constructors)
  + -[x] Геттеры и сеттеры (Getters & Setters)
  + -[x] Абстрактные методы (abstract)
  + -[x] Финализированные методы (`final`)
  + -[x] Перегруженные методы (overloaded)
  + -[x] Переопределённые методы (overridden)
  - -[ ] Методы класса `Object` (базовый класс для всех объектов):
    - -[x] `toString()`	— Возвращает строковое представление объекта.
    - -[x] `equals(Object o)`	— Проверяет, равны ли два объекта (по содержимому).
    - -[ ] `hashCode()`	— Возвращает хэш-код объекта (используется в коллекциях).
    - -[x] `clone()`	— Создаёт копию объекта.
    - -[x] `getClass()`	— Возвращает объект Class, описывающий текущий класс.
    - -[ ] `finalize()`	— Вызывается перед сборкой мусора (устарело, не рекомендуется).
  + -[x] Методы класса `String`:
    + -[x] `length()`	— Длина строки
    + -[x] `charAt(int index)`	— Символ по индексу
    + -[x] `substring(int begin, int end)`	— Подстрока
    + -[x] `equals(String s)`	— Сравнение по содержимому
    + -[x] `equalsIgnoreCase(String s)`	— Сравнение без учёта регистра
    + -[x] `contains(String s)`	— Содержит ли строка подстроку
    + -[x] `startsWith(String s)`	— Начинается ли строка с подстроки
    + -[x] `endsWith(String s)`	— Заканчивается ли строка подстрокой
    + -[x] `indexOf(String s)`	— Индекс первого вхождения
    + -[x] `replace(char a, char b)`	— Замена символов
    + -[x] `split(String regex)`	— Разделение строки по шаблону
    + -[x] `trim()`	— Удаление пробелов по краям
  - -[ ] Методы коллекций `ArrayList`:
    - -[ ] `add(E e)`	— Добавить элемент
    - -[ ] `get(int i)`	— Получить элемент по индексу
    - -[ ] `remove(int i)`	— Удалить по индексу
    - -[x] `size()`	— Количество элементов
    - -[ ] `contains(E e)`	— Проверка наличия элемента
    - -[x] `clear()`	— Очистить список
  + -[ ] Методы коллекций `HashMap`:
    + -[ ] `put(K key, V value)`	— Вставка пары ключ-значение
    + -[ ] `get(K key)`	— Получение значения по ключу
    + -[ ] `containsKey(K key)`	— Проверка наличия ключа
    + -[ ] `remove(K key)`	—Удаление пары по ключу
    + -[ ] `keySet()`	— Получить все ключи
    + -[ ] `values()`	— Получить все значения
  - -[ ] Обобщённые параметры (Generics):
    - -[ ] Использование `ArrayList<T>` и `HashMap<K, V>`
    - -[ ] Написание простого `Generic`-класса (например, `Box<T>`)
    - -[x] Написание `Generic`-метода (`<T> void printArray(List<T>)`)
    - -[x] Ограничения типов (`<T extends Number>`)
  + -[ ] Методы интерфейса `Comparable` и `Comparator`:
    + -[ ] `compareTo(T o)`	— Сравнение объектов (например, сортировка)
    + -[ ] `compare(T o1, T o2)`	— Сравнение двух объектов (Comparator)
- -[ ] Работа с массивами и коллекциями (`List`, `Map`, `Set`)
  - -[x] Массив (`Array`):
      ```java
      int[] numbers = new int[5];             // одномерный
      String[][] names = new String[3][4];    // двумерный
      double[][][] data = new double[2][3][4]; // трёхмерный
      ```
  - -[ ] Списки (`List`, например `ArrayList`) — добавление, удаление, перебор элементов:
`List<String> names = new ArrayList<>();`
  - -[ ] Множества (`Set`, например `HashSet`) — хранение уникальных элементов, проверка на наличие:
`Set<Integer> ids = new HashSet<>();`
  - -[ ] Отображения (`Map`, например `HashMap`) — хранение пар ключ-значение, доступ по ключу:
`Map<String, Integer> scores = new HashMap<>();`

+ -[x] Обработка исключений (`try-catch`, `throw`, `throws`)
- -[x] Основы ООП (наследование, инкапсуляция, полиморфизм, абстракция)
  - -[x] Наследование	Повторное использование кода	`extends`, `super`
  - -[x] Инкапсуляция	Сокрытие данных и логики	`private`, `public`
  - -[x] Полиморфизм	Разное поведение через один интерфейс	`@Override`, `interface`
  - -[x] Абстракция	Общие свойства без деталей	`abstract`, `interface`
+ -[x] Понимание `class`, `interface`, `record`, `enum`, `annotation`, `exception`

**2. Работа со стандартной библиотекой Java:**
* -[ ] `java.lang`, `java.util`, `java.io`
* -[ ] Работа с файлами
* -[ ] Работа со временем (`java.time`)
* -[ ] Основы потоков (`Thread`, `Runnable`, `synchronized`)

**3. Сборка проекта:**
* -[ ] Maven или Gradle: базовое понимание структуры проекта, зависимостей
* -[ ] Папки: `src/main/java`, `src/test/java`, `resources`, `pom.xml`

**4. Инструменты и среда разработки:**
* -[x] IDE (IntelliJ IDEA)
  * -[ ] Умение использовать IntelliJ IDEA или Eclipse:
    * -[ ] Автодополнение, отладка, работа с проектами
* -[x] Git (основные команды: `clone`, `commit`, `push`, `pull`, `branch`, `merge`)
* -[ ] Работа с системой контроля версий (GitHub/GitLab/Bitbucket)

## Работа с веб-технологиями:
* -[ ] Основы HTTP (методы GET, POST и т. д.)
* -[ ] Основы REST API
* -[ ] Простая работа с JSON и XML

## Тестирование:
* -[ ] JUnit (написание простых unit-тестов)
* -[ ] Основы TDD

## Навыки и понимание процессов разработки:
* -[x] Умение читать и понимать чужой код
* -[x] Готовность к обучению и работе в команде
* -[ ] Базовое понимание Agile/Scrum
* -[ ] Чтение документации
* -[x] Написание читаемых имён переменных и методов

## Дополнительные знания:
* -[ ] Spring Framework (Spring Boot, Spring MVC)
* -[ ] Hibernate / JPA
* -[ ] Основы SQL и работа с базами данных (PostgreSQL, MySQL)
* -[ ] Docker, CI/CD, микросервисы

## Учебные проекты

- [Calculator](https://github.com/KazarinovSU/calculator) — простой калькулятор на Java, практическое закрепление базовых конструкций и ООП  
- [GuessTheNumber](https://github.com/KazarinovSU/GuessTheNumber) — игра «Угадай число», тренировка работы с циклами и вводом данных  
- [Currency-Temperature-Converter](https://github.com/KazarinovSU/Currency-Temperature-Converter) — конвертер валют и температуры, практика с пользовательским вводом и арифметикой 

## GitHub Stats

![Vova's GitHub Stats](https://github-readme-stats.vercel.app/api?username=KazarinovSU&show_icons=true&count_private=true&hide_title=true&theme=highcontrast)

## Languages

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=KazarinovSU&layout=compact&theme=radical)


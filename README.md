# Beginner Java Developer
Привет! 👋
Я начинающий Java-разработчик, изучающий и практикующий основы языка и технологии. В процессе обучения освоил ключевые концепции и инструменты, необходимые для дальнейшего роста в области Java-разработки.
## 🔧 Технические знания и навыки

**1. Основы языка Java:**
* Типы данных, переменные, операторы ✅
* Условные конструкции (`if`, `switch`) ✅
* Циклы (`for`, `while`, `do-while`, `for (for-each loop)`) ✅
  * `break` — прерывает выполнение цикла:
  * `continue` — пропускает текущую итерацию:
* Методы и параметры ✅
  * Статические и нестатические методы ✅
  * Методы экземпляра (Instance Methods) ✅
  * Конструкторы (Constructors) ✅
  * Геттеры и сеттеры (Getters & Setters) ✅
  * Абстрактные методы (abstract) ✅
  * Финализированные методы (`final`) ✅
  * Перегруженные методы (overloaded) ✅
  * Переопределённые методы (overridden) 🔲
  * Методы класса `Object` (базовый класс для всех объектов):
    * `toString()`	— Возвращает строковое представление объекта. ✅
    * `equals(Object o)`	— Проверяет, равны ли два объекта (по содержимому). ✅
    * `hashCode()`	— Возвращает хэш-код объекта (используется в коллекциях). 🔲
    * `clone()`	— Создаёт копию объекта. ✅
    * `getClass()`	— Возвращает объект Class, описывающий текущий класс. ✅
    * `finalize()`	— Вызывается перед сборкой мусора (устарело, не рекомендуется). 🔲
  * Методы класса `String`:
    * `length()`	— Длина строки ✅
    * `charAt(int index)`	— Символ по индексу ✅
    * `substring(int begin, int end)`	— Подстрока ✅
    * `equals(String s)`	— Сравнение по содержимому ✅
    * `equalsIgnoreCase(String s)`	— Сравнение без учёта регистра ✅
    * `contains(String s)`	— Содержит ли строка подстроку ✅
    * `startsWith(String s)`	— Начинается ли строка с подстроки ✅
    * `endsWith(String s)`	— Заканчивается ли строка подстрокой ✅
    * `indexOf(String s)`	— Индекс первого вхождения ✅
    * `replace(char a, char b)`	— Замена символов ✅
    * `split(String regex)`	— Разделение строки по шаблону ✅
    * `trim()`	— Удаление пробелов по краям ✅
  * Методы коллекций `ArrayList`:
    * `add(E e)`	— Добавить элемент 🔲
    * `get(int i)`	— Получить элемент по индексу 🔲
    * `remove(int i)`	— Удалить по индексу 🔲
    * `size()`	— Количество элементов ✅
    * `contains(E e)`	— Проверка наличия элемента 🔲
    * `clear()`	— Очистить список ✅
  * Методы коллекций `HashMap`:
    * `put(K key, V value)`	— Вставка пары ключ-значение 🔲
    * `get(K key)`	— Получение значения по ключу 🔲
    * `containsKey(K key)`	— Проверка наличия ключа 🔲
    * `remove(K key)`	—Удаление пары по ключу 🔲
    * `keySet()`	— Получить все ключи 🔲
    * `values()`	— Получить все значения 🔲
  * Generics (Обобщения):
    * Использование `ArrayList<T>` и `HashMap<K, V>` 🔲
    * Написание простого `Generic`-класса (например, `Box<T>`) 🔲
    * Написание `Generic`-метода (`<T> void printArray(List<T>)`) ✅
    * Ограничения типов (`<T extends Number>`) ✅
  * Методы интерфейса `Comparable` и `Comparator`:
    * `compareTo(T o)`	— Сравнение объектов (например, сортировка) 🔲
    * `compare(T o1, T o2)`	— Сравнение двух объектов (Comparator) 🔲
* Работа с массивами и коллекциями (`List`, `Map`, `Set`) 🔲
  * Массив (Array) структура вида: ✅
    * ```java
      int[] numbers = new int[5];             // одномерный
      String[][] names = new String[3][4];    // двумерный
      double[][][] data = new double[2][3][4]; // трёхмерный
      ```
* Обработка исключений (`try-catch`, `throw`, `throws`) ✅
* Основы ООП (наследование, инкапсуляция, полиморфизм, абстракция) ✅
  * Наследование	Повторное использование кода	`extends`, `super` ✅
  * Инкапсуляция	Сокрытие данных и логики	`private`, `public` ✅
  * Полиморфизм	Разное поведение через один интерфейс	`@Override`, `interface` ✅
  * Абстракция	Общие свойства без деталей	`abstract`, `interface` ✅
* Понимание `interface`, `abstract class`, `enum` ✅

**2. Работа со стандартной библиотекой Java:**
* `java.lang`, `java.util`, `java.io` 🔲
* Работа с файлами 🔲
* Работа со временем (`java.time`) 🔲
* Основы потоков (`Thread`, `Runnable`, `synchronized`) 🔲

**3. Сборка проекта:**
* Maven или Gradle: базовое понимание структуры проекта, зависимостей 🔲
* Папки: `src/main/java`, `src/test/java`, `resources`, `pom.xml` 🔲

**4. Инструменты и среда разработки:**
* IDE (IntelliJ IDEA) ✅
  * Умение использовать IntelliJ IDEA или Eclipse: 🔲
    * Автодополнение, отладка, работа с проектами 🔲
* Git (основные команды: `clone`, `commit`, `push`, `pull`, `branch`, `merge`) ✅
* Работа с системой контроля версий (GitHub/GitLab/Bitbucket) 🔲

## 🌐 Работа с веб-технологиями:
* Основы HTTP (методы GET, POST и т. д.) 🔲
* Основы REST API 🔲
* Простая работа с JSON и XML 🔲

## 🧪 Тестирование:
* JUnit (написание простых unit-тестов) 🔲
* Основы TDD 🔲

## 🧠 Навыки и понимание процессов разработки:
* Умение читать и понимать чужой код ✅
* Готовность к обучению и работе в команде ✅
* Базовое понимание Agile/Scrum 🔲
* Чтение документации 🔲
* Написание читаемых имён переменных и методов ✅

## 📚 Дополнительные знания:
* Spring Framework (Spring Boot, Spring MVC) 🔲
* Hibernate / JPA 🔲
* Основы SQL и работа с базами данных (PostgreSQL, MySQL) 🔲
* Docker, CI/CD, микросервисы 🔲


## 📊 GitHub Stats

![Vova's GitHub Stats](https://github-readme-stats.vercel.app/api?username=KazarinovSU&show_icons=true&count_private=true&hide_title=true&theme=highcontrast)

## 🗣️ Top Languages

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=KazarinovSU&layout=compact&theme=radical)


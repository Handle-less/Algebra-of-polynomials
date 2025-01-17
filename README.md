<h1>Алгебра полиномов</h1>

<h3>Цель проекта:</h3> Создание программы, которая облегчит работу с алгеброй полиномов от трех переменных, позволит пользователю осуществлять различные операции над ними и получать результаты вычислений. Важным требованием является сохранение введенных пользователем данных, чтобы можно было их использовать еще раз.

<h3>Функциональные требования:</h3>

<li>Пользователь должен иметь возможность вводить полиномы от трех переменных.</li>
<li>Полиномы хранятся в виде односвязаного списка.</li>
<li>Полиномы хранятся во всех таблицах одновременно, ключом является имя.
Таблиц будет 6 видов: линейная на массиве, линейная на списке, упорядоченная на
массиве, дерево (авл), две хэш-таблицы;</li>
<li>Операции в выражениях из полиномов: сложение, вычитание, умножение на константу. операции должны выполняться, используя
постфиксную форму.</li>
<li>Операции над таблицами: добавление полинома (во все сразу), удаление полинома (во всех
сразу), поиск (только в активной таблице, выполняется в процессе вычисления выражений,
составленных из имен полиномов).</li>
<li>Активная (выбранная пользователем) таблица должна выводиться на экран в формате двух столбцов: 1) имя полинома, 2) строковое представление полинома.</li>
<li>Сохранение введенных пользователем данных в файл, чтобы можно было их использовать еще раз.</li>

<h3>Нефункциональные требования:</h3>

<li>Язык программирования: C++.</li>
<li>Программа должна быть написана с использованием объектно-ориентированного подхода.</li>
<li>Интерфейс программы должен быть интуитивно понятным и удобным для пользователя.</li>
<li>Программа должна обрабатывать некорректные данные и выводить соответствующие сообщения об ошибках.</li>

<h3>Ожидаемые результаты:</h3>
<li>Реализованная программа должна успешно выполнять все функциональные требования, описанные в ТЗ.</li>
<li>Программа должна быть протестирована на различных наборах входных данных.</li>

<h3>Модули и их описания:</h3>
<li>Модуль для работы с полиномами от трех переменных.
Описание: Данный модуль должен содержать класс для работы с полиномами от трех переменных, который будет иметь методы для выполнения операций над полиномами: сложение, вычитание, умножение на константу, а также методы для получения строкового представления полинома и его сохранения в файл (JSON).</li>

<li>Модуль для работы с таблицами полиномов.
Описание: Данный модуль должен содержать классы для работы с таблицами полиномов: линейной таблицей на массиве, линейной таблицей на списке, упорядоченной таблицей на массиве, таблицей на поисковом дереве (АВЛ), хеш-таблицей с открытым перемешиванием и хеш-таблицей со списками (метод цепочек). Каждый класс должен иметь методы для добавления, удаления и поиска полиномов, а также методы для вывода таблицы на экран в формате двух столбцов: имя полинома и строковое представление полинома.</li>

<li>Модуль для работы с постфиксной формой.
Описание: Данный модуль должен содержать класс для работы с постфиксной формой, который будет иметь метод для преобразования выражения, составленного из имен полиномов, в постфиксную форму.</li>

<li>Модуль для интерфейса программы.
Описание: Данный модуль должен содержать класс для интерфейса программы, который будет иметь методы для обработки ввода пользователя, вызова методов из других модулей и вывода результатов на экран. Интерфейс должен быть интуитивно понятным и удобным для пользователя, а также обрабатывать некорректные данные и выводить соответствующие сообщения об ошибках.</li>

<li>Общий модуль.
Описание: Данный модуль должен содержать общие классы и методы, которые будут использоваться другими модулями. Например, класс для работы с файлами, класс для работы с именами полиномов и т.д.</li>

<li>Тестирование программы.
Описание: Данный модуль должен содержать тесты для проверки правильной работы программы на различных наборах входных данных. Тесты должны покрывать все функциональные требования, описанные в ТЗ.</li>

<h3>Команда разработчиков</h3>
<li>Разработчик 1. Интерфейс. Линейная таблица на массиве. Таблица на поисковом дереве (АВЛ).<br>
Контакты: <a href="https://github.com/Crazy767">Александр С.<a></li>
<li>Разработчик 2. Полином (от трех переменных). Линейная таблица на
списке. Хеш-таблица с открытым перемешиванием. Общий интерфейс таблиц..<br>
Контакты: <a href="https://github.com/AndrewStiks">Андрей Д.<a></li>
<li>Разработчик 3. Постфикс для полиномов (доработанная обратная польская запись).
Упорядоченная таблица на массиве. Хеш-таблица со списками (метод цепочек).<br>
Контакты: <a href="https://github.com/Handle-less">Владислав С.<a></li>

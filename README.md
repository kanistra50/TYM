# TYM
Test You Math Knowledge.

[See demo](https://kanistra50.github.io/TYM/)



•	Требуется создать клиентскую страницу, которая представит клиенту приложение для тестирования знаний математики. Страница должна иметь две табы:
Проверка
Установка

Таба «Установка» содержит блок checkbox’ов, которые определяют тип проверочных примеров, которые будут генерироваться: сложение, вычитание, умножение, деление. Тип генерируемых примеров должен случайным образом выбираться из установленного пользователем множества.

Таба «Проверка» основная и используется для взаимодействия с пользователем при проведении тестирования. Содержит панель с примером, поле для ввода ответа и панель для отображения результата – количества правильных ответов и ошибок.
Приложение генерирует пример и ожидает от пользователя ввода ответа на него. Проверив предоставленный ответ – отражает результат, увеличивая соответствующее кол-во правильных/неправильных ответов. После каждого ответа пользователю предлагается следующий пример.

ОГРАНИЧЕНИЯ
Никаких postback.
Приложение должно работать под >IE9, Chrome..
Нет ограничений на выбор компонентов и/или библиотек для формирования пользовательского интерфейса.
Для поля, в которое пользователь вносит ответы требуется реализация валидации – ввод только натуральных чисел.
Предполагаемый результат для тестовых примеров не должен превышать 100 (клиент/заказчик – младшие школы).
В дальнейшем предполагается сохранять результаты тестирования в БД. Требуется проработать структуру и наметить способы манипуляции с данными.
Написать SQL-операторы, для:
•	Создания нужных таблиц:
•	Тестируемые ученики (имя)
•	Проведённые тесты (дата, типы примеров, кол-во правильных и неправильных ответов)
•	Неправильно решенные при тестировании примеры (пример, неверный ответ)
•	Сохранения результата тестирования
•	Получения отчетов. Выполнить сортировку по дате (от настоящего к прошлому) и имени тестируемого ученика (алфавитный порядок):
•	Показать учеников, прошедших тестирование за указанный период (имя, дата, типы решённых примеров, кол-во правильно и неправильно решённых примеров, результат = % правильных ответов)
•	Показать учеников, ни разу за период не проходивших тестирование
•	Ученики, проходившие тестирование не менее трёх раз за указанный период, результат которых не превысил 50%

Проект 2. Идея и интерфейс приложения
=============

Приложение: 

TrafficLaws


Задача:

Проверка знаний пользователя по вопросам экзаменов Правил дорожного движения России.


Аудитория:

Те, кто хотят протестировать (закрепить, повторить) свои знания Правил дорожного движения.


Сценарий:

После запуска приложения пользователю предлагается:
 - Указать режим тестирования (один билет или 20 случайных вопросов из случайных билетов)
 - Указать номер билета если выбран первый режим
 - Начать тестирование
 - Закрыть приложение
 

Поведение:

Еще до появления основного окна приложение сформирует внутри себя структуры, которые хранят в себе все билеты.
После назатия кнопки "Начать тест", открывается новое модальное окно и начинается тестирование
Тестирование проходит по массиву вопросов, состав которого формируется в зависимости от указаний пользователя на главном окне.
Пользователю показывают картинку текущего вопроса (если таковая предусмотрена вопросом), собственно текст вопроса, и варианты ответа.
У пользователя есть возможность выбрать один из них, после чего, нажатием на одну из кнопок внизу окна указать дальнейшее действие:
 - кнопка "Закрыть" прекращает тестирование, закрывает окно с вопросом и возвращается в основное окно
 - кнопка "Подсказка" открывает режим подсказки (описано чуть ниже)
 - кнопка "Следующий вопрос" проверяет правильность выбранного пользователем варианта ответа и, если указан верный вариант, то переходит к следующему вопросу в списке.
   если вопросов больше нет, но происходят действия, описанные в кнопке "Закрыть"
   если указанный пользователем вариант неверен, то открывается режим подсказки
   
Режим подсказки это всплывающее под верным вариантом ответа окно, в котором пользовтель может прочесть тескт, описывающий правильный ответ.
В этом окне предусмотрено изображение, которое может изображать зеленую галочку (режим вызван по кнопке "Подсказка") или
красный крест (режим вызван по кнопке "Следующий вопрос", а выбранный пользователем вариант ответа был неверен)


Примечания:

Я не стал копипастить все вопросы Правил дорожного движения, т.к. для этого проекта, как мне кажется трех билетов вполне достаточно.


# Decision-tree
example of preprocessing people who entered course with prediction of passing the course <br>
Выгрузка логов пользователей записавшихся на курс https://stepik.org/media/attachments/course/4852 (дата действия, просмотр, решение, пройдено/не пройдено ,удачная / неудачная попытка) <br>
Предобработка данных, попытка нахождения разницы в днях между действиями на курсе <br>
Оценка параметра is_gone для пользователей если пользователь не делает никаких действий на курсе больше 30 дней (по результатам гистограмы разницы в днях между действиями на курсе) <br>
Результаты: <br>
Создание таблицы для пользователей о текущих удачных попытках (для выдачи сертификатов) <br>
Попытка выдачи прогноза пройдет ли пользователь курс по результатам действий пользователя за 3 дня (оценка субъективная 3 дня) <br>
Нахождение самого сложного задания на курсе (на котором больше всего ошибочных результатов) <br>
Результаты о попытках пользователей по решениям степов <br>

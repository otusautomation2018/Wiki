## Правила работы над проектом:
*Важно:*
у всех задач в issues должны быть назначены labels. Автор issue должен назначить ей минимум один label.

0. Баги - самые высокоприоритетные задачи
	* Если вы нашли баг - создавайте issue в zenhub и двигайте ее в самый верх колонки TODO
	* Назначайте созданным issue лейблы
1. Берем задачу в ZenHub
2. Назначаем ее на себя
3. Передвигаем в колонку Progress
4. Создаем ветку в Git с названием вида “1-fb-AK-SimpleTests”, где “1” это номер Github issue, “AK” это Ваши инициалы или часть ника.
5. Пишем код, пишем тесты
6. Делаем PR в Github, ставим лейбл WIP
7. Заполняем в PR id issue, описание сделанной работы
8. Связываем issue и PR путем ссылки в описании
9. Передвигаем задачу в колонку CodeReview, убираем лейбл WIP
10. Добавляем двух ревьюеров.
11. Когда ревьюер проверяет PR - он смотрит не только на код, но и локально у себя запускает приложение из данной ветки и проверяет функциональность сам
12. Для мерджа необходимо два аппрува
13. Когда все проверки пройдены - автор PR мерджит PR	
14. При мердже - не просто нажимаем кнопку мердж, а рядом с ней есть стрелка, и выбираем ‘Squash and merge’. Делается это для того, чтобы у вас все коммиты объединялись в один и заливались так в мастер
15. После мерджа удаляем ветку появившейся кнопкой в гитхабе
16. Двигаем задачу в Done в ZenHub

* Тот кто сломал тесты - тот их и чинит
* После мерджа удаляем ветку из гитхаб
* Для мерджа необходимо 2 апрува
* Ежедневно проверять Slack, если пропадаете на несколько дней - поставить в слаке соответствующий статус

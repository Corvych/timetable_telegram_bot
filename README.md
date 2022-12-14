# Универсальный Telegram бот Школьного Расписания Уроков
____

## Зачем это вообще всё надо?
____

0. Попрактиковать C# в написании Telegram ботов в связке с сервером баз данных MySQL.
1. Решить глобальную проблему в неразберихе школьного расписания, особенно для более старших классов.
2. Упростить доступ к актуальной информации по школьному расписанию, ведь проще зайти в Telegram и нажать кнопку в боте, чем лезть в чат (как правило, в пакостном WhatsApp), искать там ссылку на Google Sheets (или что-то подобное), чтобы посмотерть актуальное расписание.
3. Добавить немного полезных фич с помощью алгоритмов.
____
## Чего за фичи-то такие полезные?
____

- **Разделение пользователей бота на профили**:
В некоторых школах России существует система деления учеников на "профили", то есть конкретный ученик углублённо изучает именно то, что ему нужно. В связи с этим, у каждого ученика своё расписание. Бот будет давать конкретному пользователю его расписание, с учетом профильных предметов.
- **Таймер урока**:
Вот, сидишь на уроке, сидишь, а он чертовски скучный, хочется же узнать, когда же он закончится, чтобы выйти и отдохнуть. Бот посчитает время окончания и приободрит тебя каким-нибудь весёлым фактом или сообщением, а, может и посочувствует.
- **Напоминание о "Больших Переменах"**:
Иногда ученики забывают об "обеденных" или "больших" переменах, из-за чего остаются голодными, включив функцию напоминания о таких переменах, ты точно не останешься голодным и злым.
- **Поддержка "Окон"**:
При обучении по системе профилей, в расписании учеников возможны "окна" - свободное урочное время, в которое можно позаниматься своими делами. В Боте будет предусмотрена поддержка этих самых "окон" с возможностью напоминания о них.
- **Уведомления от Администрации**:
Данная опция будет полезна для уведомления учеников о любых важных событиях/мироприятиях, например: замена преподавателя на уроке

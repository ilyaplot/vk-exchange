# Сервис обмена постами vk.com

## Основные понятия
 - Социальная сеть Вконтакте (vk.com), далее "VK"
 - Группа или паблик VK, далее "Паблик"
 - Пользователь VK, имеющий возможность размещать посты от имени Паблика (администратор или редактор), далее "Админ"
 - Сайт проекта, сам проект, далее Сервис

### Идея проекта
Сервис разрабатывается для бесплатного обмена постами VK.

Обмен постами позволит Пабликам получать подписчиков беплатно из других, близких по смыслу и аудитории Пабликов без финансовых затрат.

Любой Паблик может выставить свои посты на обмен и принять для обмена пост других пабликов.

В одно и то же время, в обоих пабликах будет происходить перекрестный репост записей. Если по каким-либо причинам не удалось сделать репост в одном из Пабликов, обмен будет отменен и репост, который уже был размещен в рамках обмена будет отменен. 

Должен быть реализован мониторинг размещенных репостов. В случае удаления одного из репостов обмена, репост, сделанный в рамках этого обена во втором паблике так же будет удален.

Должны быть установлены ограничения для молодых Пабликов. Не смогут участвовать в обмене:
 - Паблики, имеющие менее N подписчиков
 - Паблики, состоящие на N% из репостов или рекламных постов
 - Паблики, Админы которых систематически удаляют репосты обмена
 - Паблики из черного списка
 - Паблики, Админы которых находятся в черном списке
 - Паблики, состоящие из менее, чем N постов

### Работа над проектом и финансовые отношения
Над проектом работает один разработчик с возможностью подключения к проекту сторонних разработчиков.
В случае подключения разработчика к проекту, затраты на его содержание, оплата труда и размер прибыли обсуждается индивидуально и не опубликовывается. В случае публикации информации сотрудничества, разработчик исключается из проекта.

### Используемое ПО и другие программные продукты
#### По для разработки
 - Netbeans DEV c поддержкой PHP7
 - PgAdmin 1.22
 - Git, GitHub

#### Языки программирования, базы данных и фреймворки
 - PHP 7.0.10 backend
 - Yii 2.x backend, frontend
 - JavaScript, jQuery frontend
 - PostgreSQL 9.5 

### TodoList
 - Развернуть базовый скелет проекта на Yii2
 - Настроить DEV сервер проекта
 - Составить список основного функционала
 - Обозначить ключевой функционал, который должен быть реализован в инкубационном периоде
 
Смотри весь процесс разработки на youtube:  https://www.youtube.com/playlist?list=PL1YWgUoMSKjAmmkJescMmgV4j9VLzCmM8

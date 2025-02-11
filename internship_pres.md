### Part 2. Оформление отчета по итогам стажировки

1. Компания, в которой проходила стажировка, чем она занимается, какого рода проекты выполняет, какая у нее корпоративная культура.

*ПАО Сбербанк - высокотехнологичная финтехкомпания, которая давно перестала ассоциироваться только с банковским сервисом. Сегодня Сбербанк интегрирует в себе множество цифровых продуктов, которыми пользуются в повседневной и профессиональной жизни.
Внутренняя инфраструктура корпорации представлена несколькими продуктами, главные из которых портал Друг и Пульс. Первый интегрирует доступ к различными сервисам и продуктами, например, СберЧату, получению услуг, активации ИИ-помощника, получению выписок и множествую других. Пульс - платформа, которая включает все возможные административные ресурсы, инфо о сотрудниках, данные об обучении и др. И в Пульс и СберДруг являются исчерпывающими источниками знаний для любого сотрудника Сбер с момента первого "касания" компании и до увольнения.*


2. Короткий рассказ о том, на какой должности ты стажировался, в каком функциональном подразделении/отделе. Что входило в твои ежедневные обязанности.

*Команда сервиса "Роутер" (АОО ЦИТПРМП) трайба Технологии занимается разработкой и оптимизацией процесса межсервисного взаимодействия при обращении пользователей за помощью.

В Друге существует раздел, посвященный обращениям и инцидентам. Данные, которые оставляют пользователи аккумулируются на сервере и оперативно обрабтаываются. Все происходит автоматически. Целью "Сбер Роутера" является и предотвращения возможных проблем.

Задачи "Сбер Роутер"
- Автоматизация обработки обращений пользователей и возникающих инцидентов
- Перераспределение поступающих обращений и данных об инцидентов, которые невозможно решить автоматически, инженерам поддержки
- Предотвращение выхода оборудование из строя путем автоматического мониторинга 

Пользовательские инциденты поступают с фронта СберДруга, технологические - непосредственно от Service Manager, где они формируются автоматически.

В задачи стажера входило оказание содействия команде разработчиков. Прежде чем выполнить какое-либо задание потребовалось досконально изучить материалы, описывающую работу микросервисов. Все подробно изложено в Confluence.*


3. Короткий рассказ о структуре проектной команды или функционального подразделения, в котором ты проходил стажировку, а также принятую методологию организации проектной деятельности, используемые процессы и инструменты.

*Проектная команда "Роутер" являются частью команды "Сбер Ассист", главная задача которой оптимизация ресурсов сотрудников саппорта.
Конкретно команда Роутер реализует следующие проекты:
- Фронтальные микроприложения на базе СберДруга, которые позволяют автоматизировать решение обращения пользователя или перенаправить его на соответствующего специалиста. 
- Роутер или автодиспетчер - автоматическое распределение запросов, которые не могут быть решение сервисными инженерами.
- Микросервис для предиктивного решения проблем с оборудованием путем анализа данных из систем мониторинга. 
- Микросервис Единый поставщик данных из Service Manager для всех команд. Service Manager -  хелп-деск система, аккумулирующая тикеты (запросы от пользователей) и данные об инцидентах, которые создаются автоматически на основе обращений в СберДруг.

В структуре команды: разработчики на Java и C#, DevOPS-инженер и владелец продукта.*

4. Рассказ о выполненных тобой задачах (с примерами самой нелюбимой и самой любимой задачи), чем занимался на стажировке, над каким(и) проектом(ами) работал. В качестве небольшого анализа твоей работы также предоставь статистику поставленных тобой задач: их общее количество, количество успешно выполненных, количество возвратов задач на переделку и среднее время выполнения задач. Укажи, какие навыки/качества ты приобрел, какие навыки/качества использовал (не только технические!) в процессе стажировки с примерами ситуаций.

*Месяцы стажировки пришлись на период, когда в команде разрабатывался единый поставщик данных, а также происходил переход от вендора БД Oracle на Postgres.

За период стажировки я смогла познакомиться с технической документации к микросервисам. Всего в системе Сбер Ассист действует пять микросервисов, в том числе: система обработки тикетов (Service Manager), поставщик данных, роутер, сервис, получающий сведения из систем мониторинга.

Поставленные задачи:
    1. Реализовать единый поставщик данных из Service Manager для всех команд. 
    Требовалась аналитика данного процесса. На основании таблицы ЗНО необходимо описать поля Инцидентов, которые существуют в БД Oracle.

В систему обработки тикетов (Service Manager) поступают запросы, далее происходит автоматизированное распределение задач на инженеров. К Service Manager имеют доступ пять команд SberAssist, которые работают с запросами. Суть задачи - сделать так, чтобы источник данных для всех команд был один и данные не дублировались для разных команд.

Существует таблица ЗНО - запросов на обслуживание - это база данных с полями для описания инцидента: NUMBER, STATUS, CATEGORY и др. Из этой таблицы требовалось взять Инциденты и описать их.

    2. Написание аналитики процесса повторной установки пакета на АРМ.

5. Итоги твоей стажировки, чего достиг, какой вклад внес в компанию и проект(ы), над которым(и) непосредственно работал.

Считаю, что стажировка помогла лучше понять роль системного аналитика в команде. Особенно прояснить ситуацию смог курс для начинающих системных аналитиков, организованный командой СберДруга. 
Как выяснилось, роль системного аналитика подразумевает комплексное знание об архитектуре проекта, применяемых технологиях, которые используются в конкретной системе. По итогам аналитики, подготавливаемой специалистом, происходит дальнейшая разработка процессов. Аналитка дает важные ориентиры для разработчиков, без нее возникает множество дополнительных вопросов, решение которых сильно тормозит процесс.
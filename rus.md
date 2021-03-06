# Дайджест новостей №2

Привет! Это второй выпуск нашего, всё ещё экспериментального, еженедельного
дайджеста новостей. Его веду я, [Андрей Романов][13], фронтенд-разработчик
в Avito и автор сообщества [For Web][14]. Напомню, что основная
идея этого дайджеста — собрать в одном месте наиболее важные и полезные
материалы прошедшей недели, сопроводив их небольшим описанием. Не стесняйтесь
делиться предложениями по улучшению дайджеста в комментариях.


## Русскоязычные материалы
### [Дорогой JavaScript, ...][8]

Джеймс Кайл обращается к сообществу с призывом ценить труд своих коллег.
Он как активный участник опесорс-сообщества не раз сталкивался с хамством
других разработчиков, считавших, что им должен весь мир. Не забывайте, что
даже за плохими по вашему мнению опенсорс-проектами стоят такие же
разработчики, как и вы — уважайте их труд и критикуйте конструктивно.


### [Распутываем спагетти-код: как писать поддерживаемый JavaScript][12]

Как не сойти с ума, поддерживая старый проект с легаси-кодом? Первой мыслью
может быть «здесь нужно всё выкинуть и переписать с нуля!». Мориц Крёгер
рассказывает, как последовательно сделать из кошмарного проекта конфетку —
от анализа и выработки единого кодстайла до тестов и документации.


### [Основы производительности React-приложений][6]

Пишете на React, но нечасто используете метод `shouldComponentUpdate`?
Обязательно прочитайте эту статью. Вы узнаете, когда React запускает перерисовку
компонентов и как её избежать, если компонент не менялся — на средних
и больших проектах это просто необходимо, иначе всё начнёт тормозить.


### [Как писать сообщения коммитов][4]

Практические приёмы и советы по улучшению сообщений коммитов от Криса Бимса.


## Англоязычные материалы
### [Chrome 55 uses ~30% less memory than Chrome 54][0]

Небольшая, но приятная для всех новость — Chrome 55 потребляет на ~30% меньше
памяти, чем предыдущая версия.


### [Node.js Benchmarks][1]

В Node.js появилась рабочая группа, ответственная за производительность,
а вместе с ней появилась страничка, на которой ежедневно выкладываются
результаты тестов производительности разных версий node.js. Основные задачи рабочей
группы — отслеживать и своевременно предотвращать снижение производительности.
Кстати, любой желающий может присоединиться к рабочей группе и помочь.


### [CSS Grid!][2]

У вас есть какие-то вопросы или сомнения насчёт CSS-гридов? Эрик Мейер в виде
статьи-диалога ответил на все волнующие вопросы: когда и где будут
поддерживаться гриды, как быть со старыми браузерами, какие проблемы решаются
гридами и по каким материалам учиться.


### [Installing web apps on phones (for real)][3]

Раньше прогрессивные веб-приложения можно было только добавить на главный экран,
и они не вели себя как нативные приложения в полной мере. Теперь появилась (пока
что экспериментальная) возможность «честно» устанавливать их на устройство.
Хенрик Йортег написал большой обзор: какое место занимают PWA на рынке, какие
сейчас есть проблемы и как они решаются появлением возможности установки.


### [Virtual CSS with Styletron][5]

Styletron — новый инструмент для CSS в JS, отличающийся от существующих решений
высокой производительностью и меньшим количеством генерируемых стилей. Под
капотом работает движок вроде виртуальной DOM, только для CSS. Этот движок
генерирует атомарные классы для реиспользования общих кусков стилей, за счёт
чего и достигается высокая эффективность инструмента.


### [The Web, Worldwide][7]

Тим Кэдлек сделал удобный сервис со статистикой использования интернета по всему
миру. Выбираете интересующую вас страну и получаете основную информацию о стране
и её жителях (население, уровень грамотности, доступ к электричеству)
и детальную информацию об интернете в этой стране (количество пользователей
и качество связи, доступность связи, использование HTTPS).

![Книга Working the Command Line на разных устройствах][working the command line]


### [Working the Command Line][9]

Реми Шарп учит основам и полезным приёмам работы с командной строкой в новой
книге серии A Book Apart Briefs.


### [Learn Advanced CSS Layout Techniques][10]

Новый видеокурс на Egghead о продвинутых приёмах вёрстки: от скрытия пустых
элементов до разбиения меню на колонки без изменения разметки.

![JavaScript 30 — тридцатидневное соревнование по программированию на чистом JavaScript][javascript 30]


### [JavaScript 30][11]

Как давно вы писали на чистом JavaScript? Уэс Бос выпустил новый курс,
посвящённый изучению JS на практике. 30 дней, 30 видео и 30 проектов, которые
вам предстоит сделать без использования каких-либо библиотек или фреймворков.


[0]: https://www.prerender.cloud/blog/2016/12/03/chrome-memory-54-vs-55
[1]: https://benchmarking.nodejs.org/
[2]: http://meyerweb.com/eric/thoughts/2016/12/05/css-grid/
[3]: https://joreteg.com/blog/installing-web-apps-for-real
[4]: http://frontiermag.ru/commit-message.html
[5]: https://ryantsao.com/blog/virtual-css-with-styletron
[6]: http://blog.csssr.ru/2016/12/07/react-perfomance/
[7]: https://www.webworldwide.io/
[8]: https://habrahabr.ru/post/316978/
[9]: https://abookapart.com/products/working-the-command-line
[10]: https://egghead.io/courses/learn-advanced-css-layout-techniques
[11]: https://javascript30.com/
[12]: http://prgssr.ru/development/rasputyvaem-spagetti-kod-kak-pisat-podderzhivaemyj-javascript.html
[13]: http://andrew-r.ru
[14]: http://vk.com/forwebdev

[working the command line]: img/working-the-command-line.jpg "Working the command line"
[javascript 30]: img/javascript30.png "javascript 30"

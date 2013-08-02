### Ответы на вопросы анкеты для поступающих в ШРИ 2012

#### Год рождения

1989

#### Город, в котором вы живете

Ростов-на-Дону

#### Вуз, факультет, специальность, кафедра

Южный Федеральный Университет (бывш. РГУ), факультет механики, математики и компьютерных наук, специальность — механик, кафедра теории упругости

#### Год окончания вуза

2011

#### Уровень владения английским

[X] средний

Читаю специальную литературу, например, [«Pro JavaScript Techniques» John Recig](http://www.ozon.ru/context/detail/id/4608155/).

#### Чего вы ожидаете от участия в Школе?

* хочу повысить свои скиллы; 
* пообщаться с другими людьми, которые хотят развиваться в области фронтенда;
* попасть на практику;
* устроиться на работу.

#### Откуда вы о нас узнали?

Со [страницы событий](http://events.yandex.ru)

#### Сколько времени вы были бы готовы уделять стажировке или работе в Яндексе?

Полный рабочий день

#### Расскажите о вашем опыте разработки. Нам будет интересно всё — как серьезный интерфейс, так и просто домашняя страничка.

У меня есть небольшой [сайт](http://vitkarpov.github.io), куда я выкладываю свое [портфолио](http://vitkarpov.github.io/projects.html). Сайт сделать с использованием [docpad](https://github.com/bevry/docpad).

Я сделал табачные акционные сайты для [Донтабака](http://www.action.dontabak.ru/), [Ричмонда](http://www.richmond-tobacco.com/) в 2010 и 2011 годах (акции проходят каждый год). 

Эти сайты построены по принципу одностраничных приложений — на запросы к сервер отдавал JSON с данными, шаблонизация проводилась на клиенте, для этого использовался [простой шаблонизатор Джона Рейсига](http://ejohn.org/blog/javascript-micro-templating/), для организации дата-биндинга не использовался фреймворк (типа angular или backbone).

Некоторые проекты я верстал с использованием независимых блоков, однако не использовал инструмены и придерживался классической структуры проекта на файловой системе. 

Последние проекты я верстал с БЭМ-ориентированной структурой файловой системы, с использованием шаблонизатора jade. Все, что нужно блоку лежит в папке блока, включая его разметку. Данные отделены от разметки и лежат в отдельном файле data.yaml.
Сборкой проекта в данном случае занимается grunt.js.

Конфиг гранта, стек технологий и идея взяты из [html-scaffold](https://github.com/vitkarpov/html-scaffold).

#### Если вы где-нибудь работали, расскажите, какие у вас были должностные обязанности и был ли опыт работы в команде.

Последние 1,5 года я работал в [Вебстрое](http://webstroy.ru/portfolio/sites/all/).

До Вебстроя, а также параллельно с ним работал [на фрилансе](http://free-lance.ru/users/vitkarpov/).

Первый год — на должности веб-технолога, занимался версткой и сборкой сайтов на Битриксе и YII (писал шаблоны, иногда правил контроллеры).  

Последние полгода работал на должности руководителя небольшой группы из 3 человек. Занимался планированием совместной работы, контролем качества верстки, работой с таск-трекером (Редмайн), внедрением различных инструментов, направленных на повышение качества и интереса к работе: wiki, jsdoc, jslink.

Большинство подходов не прижились из-за специфики работы: небольшие сайты на потоке обычно не нуждаются в документации, работа построена по принципу один человек — один сайт, супер качество вообще говоря не требуется (важнее скорость), для верстки не нужны шаблоны, потому что не удается использовать их сразу на бэкэнде.

Уволился, когда понял, что хочу работать над проетами с более длинным циклом разработки.

#### 	Перечислите, какими программными продуктами вы пользуетесь в своей работе — от редактора до специализированных утилит (Intellij Idea, Node.js, Uglify.js, GNU Make). Для каждого инструмента укажите, какие задачи вы с помощью него решаете и почему выбрали именно его.

В качестве редактора кода использую Sublime Text 2. Иногда что-то правлю в vim из командной строки. Для саблайма стоят несколько плагинов, которыми я пользуюсь:

* emmet — помогает быстрее писать ЦСС
* markdown preview — позволяет посмотреть сгенерированный маркдаун в html, прежде чем запушить какой-нибудь README
* DocBlockr — помогает быстрее писать jsdoc документацию

Под node.js запускаю grunt.js в качестве сборщика, здесь работают несколько тасков:

* uglify
* cssmin
* concat
* coffee
* styl

#### Пользуетесь ли вы командной строкой? Какими командами вы пользуетесь и какие задачи вы решаете с их помощью? С какими программами вы преимущественно или полностью взаимодействуете через интерфейс командной строки?

Да. Постоянно пользуюсь git, исключетельно через командную строку, а также программы из-под ноды: grunt, bem tools.

Для кодирования файлов в base64 (чтобы, например, иконки вставлять через data-uri) использую одноименную с форматом программу.

С файловой системой я работаю тоже преимущественно из командной строки: ls, pwd — чтобы осмотреть, mv — что-то куда скопировать или переменовать папку, touch, mkdir — создать файл или папку, cat — посмотреть содержимое файла или скопировать его в другой файл (поменяв стандартный вывод для cat), rm -rf — если нужно что-то удалить.

ps позволяет посмотреть список запущенных процессов, а kill — убить какой-нибудь процесс по ИД, это полезно, например, когда запускаешь grunt или bem server как демон (чтобы можно было пользоваться консолью и создавать блоки с помощью bem create, например), а после хочешь прервать его работу.

#### Напишите на JavaScript функцию, которая выводит список всех чисел, которые равны сумме факториалов своих цифр.

https://github.com/vitkarpov/factorial


#### Даны незавершенные интерфейсы корабля и планеты. Напишите недостающий код.

https://github.com/vitkarpov/introtask-space

#### Сверстайте форму-анкету с нашими заданиями для кандидатов.

https://github.com/vitkarpov/yandex-shri

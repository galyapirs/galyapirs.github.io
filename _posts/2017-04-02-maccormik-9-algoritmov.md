---
layout: post
title:  "Девять алгоритмов, которые изменили мир. Остроумные идеи, лежащие в основе современных компьютеров"
date:   2017-04-02 00:00:00 +0000
book_author: "Дж. Маккормик"
bibliographic_data: "Дж. Маккормик. Девять алгоритмов, которые изменили мир. Остроумные идеи, лежащие в основе современных компьютеров / Пер. с англ. Слинкин А. А. - М.: ДМК Пресс, 2016. - 236 с."
excerpt: "Прочитав книгу, вы не станете специалистом по компьютерной безопасности, искусственному интеллекту или еще какой-то области информатики,вы не станете гораздо более опытным пользователем компьютера. Конечно, кое-какие практически полезные знания вы приобретёте. И вы сумеете по-настоящему оценить красоту идей, с которыми имеете дело каждый день, пользуясь своими компьютерными устройствами. Автор объясняет великие идеи просто, не требуя от читателя знания информатики или умения программировать."
cover: ""
---

Из аннотации книги:

> Ежедневно мы используем впечатляющие технологические достижения, даже не задумываясь об этом. Мы передаем по сети гигабайты информации, просматриваем тысячи документов в поисках необходимого, совершаем покупки в интернет-магазинах. Мы архивируем объемные материалы, так чтобы их можно было отправить по электронной почте, и пользуемся искусственным интеллектом компьютеров, которые автоматически исправляют опечатки в тексте, ретушируют фотографии и делают за нас многое другое...
>
> Все это при нынешнем уровне развития технологий воспринимается как должное. Но ведь такие «чудеса» были бы невозможны без величайших идей информатики, родившихся в XX веке!
>
> Эта книга - о том, как эти идеи зародились и как воплощались в жизнь.
>
> Издание рассчитано на широкую аудиторию. Предварительного знакомства с информатикой от читателей не требуется.

Об авторе:

> Джон Маккормик (John MacCormick) –преподаватель информатики и ученый. Вырос в Новой Зеландии, изучал математику и информатику в Англии, в настоящее время живет в штате Пенсильвания, США. Маккормик защитил докторскую диссертацию по информатике в Оксфордском университете, работал в исследовательских лабораториях компаний Hewlett-Packard и Microsoft, а сейчас является профессором информатики в колледже Дики неон. В сферу его интересов входят такие области, как машинное зрение, крупномасштабные распределенные системы, обучение информатике и пропаганда информатики в обществе.

стр. 12

> #### Глава 1. Введение: необычные идеи, каждодневно используемые в компьютерах
>
> Сегодня, в 21 веке мы наслаждаемся плодами поражающего воображение развития технологий, но никаких вычислительных устройств – будь то кластер из самых мощных доступных сегодня машин или модный гаджет последней модели – не существовало бы без основополагающих идей информатики, возникших в 20 столетии.

стр. 13

> … алгоритм – это рецепт, в котором описывается точная последовательность шагов, приводящая к решению задач.

стр. 21

> #### Глава 2. Индексирование в поисковых системах: поиск иголки в самом большом в мире стоге сена
>
> Поисковые системы оказывают колоссальное влияние на нашу жизнь. Но обращаясь к ним с запросами много раз на дню, мы редко задумываемся над тем, как этот замечательный инструмент работает. Огромный объем доступной информации, скорость поиска и качество его результатов кажутся настолько естественными, что мы раздражаемся, когда ответ не приходит за одну-две секунды. Мы как-то забываем, что каждый успешный поиск находит иголку в самом большом в мире стоге сена: Всемирной паутине

стр. 22

> … обработка запроса состоит из двух основных шагов: сопоставление и ранжирование. На практике оба шага для повышения эффективности объединяются в один. Но концептуально они различны, поэтому будем предполагать, что сопоставление завершается до начала ранжирования.

стр. 23

> Задача выбора и правильного упорядочения нескольких лучших результатов называется «ранжированием». Этот второй этап, следующим за сопоставлением, и является самым важным. В жестоком мире индустрии поиска выживают системы с лучшим механизмом ранжирования, остальные вымирают. Не будет преувеличением сказать, что сама жизнь и смерть поисковых систем целиком зависят от алгоритмов ранжирования.

стр. 24

> В основе любой поисковой системы лежит фундаментальная идея индекса. Но не создатели поисковых систем придумали индексы; на самом деле, идея стара, как сама письменность.

стр. 35

> … само существование поисковой системы зависит от качества ранжирования, а его можно значительно повысить, учитывая структуру страницы.

стр. 38

> #### Глава 3. PageRank: технология, породившая Google
>
> … новаторский алгоритм ранжирования результатов поиска, который известен под названием PageRank, изобрели Ларри Пейдж и Сергей Брин в 1997 году, опубликовали его в 1998 году в статье, представленной на научную конференцию «The Anatomy of a Large-scale Hypertextual Web Search Engine» (Анатомия системы крупномасштабного гипертекстового Интернет-поиска).

стр. 44

> … трюк со случайным посетителем. … он сочетает желательные характеристики трюков с гиперссылками и авторитетностью, но работает, даже когда гиперссылки образуют цикл.

стр. 45

> … во всех примерах из этой главы случайные посетители рестартуют с вероятностью 15%, именно такое значение выбрали основатели Google Пейдж и Брин в оригинальной статье, где описали прототип их поисковой системы.

стр. 49

> Поисковые системы вынуждены втягиваться в гонку вооружений с веб-спамерами и постоянно совершенствовать алгоритмы, чтобы получаемые ранги отражали реальное положение вещей. Стремление улучшить алгоритм PageRank дало многочисленным исследованиям в академических и промышленных кругах с целью найти иные алгоритмы, в которых гипертекстовая структура веб используется для ранжирования результатов. Подобные алгоритмы часто называют алгоритмами ссылочного ранжирования.

стр. 50

> Несмотря на многочисленные усложнения, характерные для современных поисковых систем, красивая идея, лежащая в основе алгоритма PageRank, - тот факт, что авторитетные страницы могут вносить вклад в авторитетность других страниц посредством гиперссылок, - остается в силе. Именно эта идея помогла Google свергнуть AltaVista с пьедестала и за несколько бурных лет превратить Google из небольшой начинающей компании в короля поиска. Без основополагающей идеи PageRank результаты большинства операций поиска в веб давали бы тысячи подходящих, но нерелевантных страниц. PageRank поистине алгоритмическая жемчужина, которая позволяет иголке подняться на самую вершину стога сена.

стр. 51

> #### Глава 4. Криптография с открытым ключом: отправка секретов почтовой открыткой
>
> Люди любят сплетничать. И секреты они тоже любят. А поскольку задача криптографии состоит в передаче секретов, все мы немного криптографы. Однако людям обменяться секретом проще, чем компьютерам. Если вы хотите сообщить секрет другу, можете просто пошептать ему на ушко. У компьютеров такой возможности нет. Компьютер не может «прошептать» номер кредитной карты другому компьютеру. Если два компьютера связаны через Интернет, то они не контролируют, куда попадет номер кредитной карты и какие ещё компьютеры могут им завладеть. … компьютеры обходят эту проблему, применяя одну из самых изобретательных идей информатики, оказавшую огромное влияние на нашу жизнь: криптографию с открытым ключом.

стр. 56

> На момент написания этой книги самым популярным блочным шифром был AES (Advanced Encryption Standard). Этот шифр можно использовать в разных режимах, но как правило берутся блоки по 16 символов, 128-битные ключи и 10 раундов операций перемешивания.
>
> … подавляющее большинство схем шифрования в Интернете работает так: разбивается сообщение на блоки и используется вариант трюка со сложением для шифрования каждого блока. Но, как выясняется, это самая простая часть. Проблема в том, как определить общий секрет. На первый взгляд, это невозможно, но оказывается, что есть остроумный способ решить задачу. В информатике это решение называют протоколом обмена ключами Диффи-Хеллмана. (Уитфилд Диффи и Мартин Хеллман впервые опубликовали этот алгоритм в 1976 году).

стр. 65

> Первая важная идея называется арифметикой часов. В общем-то, все мы с ней давно знакомы: на циферблате часов есть всего 12 делений, поэтому когда часовая стрелка пересекает 12, отсчёт начинается снова с 1. … В математике арифметика часов работает аналогично, но с двумя отличиями: (1) количество делений на циферблате может быть произвольным и (2) отсчёт начинается не с 1, а с 0.

стр. 66

> Вторая математическая идея – это степенная нотация. Тут ничего хитрого нет: это просто короткий способ записать несколько операций умножения числа на себя самого. Степенную нотацию можно сочетать с арифметикой часов.

стр. 73

> #### Глава 5. Коды, исправляющие ошибки: ошибки, которые исправляются сами собой
>
> … код исправляющий ошибки – алгоритм, который как по волшебству обнаруживает и исправляет ошибки в компьютерных данных.

стр. 74

> Компьютеры решают три фундаментальные задачи. Самая важная - вычисления. Это означает, что компьютеру подаются на вход какие-то данные, а он преобразовывает их для получения полезного ответа. Но умение вычислять ответы было бы практически бесполезно без двух других задач, решаемых компьютерами: хранение и передача данных. (Компьютеры хранят данные по большей части в памяти и на дисках. А передают их как правило через Интернет.)
>
> Но с передачей и хранением данных связана серьезнейшая проблема: данные должны быть абсолютно правильны - во многих случаях даже малейшая ошибка может сделать данные бесполезными.

стр. 75

> Основополагающий трюк, благодаря которому возможна надежная передача по ненадежному каналу, всем нам хорошо знаком: чтобы гарантировать правильную передачу информации, ее нужно передать несколько раз.

стр. 78

> Хотя в компьютерах трюк с повторением в том виде, в каком он описан выше, не используется, мы рассмотрели его первым, чтобы вы поняли общий принцип организации надежной связи. Принцип этот состоит в том, что одно исходное сообщение послать недостаточно, для повышения надежности нужно передать еще что-то. В случае трюка с повторением это «что-то» - дополнительные копии исходного сообщения. Но, как выясняется, повысить надежность можно, передавая и другие виды дополнительной информации, - и этих видов не так уж мало. В информатике эту дополнительную информацию называют «избыточностью». Иногда избыточность добавляется к исходному сообщению. С такой техникой «дописывания» мы познакомимся ниже, когда будем рассматривать трюк с контрольной суммой. Но сначала рассмотрим другой вид избыточности, когда исходное сообщение заменяется другим, более длинным - «избыточным». Получив более длинное сообщение, мы затем можем восстановить из него исходное, даже если в процессе передачи по плохому каналу оно было искажено. Эту технику мы будем называть трюком с избыточностью.

стр. 80

> Поясним еще раз, почему трюк с избыточностью предпочтительнее трюка с повторением. Основная причина - их сравнительная стоимость. В информатике стоимость схем исправления ошибок измеряют в терминах «накладных расходов», т. е. объема дополнительной информации, которую нужно передать, чтобы сообщение можно было принять правильно. Накладные расходы трюка с повторением огромны, поскольку приходится передавать полные копии сообщения. Накладные расходы трюка с избыточностью зависят от используемого набора кодовых слов. Но математики придумали наборы кодовых слов с гораздо меньшей избыточностью и при этом такие, что вероятность пропустить ошибку крайне мала. Низкие накладные расходы этих кодовых слов и есть та причина, по которой в компьютерах применяется трюк с избыточностью, а не с повторением.
>
> До сих пор мы во всех примерах предполагали использование кодов для передачи информации, но все сказанное равным образом относится и к задаче хранения информации. Чтобы обеспечить высочайшую надёжность, которую мы видим, CD, DVD и жесткие диски опираются на коды, исправляющие ошибки.

стр. 91

> В информатике трюк с указкой называется «двухмерным контролем чётности». Слово чётность означает то же самое, что простая контрольная сумма, но относится к двоичным числам, с которыми обычно работают компьютеры. А двухмерной она называется, потому что сообщение представлено в виде таблицы с двумя измерениями (строки и столбцы). Двухмерный контроль чётности раньше применялся в некоторых реальных компьютерных системах, но он не так эффективен, как некоторые другие трюки с избыточностью.

стр. 94

> #### Глава 6. Распознавание образов: обучение на опыте
>
> … распознавание образов можно определить более общо: заставить компьютеры действовать «разумно», исходя из входных данных, характеризуемых высокой изменчивостью.

стр. 95

> … появились кое-какие изобретательные алгоритмы, которые позволяют компьютерам добиваться хороших результатов при решении некоторых задач распознавания: классификаторы по ближайшим соседям, деревья решений и искусственные нейронные сети.

стр. 96

> Стандартный подход к распознаванию образов – рассматривать эту деятельность как задачу классификации. … Задача компьютера – обработать образцы данных, которые он никогда раньше не видел, и выполнить классификацию – отнести каждый образец к одному из возможных классов.

стр. 100

> В простейшей форме трюк с «ближайшим соседом» делает именно то, что сказано в названии. Получив неклассифицированный образец, мы первым делом ищем ближайший к нему классифицированный образец и в качестве предсказания берём класс этого образца.

стр. 101

> … эффективные системы распознавания образов, как правило, представляют собой сплав математического понимания, экспертной оценки и практического опыта.

стр. 104

> … при наличии достаточного количества обучающих данных, дерево решений можно научить выполнять точную классификацию.

стр. 106

> Для построения хорошей системы распознавания образов иногда требуется приложить немало ручного труда, но это одноразовые затраты, которые окупаются многократно.

стр. 107

> Этап обучения классификатора по дереву решений может быть сложным, но он полностью автоматический и выполняется только один раз. После этого мы получаем требуемое дерево решений, а этап классификации оказывается поразительно простым: как и в игре в двадцать вопросов, нужно спускаться вниз по дереву в зависимости от ответов на вопросы, пока не достигнем прямоугольника с окончательным решением. Как правило, хватает всего нескольких вопросов, так что этап классификации оказывается очень эффективным. Сравните с методом ближайшего соседа, когда на этапе обучения не пришлось прикладывать ни малейших усилий, зато на этапе классификации нужно было сравнивать предъявленный образец со всеми обучающими (а таких в случае задачи о рукописных цифрах 100000).

стр. 109

> Искусственная нейронная сеть – это компьютерная модель, описывающая крохотную часть мозга в очень упрощённом виде.

стр. 112

> … настройка нейронной сети производится автоматически путём обучения на примерах.

стр. 115

> … этап обучения нейронной сети – достаточно длительный процесс, в котором многократно корректируются все веса и пороги, пока сеть не станет показывать хорошие результаты на обучающих образцах. Однако всё это может автоматически сделать компьютер, а в результате получится сеть, которую можно будет использовать для классификации новых образцов простым и эффективным способом.

стр. 117

> … один из важных уроков, который получили исследователи, изучающие искусственный интеллект в течение нескольких последних десятилетий: псевдоразумное поведение может проявиться в системах, кажущихся случайными.

стр. 121

> Глава 7. Сжатие данных: кое-что задаром.
>
> … компьютерные файлы и другие данные можно сжать, уменьшив размер для удобства хранения и транспортировки. Позже их можно распаковать и использовать в исходном виде.
>
> Например, многие сообщения, передаваемые через Интернет, сжимаются без ведома пользователя, и почти всё скачиваемое программное обеспечение представлено в сжатом виде, благодаря чему на передачу файлов уходит в несколько раз меньше времени.

стр. 122

> Важно понимать, что есть два очень разных вида сжатия: без потери и с потерей информации. Сжатие без потери информации - это самый что ни на есть бесплатный сыр, когда вы действительно получаете кое-что задаром. Алгоритм сжатия без потери информации получает на входе файл, сжимает его в несколько раз, а затем распаковывает, получая в точности исходный файл. Напротив, в случае сжатия с потерей информации файл, получающийся после распаковки, немного отличается от исходного. Но хочется предостеречь вас от чрезмерных восторгов при виде бесплатного сыра: алгоритмы сжатия без потери информации дают впечатляющее уменьшение размера отнюдь не для всех файлов. Однако хороший алгоритм сжатия может существенно уменьшить размеры файлов большинства часто встречающихся типов.

стр. 127

> … преобразование между числовыми кодами и знаками должно быть однозначным, даже если коды хранятся подряд, без каких-либо разделителей.

стр. 131

> … иногда гораздо полезнее сжатие с потерей информации, при котором восстановленный файл оказывается очень похож на исходный, но может не совпадать с ним в точности.

стр. 132

> Простой и полезный трюк, применяемый для сжатия с потерей информации, - пропустить часть данных.

стр. 137

> Хороший алгоритм сжатия устраняет неэффективную избыточность, а кодирование с целью исправления ошибок добавляет другую, более эффективную избыточность. Таким образом, часто сообщение сначала сжимают, а потом добавляют в него данные для исправления ошибок.

стр. 139

> #### Глава 8. Базы данных: в поисках непротиворечивости
>
> … все онлайновые сделки обрабатываются с помощью изощренных баз данных, разработанных учёными с 1970-х годов.
>
> Базы данных отвечают за два важнейших аспекта обработки сделок: эффективность и надёжность. Эффективность обеспечивается алгоритмами, которые дают тысячам клиентов возможность одновременно совершать сделки, не опасаясь конфликтов или противоречий. А надёжность - алгоритмами, благодаря которым данные не пропадают даже в случае поломки дисков компьютера, хотя обычно это приводит к масштабной потере данных. Онлайновый банкинг - канонический пример приложения, которое должно быть исключительно эффективным (чтобы обслуживать одновременно много пользователей без ошибок и не создавая противоречий) и стопроцентно надёжным. 
>
> … три фундаментальных - и очень красивых - идеи, лежащих в основе баз данных: упреждающая запись в журнал, двухфазная фиксация и реляционные базы данных. Благодаря этим идеям базы данных стали доминирующей технологией хранения важной информации определенного вида.

стр. 141

> Противоречия - худший из кошмаров администратора баз данных.

стр. 142

> Транзакции – пожалуй, самая важная идея в мире баз данных.

стр. 145

> … учёные ввели понятие «транзакции» - набора изменений базы данных, которые должны произойти все вместе, чтобы база данных оставалась непротиворечивой.

стр. 146

> Не все мы умеем чётко организовывать свою жизнь. Но повезло нам и этом отношении или нет, все мы знакомы с орудием, которым пользуются организованные люди: списком предстоящих дел. Даже если лично вам вести такой список не нравится, возражать против его полезности трудно. Если за день нужно сделать 10 дел, то начать стоит с того, чтобы их записать - и лучше бы в порядке, гарантирующем эффективность. Список дел особенно полезен, если вам случается на что-то отвлечься (не сказать ли - «в случае сбоя»?) посередь дня. Если вы по какой-то причине забудете, что осталось сделать, то достаточного беглого взгляда на список, чтобы освежить память.
>
> Транзакции баз данных - это тоже особого рода список дел. Потому-то мы и говорим о трюке со списком дел, хотя специалисты по информатике применяют термин «упреждающая запись в журнал».

стр. 147

> Основная идея заключается в том, чтобы вести журнал действий, которые базе данных предстоит выполнить. Журнал хранится на жестком диске или на каком-нибудь другом постоянном запоминающем устройстве, поэтому информация не пропадает после сбоя и перезапуска. Все операции, входящие в состав транзакции, сначала записываются в журнал и, стало быть, сохраняются на диске и только потом исполняются. Если транзакция завершается успешно, то можно удалить связанный с ней список дел из журнала и тем самым сэкономить место.

стр. 160

> В терминологии баз данных любой столбец, по которому можно «поискать» детальную информацию, называется ключом.

стр. 161

> Красота подобного использования ключей заключается в том, что поиск в базе по ключу можно производить очень эффективно. Делается это так же, как при поиске слова в словаре.

стр. 162

> Множество заранее вычисленных групп страниц для быстрого поиска по ключу в информатике называется В-деревом. Это ещё одна остроумная идея, играющая огромную роль в современных базах данных.

стр. 167

> #### Глава 9. Цифровые подписи: кто на самом деле написал эту программу?
>
> Из всех идей, с которыми мы встретились в этой книге, концепция «цифровой подписи», пожалуй, самая парадоксальная. Если понимать буквально, то слово «цифровой» означает «состоящий из ряда цифр». Но, по самому своему определению, такой объект можно скопировать: достаточно просто копировать одну цифру за другой. Если можно прочитать, то можно и скопировать! С другой стороны, весь смысл «подписи» состоит в том, что прочитать ее можно, а скопировать (то есть подделать) не может никто, кроме автора. 

стр. 184

> … схема со степенными замками и ключами называется цифровой подписью RSA по именам изобретателей (Рональд Райвест, Ади Шамир, Леонард Адлеман), которые опубликовали её в 1970-х годах.

стр. 192

> #### Глава 10. Что можно вычислить?
>
> Сколь бы изощрённые алгоритмы ни изобретали будущие исследователи, всегда будут существовать задачи, ответ на которые невозможно «вычислить».

стр. 196

> В более абстрактных терминах доказательство от противного можно описать следующим образом. Допустим, мы подозреваем, что некоторое утверждение S ложно, но хотели бы доказать это неопровержимо. Сначала мы предполагаем, что S истинно. Применяя какое-то рассуждение, мы устанавливаем, что некое другое утверждение Т тоже должно быть истинно. Если, однако, известно, что Т ложно, то мы пришли к противоречию. Это доказывает, что исходное утверждение (S) обязано быть ложным. Математик сказал бы более кратко: «из S следует Т, но Т ложно, следовательно, S тоже ложно». Вот в этом и состоит суть доказательства от противного.



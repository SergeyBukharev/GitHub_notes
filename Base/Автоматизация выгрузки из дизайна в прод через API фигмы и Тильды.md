---
aliases:
---
2021-21-11 | 00:58
tags: 
___

# Автоматизация выгрузки из дизайна в прод через API фигмы и Тильды

![[Pasted image 20211121005812.png]]


Дизайн ориентированные идеи для Тильды. Или чего мне не хватает для счастья?

— Подсасывания адаптивных фреймов (названия и кол-во блоков должно быть идентичным десктопу, тк у тильды по умолчанию включена) под адаптивку.
— Создания html блока с динамически обновляемыми текстовыми данными из фигмовских таблиц [Такие группы слоёв должны начинаться с TABLE в названии, чтобы тильда автоматически формировала из кода фигмы код для динамического блок на Тильде]
— Импорт с учётом тёмной и светлой темы — то бишь, импорт страниц (Dark и Light) с импортом внутренних фреймов, у которых следущая градация по сетке: 1920px - 1024px - 768px - 320px 

— Идея для подсасывания стандартных блоков. Кстати, Тильда. Может уже добавите к своим стандартным блокам фигменские проекты, чтобы можно было подсасывать их без этого пердолинга с текстом.

Это же возможно сделать всё через апишку фигмы. Странно, почему никто об этом не пишет. Это от какого кол-ва пердролинга двигания блоков под адаптивку можно избавиться. У меня, например, для подстраивания одной только страницы уходит около 30-180 минут в зависимости от присутствия анимации и сложности макета. А теперь перемножьте время на каждую страницы на 100 страниц, например. В итоге получим от 50 до 300 ЧАСОВ на редактирование ста уникальных страниц. Пиздец. С автообновляемыми макетами из фигмы можно получить лишние 50-300 часов времени на проверку новых гипотез или АБ-тестики, например. Ну или чем там занимаются продуктовые дизайнеры.

Кстати, в документации можно сделать пометку о том, что все страницы без нужного названия просто игнорируются. Это можно сделать, чтобы тильда не экспортировала дизайн-систему, например, или другую корпоративную информацию.

Я уж не говорю про имопрт взаимо...

— Импорт взаимодействия из прототипа (для этого надо указывать отдельную ссылку на прототип, либо добавить чекбокс на прототип)

Прост прикиньте, указываете ссылку и тильда формирует целый сайт из вашего файла в фигме, с учётом актуальных данных из таблиц и автообновлением через интерфейс своего плагина, например. В плагине так же можно настроить скорость автообновления (60 мин минимум - для защиты от сильных нагрузок на сервера).
А защитить всё это можно загрузкой через api key, который формирует сама фигма.

И ещё. идея. Но уже больше для фигмы. Жду недождусь, когда можно будет убрать UI с ifram'a, который формирует фигма и добавить больше возможностей для настройки этого фрейма. Например настройки проверки айдишника из хэда на тильде. Аналогичная проверка применяется, когда хочешь добавить счётчик я.метрики на сайт. Думаю, вы и так поняли. :)

Есть правда две проблемки. Заключается она в вариантах и наименовании слоёв под адаптивку. Для этого скорее всего в документации придётся вводить свои правила и добавлять инструкцию для дизайнеров, чтобы тильда могла сопоставить картинки и другой контент с исходным. Например для того чтобы сделать так — пример 
Надо:
а) Надо сменить в компоненте название на размер девайса например сделать из [BUTTON_HOVER_Desktop-1920px] — [BUTTON_HOVER_Mobile-320px]. 
б) Сделать стандартом единую систему наименований для компонентов в дизайн-системах для корректной выгрузки макетов.

Ну а дальше уже можно интегрировать страницы из тильды, куда-нибудь в другие CMSки по типу того же Битрикса или WP.

Понятно, что для создания сверхфункциональных сложных сервисов надо прибегать уже к другим фреймворкам, CMSкам и библиотекам.

Ну и по классике 
Посмотреть прототипы гипотез. Чтобы поменять сценарий выберете необходимый из сайдбара.

Были ещё гипотезы, но их сложно проверить без доступа к системе, что называется со стороны бекэнда. Ну тут уж извините. Мои полномочия всё. Можете взять гипотезы в свой беклог, а можете не брать. Моё дело — предложить.

___
### Links
- 

___
### Base-links
-


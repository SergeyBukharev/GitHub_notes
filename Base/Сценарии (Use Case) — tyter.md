---
aliases:
---
2021-20-06 | 22:32
tags: 
___

# Сценарии (Use Case) — tyter

## Шаблон для гипотезы
* Что тестируем?
Какой процесс проходит пользователь, чтобы прийти к результату (цели/выполнению работы)?

* Контекст
Технический: веб/мобайл/другое устройство. 
Социальный: Где происходит и при каких обстоятельствах? 

* Цель пользователя под конец сценария? Зачем ему это?
(Во всём контексте / В микросценарии)

* Цель (Проставляется после тестирования)
Достигнута / Не достигнута

* На выходе — блок-схема (Я-вопросы / Я-действия для экрана) и кликабельный прототип.
[use case 1 — tyter]()

---
## 1 Сценарий — Создание нового проекта
* Что тестируем?
Регистрация и создание нового проекта.
Сможет ли пользователь создать новый проект и написать для него перую сцену.

* Контекст.
Пользователь уже зарегестрирован и аторизован в системе. У него нет проектов.

* Цель пользователя под конец сценария
Создан новый проект, сцена написана.

---
## 2 Сценарий  — предоставление доступа к персонажам и локациям (Доступно только для Pro?)
* Что тестируем?
Возможность поделиться бибилиотекой компонентов с другими участниками команды.

* Контекст
Пользователю написали по почте, чтобы он расшарил библиотеку персонажей и локаций (далее компоненты) другим участниками команды. Пользователь уже авторизован в системе и находится на странице проектов. У него есть готовый проект с персонажами и локациями.

* Цель пользователя под конец сценария
Персонажи отправлены другим участникам команды + отправлены уведомления по почте.

Участники: 
Пользователь (П)
Система (С)

Сценарий:
1. (П) открывает проект, в котором есть библиотеки.
2. (П) нажимает на кнопку «Инструменты».
3. (П) переходит на вкладку компоненты компоненты. 
4. (П) нажимает на иконку «Библиотеки».
5. (С) Открывается модальное окно библиотек.
	1. Если пользователь открывает бибилиотеку первый раз, С рассказывает о библиотеках и как ими пользоваться.



---

## 3 Сценарий — Раскадровки — создание проекта
* Что тестируем?
Создание раскадровки.

- Способ первый. 
Добавление раскадровки в тело сценария

- Способ второй
Добавление раскадровик как отдельного проекта




---

## 4 Сценрий — Добавление персонажей
* Что текстируем?
Добавление нового персонажа в библиотеку компонентов через текст или через боковую панель.

---

## 5 Сценарий — Комментирование
* Что тестируем?
Добавление комментариев в тексте, раскадровках и к персонажу.

* Контекст
Пользователю доступен только просмотр и комментирование текста.

* Цель пользователя под конец сценария
Пользователь добавил комментарии. Создателю проекта на почту пришло уведомление о новых комментариях.

---

## 6 Сценрий — преддективный ввод
* Что тестируем?
Сможет ли пользователь написать сцену с помощью горячих клавиш.

---

## 7 Сценарий —  создание команды и добавление участников в команду




___
### Links
- 

___
### Base-links
- [[Tyter — приложение для создания историй]]


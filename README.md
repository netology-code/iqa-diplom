# Курсовой проект к модулю «Ручное тестирование веб-приложений»

Перед вами курсовой проект по модулю «Введение в тестирование». Он содержит задания, которые помогут ещё раз отработать полученные знания и вспомнить теорию. У этого задания более высокий уровень сложности, чем у предыдущих домашних заданий, но оно позволит вам погрузиться в процессы, которые ожидают вас при устройстве на работу и при выполнении рабочих задач.

## Правила выполнения курсового проекта

1. Объект тестирования: интернет-магазин https://henderson.ru. **Важно:** это реальный сайт, не тестовый, поэтому не надо совершать на нём покупки и прочие подобные действия. При возникновении вопросов по работе сайта и связанным проблемам писать надо вашему курсовому руководителю, а не представителям сайта.
1. Скопируйте шаблон таблицы на свой Google Диск [здесь](https://u.netology.ru/backend/uploads/lms/content_assets/file/991/IQA_Diploma_Name_Surname_Group.xlsx), укажите в названии файла свои фамилию, имя и группу вместо Name, Surname, Group. Ссылка на эту сводную таблицу и будет ссылкой, которую вы будете прикреплять при сдаче курсовой.
1. Проверьте настройки доступа — необходимо, чтобы в ваших документах и таблицах была открыта возможность комментировать всем пользователям в интернете, кому предоставлена ссылка.
1. В предоставленном шаблоне есть все шаблоны, которые нужны для выполнения задания.
1. В своей таблице прикрепляйте ссылки на выполненную работу по каждому заданию.
1. Все таблицы должны быть отформатированы с переносами и правильной вёрсткой, иначе они будут возвращены на доработку. Пример можно увидеть [тут](https://u.netology.ru/backend/uploads/lms/content_assets/file/992/%D0%A4%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86.docx).
3. Вам необходимо выполнить пять заданий, кроме заданий со звёздочкой (задания 3.2.* и 2.2.* выполняются по желанию). Не полностью выполненное или не полностью доработанное задание на проверку не принимается.
4. Когда выполните все пять заданий, прикрепите в личном кабинете ссылку на свою таблицу с решениями и ожидайте проверки преподавателя.
5. Курсовой проект считается принятым, когда все пять заданий (кроме заданий 3.2.* 2.2.*) приняты преподавателем.
6. Если вам вернули курсовую на доработку:
- для заданий 1, 2.1., 3.1. доработанную версию надо создать на новом листе в изначальной таблице. Для этого мы [переименовываем](https://u.netology.ru/backend/uploads/lms/content_assets/file/993/Screenshot_at_Jul_20_10-10-59.png) уже существующий лист в «ДЗ Версия 1», создаём новый через [дублирование](https://u.netology.ru/backend/uploads/lms/content_assets/file/994/%D0%91%D0%B5%D0%B7_%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.png), новый лист переименовываем в «ДЗ Версия 2» и выполняем доработки уже в нём. Аналогично для доработок после второй;
- для остальных заданий добавляем новую информацию в старом файле или так, как будет согласовано с проверяющим преподавателем;
- доработка по курсовому проекту отправляется студентом и проверяется преподавателем только после доработки всех необходимых пунктов.

## Задание 1

Написать чеклист для функциональной проверки [личного кабинета зарегистрированного авторизованного пользователя](https://henderson.ru/cabinet/), включая функционал разделов, на сайте https://henderson.ru/.

**Требования к выполнению**
* Чеклист должен представлять собой структурированный многоуровневый список, который содержит набор функциональных позитивных и негативных проверок клиентской стороны компонентов объекта тестирования.
* Каждый пункт проверки в должен быть в отдельной ячейке списка и со своим приоритетом.
* При составлении списка проверок должны учитываться различные варианты состояний страниц. Например, при проверке функции «Мои отзывы» мы проверяем не только состояние без отзывов, но и с ними.
* Мы ожидаем от вас список проверок функционала личного кабинета без учёта хедера и футера страницы, то есть то, что есть в этой [области](https://u.netology.ru/backend/uploads/lms/content_assets/file/995/%D0%91%D0%B5%D0%B7_%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F__1_.png).

## Задание 2

2.1. Необходимо написать набор тест-кейсов на проверку функционала авторизации (входа) на сайте Хендерсон с главной страницы. Обратите внимание, что проверки должны покрывать как позитивные, так и негативные проверки, а также при написании тестов вам нужно использовать изученные практики тест-дизайна. Проверки должны быть атомарными, а также учитывать проверку процесса авторизации от начала до конца. Помните, что задача - в первую очередь проверить функциональность, а не верстку.
Ваша задача — написать минимум 10 тест-кейсов.


2.2.* Разработчики решили в будущем добавить новую функциональность на сайт, но пока у нас в распоряжении есть только техническое задание, оно же - требования. Пока они недоработаны, но мы уже можем начать процесс тестрования требований. [ссылке](https://u.netology.ru/backend/uploads/lms/content_assets/file/996/%D0%9F%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D1%81%D0%BA%D0%B8%D0%B9_%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B9_%D0%BF%D0%BE_%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D1%83_%D0%B2%D0%BE%D1%81%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BF%D0%B0%D1%80%D0%BE%D0%BB%D1%8F_%D0%BD%D0%B0_%D1%81%D0%B0%D0%B9%D1%82%D0%B5_henderson.docx) Напишите свои вопросы по этим требованиям. Они могут касаться не описанных, но важных сценариев, граничных значений и подобных проблем, по аналогии с ДЗ.

## Задание 3

3.1. На основе [скриншота](https://u.netology.ru/backend/uploads/lms/content_assets/file/997/%D0%91%D0%B5%D0%B7_%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F__2_.png) создайте не менее трёх баг-репортов. Обратите внимание, что здесь в окружении мы можем описать тот браузер, с которого проводилась бы проверка, то есть ваш актуальный.

3.2.* Найдите баг в функции «Написать отзыв» в карточке товара и составьте на него баг-репорт. Если найдёте несколько — замечательно!

## Задание 4

Вы тестируете страницу карточки товара. Из ТЗ вы знаете, что товар может стоить от 1 рубля до 10 000 000 рублей. К сожалению, на сайте сейчас товаров с такой ценой нет, а разработчик бэкенда в отпуске, поэтому вам нужно протестировать вёрстку страницы карточки товара с максимальной и минимальной ценой самостоятельно.
Ваша задача — самостоятельно определить, как проще это сделать, и предоставить решение в виде скриншотов страницы карточки товара с минимальной и максимальной ценой. Важно, чтобы было видно, с помощью чего вы изменили эту цену.

## Задание 5

Менеджеру нашего проекта срочно надо узнать, что содержится в Preview запроса, в котором мы получаем информацию о странах при загрузке главной страницы сайта Henderson. Фронтенд-разработчик ушёл в отпуск в поход без связи, а документация пропала.

Известно, что найти эту информацию можно в данных, которые уходят в GET запросе по адресу, который содержит в себе GetCountries. 

Ваша задача — изучить ответы и запросы при работе с сайтом, найти запрос, в котором есть нужные параметры, найти, как же выглядит Preview, и приложить скриншот искомой информации в таблицу с решениями.

Обратите внимание, что задание надо выполнять с выключенным VPN и выключенными блокировщиками рекламы.

### Как правильно задавать вопросы преподавателю

Что поможет решить большинство частых проблем:

1. Попробуйте найти ответ сначала самостоятельно в интернете или в материалах курса и только после этого спрашивать у преподавателя. Навык поиска ответов пригодится вам в профессиональной деятельности.
1. Если вопросов больше одного, то присылайте их в виде нумерованного списка. Так преподавателю будет проще отвечать на каждый из них. 
1. При необходимости прикрепите к вопросу скриншоты и стрелочкой покажите, где не получается. 

Что может стать источником проблем:

1. Вопросы вида «Ничего не работает. Не запускается. Всё сломалось». Преподаватель не сможет ответить на такой вопрос без дополнительных уточнений. Цените своё время и время других.
2. Откладывание выполнения курсового проекта на последний момент.
3. Ожидание моментального ответа на свой вопрос. Преподаватели — работающие QA, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы :)

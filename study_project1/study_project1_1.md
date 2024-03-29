# Тестирование функционала личного кабинета крупного интернет-магазина. Чек-листы, тест-кейсы, баг-репорты, работа с DevTools

[Курсовой проект. Задания](https://github.com/YashmetovYury/all-for-study-testing/blob/a8826f5a5fa7ee92808f1ab04a22ae3945dd2b82/study_project1/study_project1.md)
## Задание 1

Написать **чек-лист** для функциональной проверки личного кабинета зарегистированного авторизованного пользователя (включая функционал разделов) на сайте https://henderson.ru/.

**Требования к выполнению:**

* Чек-лист должен представлять собой структурированный (многоуровневый) список, который содержит набор функциональных позитивных и негативных проверок клиентской стороны компонентов объекта тестирования.
* Каждый пункт проверки в данном случае должен быть в отдельной ячейке списка и со своим приоритетом.
* При составлении списка проверок должны учитываться различные варианты состояний страниц. Например, при проверке функционала "Мои отзывы" мы проверяем не только состояние без отзывов, но и с ними.
* Мы ожидаем от вас список проверок функционала личного кабинета без учета хедера и футера страницы.

**[РЕШЕНИЕ. ЧЕК-ЛИСТ.](https://docs.google.com/spreadsheets/d/1a32UU8CHF4Rx8i-189s2_uRyLRiZiOsYO0BpPqR0mck/edit?usp=sharing)**
**[РЕШЕНИЕ. ЧЕК-ЛИСТ.](https://docs.google.com/spreadsheets/d/1qMIOMTjThoQWSG8t2lTuN269WuSP-lP3cQuaoYDBW_Q/edit#gid=1798737482)**

## Задание 2

Необходимо написать **набор тест-кейсов** на проверку функционала восстановления пароля.

Ваша задача - написать минимум 20 тест-кейсов, которые должны покрывать все, что описано в требованиях по ссылке, и учитывать позитивные и негативные кейсы и включать в себя полные циклы восстановления пароля. Помните, что мы проверяем не только и не столько саму форму, но процесс восстановления с применением техник тест-дизайна. Обратите внимание, что основа для написания тестов - информация в требованиях, а не на реальном сайте + не все требования могут быть реализованы в реальном сайте на данный момент.

**[РЕШЕНИЕ. ТЕСТОВЫЕ СЦЕНАРИИ.](https://docs.google.com/spreadsheets/d/125NCSt68zSBBIj1GR3knAbMKlnoIrtLoQ1zPU2_lga0/edit?usp=sharing)**

## Задание 3

3.1.
На основе [скриншота](https://drive.google.com/file/d/1cmC0wWP1vQdWl40FtdpRJ9-eCEX6cDYL/view?usp=sharing) создать не менее трех **баг-репортов**. Обратите внимание, что в данном случае, в окружении мы можем описать тот браузер, с которого проводилась бы проверка, т.е ваш актуальный браузер.

**[РЕШЕНИЕ. БАГ-РЕПОРТЫ.](https://docs.google.com/spreadsheets/d/10BTXXmRz9gz2tzEDZxTsgWNr7dvYVPJf0Gj9rnppkII/edit?usp=sharing)**


## Задание 4

Вы тестируете страницу карточки товара. Из ТЗ вы знаете, что товар может стоить от 1 рубля до 10 000 000 рублей. К сожалению, на сайте в данный момент товаров с такой ценой нет, а разработчик бекенда в отпуске, поэтому вам нужно **протестировать верстку страницы карточки товара с максимальной и минимальной ценой** самостоятельно. Ваша задача - самостоятельно определить, как проще это реализовать, и предоставить решение в виде скриншотов страницы (чтобы было видно, с помощью чего вы изменили эту цену) карточки товара с минимальной и максимальной ценой товара.

**РЕШЕНИИЕ:**
* Минимальная цена 1 р. 

![2022-06-07_16-29-08](https://user-images.githubusercontent.com/82056292/181476317-1ece7d21-9f87-42df-a610-a4d57e21e719.png)


* Максимальная цена 10 000 000 р. 

![2022-06-07_16-27-27](https://user-images.githubusercontent.com/82056292/181476423-ceffac6a-497e-4b66-8118-2344099e0bc7.png)


## Задание 5
Бекенд разработчик говорит, что мы отправляем данные с сайта в неправильном формате и просит вас помочь найти нужный запрос. Фронтенд разработчик ушел в отпуск в поход без связи, а документация пропала.

Известно, что проблема в данных, которые уходят в post запросе по адресу api.mindbox.ru/v3/js/operations/, и происходит это скорее всего при работе с личными данными пользователя (например авторизация, личный кабинет, просмотр корзины).

Ваша задача - **изучить ответы и запросы при работе с сайтом; найти, как же выглядят параметры deviceUUID, requestId и status**, и приложить скриншот искомого превью в таблицу с решениями.

**РЕШЕНИИЕ:**

![2022-06-07_17-46-11](https://user-images.githubusercontent.com/82056292/181476153-05ccef9a-3a09-4971-8998-d31100404c40.png)

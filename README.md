Заголовки
=======
                          

# H1
## H2
### H3
#### H4
##### H5
###### H6

Кроме того, H1 и H2 можно обозначить подчеркиванием:

Alt-H1
======

Alt-H2
------

Выделение
=========


Курсив обозначается *звездочками* или _подчеркиванием_.

Полужирный шрифт - двойными **звездочками** или __подчеркиванием__.

Комбинированное выделение **звездочками и _подчеркиванием_**.

Для зачеркнутого текста используются две тильды . ~~Уберите это.~~


Списки
========
1. Первый пункт нумерованного списка
2. Второй пункт
⋅⋅*Ненумерованный вложенный список.
1. Сами числа не имеют значения, лишь бы это были цифры
⋅⋅1. Нумерованный вложенный список
4. И еще один пункт.

⋅⋅⋅Внутри пунктов списка можно вставить абзацы с таким же отступом. Обратите внимание на пустую строку выше и на пробелы в начале (нужен по меньшей мере один, но здесь мы добавили три, чтобы также выровнять необработанный Markdown).

⋅⋅⋅Чтобы вставить разрыв строки, но не начинать новый параграф, нужно добавить два пробела перед новой строкой.⋅⋅
⋅⋅⋅Этот текст начинается с новой строки, но находится в том же абзаце.⋅⋅
⋅⋅⋅(В некоторых обработчиках, например на Github, пробелы в начале новой строки не нужны.)

* Ненумерованный список можно размечать звездочками
- Или минусами
+ Или плюсами

Ссылки
=======
[Обычная ссылка в строке](https://www.google.com)

[Обычная ссылка с title](https://www.google.com "Сайт Google")

[Ссылка со сноской][Произвольный регистронезависимый текст]

[Относительная ссылка на документ](../blob/master/LICENSE)

[Для ссылок со сноской можно использовать цифры][1]

Или можно просто вставить ссылку в квадратные скобки [текст ссылки]

Произвольный текст, после которого можно привести ссылки.

[произвольный регистронезависимый текст]: https://www.mozilla.org
[1]: http://slashdot.org
[текст ссылки]: http://www.reddit.com

Изображения
===========

Вот наш логотип (наведите указатель, чтобы увидеть текст заголовка):

Внутри строки:  
![alt-текст](https://w7.pngwing.com/pngs/446/964/png-transparent-butterfly-blue-morpho-menelaus-butterfly-blue-blue-and-white-butterfly-illustration-blue-brush-footed-butterfly-symmetry-thumbnail.png "Текст заголовка логотипа 1")

В сноске:  
![alt-текст][logo]

[logo]: https://w7.pngwing.com/pngs/446/964/png-transparent-butterfly-blue-morpho-menelaus-butterfly-blue-blue-and-white-butterfly-illustration-blue-brush-footed-butterfly-symmetry-thumbnail.png "Текст заголовка логотипа 2"

Таблицы
========
В оригинальном Markdown нет разметки для таблиц, но есть в GitHub Flavored Markdown.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Можно управлять выравниванием столбцов используя символ двоеточия. Ещё можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

| Left-Aligned  | Center Aligned  |      Right Aligned    |
|:------------- |:---------------:| ---------------------:|
| Content Cell  | Content Cell    | **bold**              |
| Content Cell  | Content Cell    | ~~strikethrough~~     |
| Content Cell  | Content Cell    | [link](https://ya.ru) |



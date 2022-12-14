# Введение в контроль версий и Markdown

![Логотип](markdown--v2.png "Markdown")

**Markdown** — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).

Его разработчик **Джон Грубер** так описал цель его создания:
>Основная цель разработки синтаксиса форматирования Markdown - сделать его максимально читаемым. Идея состоит в том, что отформатированный с помощью Markdown документ должен быть опубликован как есть, как обычный текст, и не должен выглядеть так, как будто он размечен тегами или инструкциями по форматированию.

## Форматирование текста

Для обозначения курсива необходимо с двух сторон текста поставить \* или \_ - *Курсив* & _Курсив_

Для обозначения полужирного текста необходимо с двух сторон поставить \*\* или \_\_ - **Полужирный** & __Полужирный__

Для зачеркнутого текста поставить двойную тильду \~~ - ~~Зачеркнут~~ 

Разные варианты необходимы, чтобы например *среди курсивного шрифта какие-то слова __выделять полужирным.__*

Обратный слэш необходим, чтобы показать спецсимволы как обычные символы.

## Составление списков

Для составления нумерованных списков необходимо поставить номер с точкой вначале. Вложенные списки отделяются табуляцией. Например:

1. Первый пункт
    1. Вложенный первый
    2. Вложенный второй
2. Второй пункт

**!Обратить внимание**: Нельзя нумеровать 1.1 и т.д.

Для составления ненумерованных списков необходимо поставить звездочку \*, дефис - или плюс + вначале:
* Первый пункт
    * Вложенный пункт
* Второй пункт
* Третий пункт
- Четвертый пункт
+ Пятый пункт

**!Обратить внимание**: Использование разных символов начала списка отделяет один список от другого.

## Список литературы

1. [Wikipedia](https://ru.wikipedia.org/wiki/Markdown "Markdown")
2. [Руководство по оформлению](https://gist.github.com/Jekins/2bf2d0638163f1294637 "github")
# Инструкция для работы с Markdown 

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или (_) Например, *вот так*, или _вот так_.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_. 

#  _**Добавить информацию по остальным разделам!**_ 

Чтобы выделить текст полужирным, необходимо обрамить его двумя звездочками (**).

### Списки

Чтобы выделить нумерованный список необходимо

1. Первый пункт
2. Второй пункт 

Для разметки неупорядоченных списков можно использовать или `*`, или `-`, или `+`:

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*). 
Например, вот так:

* Элемент 1
* Элемент 2
* Элемент 3

На самом деле не важно как в коде пронумерованы пункты, главное, чтобы перед элементом списка стояла цифра (любая) с точкой. Можно сделать и так:

0. элемент 1
0. элемент 2
0. элемент 3
0. элемент 4

Вложенные пункты создаются четырьмя пробелами перед маркером пункта:

* элемент 1
* элемент 2
    * вложенный элемент 2.1
    * вложенный элемент 2.2
* элемент ...

## Список с абзацами: 

* Раз абзац. Lorem ipsum dolor sit amet, consectetur adipisicing elit.
* Два абзац. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.
* Три абзац. Ea, quis, alias nobis porro quos laborum minus sed fuga odio dolore natus quas cum enim necessitatibus magni provident non saepe sequi?
    Четыре абзац (Четыре пробела в начале или один tab).

# Изображения

Чтобы вставить изображение в текст, достаточно написать следующее: ![]() 

Например:

![Привет, это ЗК!](koleos.jpg)


## Работа с таблицами

## Цитаты

**Цитаты оформляются как в емейлах, с помощью символа `>`.**

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

**Или более ленивым способом, когда знак `>` ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:**

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

**В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:**

> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");

### Исходный код

    В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

    Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```
    Самое приятное, что в коде не нужно заменять угловые скобки `< >` и амперсанд `&` на их html-сущности.

### Инлайн код



## Ссылки

## Команды

## Заголовки

Заголовки отмечаются диезом `#` в начале строки, от одного до шести. Например:

# Заголовок первого уровня #

## Заголовок h2

### Заголовок h3

#### Заголовок h4

##### Заголовок h5

###### Заголовок h6

В декоративных целях заголовки можно «закрывать» с обратной стороны.









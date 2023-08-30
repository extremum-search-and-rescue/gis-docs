---
title: Название страницы <!--Отображается в Title страницы, заголовке H1 и меню навигации-->
date: 2023-08-29 <!--Дата создания страницы, служит для сортировки ссылок в меню навигации-->
layout: post <!--Выбор шаблона для страницы, не меняем, используем стандартный-->
redirect_from: <!--В случае, если нужно настроить переадресацию с устаревших страниц-->
  - 111.html
  - 222.html
  - 333.html
---

## Заголовок H2 <!--Отображается в меню навигации-->
### Заголовок H3 <!--Отображается в меню навигации-->
#### Заголовок H4
##### Заголовок H5
###### Заголовок H6

*Italic*

**Bold**

[Текст гиперссылки](https://help.gis.extremum.org) <!--Добавление гиперссылки-->

![Описание картинки - alt](/assets/images/111.png) <!--Добавление картинки <img>-->

> Простейшая подсказка

> ##### Подсказка с заголовком
> И текстом

> ##### Подсказка с заголовком
> И текстом на зеленом фоне
{: .block-tip }

> ##### Подсказка с заголовком
> И текстом на желтом фоне
{: .block-warning }

> ##### Подсказка с заголовком
> И текстом на красном фоне
{: .block-danger }

<!--Таблица, корректно работающая на мобильных устройствах. Перевод строки после открывающего div и до закрывающего обязателен.-->
<div class="table-wrapper" markdown="block">

|title1|title2|title3|title4|title5|title6|title7|title8|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|

</div>

```markdown
Для отображения текста с кнопкой копирования в буфер (например, кода, который не должен быть обработан)
```
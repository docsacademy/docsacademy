---
title: "Заголовки и абзацы"
date: 2023-01-28T11:02:05+06:00
lastmod: 2023-01-28T10:42:26+06:00
weight: 4
draft: false
# search related keywords
keywords: ["заголовок"]
---

#### Заголовки - хэш-символы

В Markdown существует два способа маркировки заголовков:

При помощи хэш-символа # в начале строки. Количество хэш-символов может быть от одного до шести и соответствует
уровню заголовков от H1 до H6 в HTML. Например, один хэш-символ используется для заголовка первого уровня H1,
два хэш-символа для заголовка второго уровня H2 и т.д.

![Заголовки - хэш-символы](/images/Markdown/markdown-h1-to-h2-hashtag.png)

Помимо хэш-символов в начале строки, можно также добавить хэш-символы после текста. Количество хэш-символов в конце
строки может не соответствовать количеству хэш-меток в начале строки. Хэш-символы в конце строки не влияют на
форматирование текста и используются “для красоты”.

#### Заголовки - знаки равно и пунктиры

Другой вариант предусматривает подчеркивание заголовка символами “=” (знак равно) или “-” (пунктир). Данный способ
работает только для создания заголовков первого и второго уровня. При этом можно использоваться любое количество
подчеркиваний символами “=” (заголовок первого уровня) или “-” (заголовок второго уровня).

![Заголовки - хэш-символы](/images/Markdown/markdown-h1-to-h2.png)

#### Абзацы

В Markdown абзацы и другие элементы текста отделяются друг от друга пустыми строками. Сколько пустых строк помещается
между элементами, не играет никакой роли.

![Абзацы - пустые строки](/images/Markdown/markdown-paragraphs.png)

Пробелы и знаки табуляции между словами рассматриваются как один пробел.

![Абзацы - пробелы](/images/Markdown/markdown-spaces-between-words.png)

Если используется четыре знака отступа Markdown интерпретирует текст как код и форматирует его соответствующим образом.

![Абзацы - отступ](/images/Markdown/markdown-formatting-as-code.png)

Чтобы создать разрыв строки в Markdown (идентично тегу <br> в HTML), можно поставить два пробела в конце строки.
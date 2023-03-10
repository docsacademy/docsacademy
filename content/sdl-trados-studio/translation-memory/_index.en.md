---
title: "Память переводов"
date: 2023-01-02T11:02:05+06:00
lastmod: 2023-01-05T10:42:26+06:00
weight: 3
draft: false
# search related keywords
keywords: ["память переводов"]
---

В основе большинства систем автоматизированного перевода лежит па-мять переводов. Память переводов представляет
собой специальную базу данных, хранящую исходный текст и его переведенный эквивалент. При переводе новых текстов
базы данных проверяются на наличие идентич-ных или схожих фрагментов:

* Если такие фрагменты находятся, они показываются переводчику, который может использовать их без изменения
или внести в текст необходимые исправления. Отредактированный фрагмент также сохраня-ется в памяти переводов
и может использоваться в дальнейшем при переводе новых текстов.

* Если система не находит похожие фрагменты, переводчик может сам ввести перевод для нового фрагмента. После
того как фрагмент будет переведен, он также сохраняется в базе данных, а система переходит к переводу следующего
фрагмента.

Обычно память переводов хранится в виде отдельных файлов, которые могут подключаться к системам автоматизированного
перевода. Некоторые системы позволяют одновременно работать с несколькими файлами (например, SDL Trados Studio).
При этом одна память может использо-ваться в качестве основной, а остальные - для получения справочной информации.

Наиболее отчетливо преимущество систем автоматизированного перевода проявляется при обновлении уже переведенных
документов. В этом слу-чае все фрагменты, которые не изменялись с момента последнего перевода, переводятся
автоматически, а для измененных фрагментов отобра-жается перевод похожих, ранее переведенных предложений.

![Пример совпадения в SDL Trados Studio](/images/sdl-trados-studio/translation-memory-matches.png)

Как правило, тексты хранятся в базе данных в виде так называемых сегментов. Сегментом может быть любой кусок
текста: целое предложение, заголовок, элементы списка и т.д. Наряду с переведенными сегментами в базе данных
обычно хранится дополнительная информация о сегментах: дата создания, дата последнего изменения, имя переводчика
и т.д.

![Сегменты в памяти переводов](/images/sdl-trados-studio/translation-memory-segments.png)

1:	Сегменты <br />
2: Дополнительная информация
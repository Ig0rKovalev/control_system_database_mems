# Система управления базой данных мемов
## ОПИСАНИЕ ПРОБЛЕМЫ
Иногда возникает ситуация, когда в Вашей переписке с другом всплывает случайная фраза, идеально подходящая
под формат интернет мема. В такой ситуации лучшим решением бы было отправить соответствующий мем,
связанный с этой фразой. Но поиск конкретной картинки, которая подходила бы лучше всего, может занять
непростительно много времени. Момент будет упущен, беседа продолжит течь в своём темпе или вовсе
прекратится. Можно хранить огромную кучу боевых картинок в папке на компьютере, но это метод не для всех, так
как нужно запоминать структуру и содержимое всей этой папки (а она может быть достаточно большой). Для
избежание подобных катастроф и необходима СУБМ (система управления базой мемов).
## ФУНКЦИОНАЛ
− Хранение информации обо всех сохранённых мемах и тегах:
1) О мемах: название, изображение, дата добавления, описание;
2) О тегах: название, описание.
− Возможность сохранять картинку с произвольным количеством тегов и текстовым описанием шаблона, который
используется в меме (шаблоны: «блондинка показывает пальцем на кота» или «Парень из мультфильма срывает
маску со злодея», теги: «студенты» или «аниме»);
− Поиск по базе с настраиваемым фильтром и интерактивное «облако тегов» с возможностью выбора множества
вариантов (mangalib.me – хороший пример):
1) По одному тегу или их комбинации;
2) По текстовому описанию (или шаблону);
3) По дате добавления.
− Интерфейс Drag-and-drop для добавления новых мемов в базу в виде отдельной, постоянно активной области;
− Добавление новых мемов из буфера обмена;
− Помещение наиболее подходящего по тегам мема сразу в буфер обмена
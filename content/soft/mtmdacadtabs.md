+++
title = "MtmdAcadTabs"
+++

Приложение MtmdAcadTabs.arx предназначено для отображения "закладок"
с названиями чертежей в окне автокада. Отличительной особенностью MtmdAcadTabs
является возможность гибкой настройки отображаемого текста с помощью AutoLISP.
В частности, вместо имени файла чертежа можно отображать название документа
из SQL-базы системы документооборота либо формировать название по определенным правилам.

Данное приложение поставляется ["как есть"](https://ru.wikipedia.org/wiki/Как_есть)
со всеми вытекающими последствиями. Приложение бесплатно для некоммерческого применения.

## Инструкция по установке:

Данная версия не имеет инсталлятора, поэтому рекомендуется развернуть архив
в отдельный каталог, затем выбрать один из способов загрузки в автокад:
* Добавить путь к файлу MtmdAcadTabs.x.y.arx в Startup Suite (Menu->Tools->Load application->Startup Suite->Add...)
* Добавить строку (arxload "ПОЛНЫЙ ПУТЬ\MtmdAcadTabs.x.y.arx") в файл acad.lsp

## Инструкция по настройке:

По умолчанию закладки отображают имя файла чертежа без пути. Для настройки
под конкретные требования пользователя отредактируйте файл MtmdAcadTabs.lsp.
Более подробные инструкции см. в файле MtmdAcadTabs.lsp

##  История изменений:

4.10.04 - v.1.0 beta

6.10.04 - v.1.0
* Исправлены некоторые ошибки

7.10.04 - v.1.02
+ Список открытых документов в выпадающем меню

30.12.08 - v.1.1
+ Появилась возможность определять свои команды в контекстном меню (смотри пример в mtmdacadtabs.lsp)

17.08.10 - v.1.2
+ Закрытие документа по щелчку средней кнопкой мыши + Выпущены модули для автокада версий 2007-2009 и 2010

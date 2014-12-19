
## Что это?


Markdown - это легковесная вики-разметка. Поддерживаются все необходимые элементы для оформления статей - заголовки, списки, ссылки, картинки, форматирование. Главная цель которая ставилась при ее создании - читабельность в "сыром" виде. Например текст который вы сейчас читаете, в оригинальном виде выглядит [так](https://raw.githubusercontent.com/mzagorny/md/master/README.md)

## Какие проблемы решает markdown?

- Совместная работа над документацией

Поскольку markdown представляет собой текст, это дает возможность версионировать его любыми средствами контроля версий 

- Поддержание актуальности технической документации

За счет того, что операций по оформлению текста требуется минимум - то файлы с документацией включаются прямо в проект с кодом и версионируются по единой схеме с файлами проекта.
Кроме того все популярнее становится ведение всей документации в markdown в репозитории - например [документация Microsoft по Azure](https://github.com/Azure/azure-content)

## Как это можно применить мне?

Вопрос: Тут у вас гитхаб, а на работе как я ваш маркдаун смотреть буду?

Ответ: Есть [возможность](http://johnmacfarlane.net/pandoc/ "pandoc") конвертации markdown во все популярные форматы (html,docx,pdf)
Также есть [плагин](http://vswebessentials.com/ "Web Essentials") для работы с markdown в Visual Studio, а кроме того, TFS Server 2013 также [начал](http://blogs.msdn.com/b/visualstudioalm/archive/2014/08/07/project-homepages.aspx) двигаться в сторону поддержки markdown-разметки. А последние версии TFS Server уже поддерживают markdown см очень наглядный [видеообзор](http://channel9.msdn.com/Blogs/briankel/Lightweight-Web-Editing-with-Markdown-Files-in-Visual-Studio-Online)

## Ссылки

**Описания**
- [Markdown home](http://daringfireball.net/projects/markdown/syntax) - описание формата и философия markdown от автора
- [Более интерактивная справка от github](https://guides.github.com/features/mastering-markdown/)
- [Github flavored markdown](https://help.github.com/articles/github-flavored-markdown/) - более продвинутый маркдаун от гитхаб. Поддерживает таблицы и блоки кода. GFM Markdown используется в Visual Studio Online/TFS Server

**Инструменты**
- [Pandoc](http://johnmacfarlane.net/pandoc/) - конвертер markdown в другие форматы
- [Web Essentials](http://vswebessentials.com/) - плагин для Visual Studio, включает в себя поддержку markdown
- [MarkdownPad2](http://markdownpad.com/) - удобный markdown блокнот - бесплатный для частного использования
- [Github Atom](https://atom.io/) - текстовый редактор нового поколения от github. Поддержка markdown и git из коробки
- [Remark](http://gnab.github.io/remark/#1) - делаем презентации в markdown

## Как включить расцветку в Notepad++

1. Сохраняем содержимое [отсюда](https://raw.githubusercontent.com/Edditoria/markdown_npp_zenburn/master/default_theme/userDefineLang.xml) в xml файл с произвольным именем
1. Запускаем npp
1. Нажимаем меню Language - > Define your language...
1. В появившемся окне нажимаем кнопку Import...
1. Выбираем xml файл который мы сохранили
1. Перезапускаем npp




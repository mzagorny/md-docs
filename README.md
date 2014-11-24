
Что это?
==

Markdown - это легковесная вики-разметка. Главная цель которая ставилась при ее создании - читабельность в сыром виде.
Есть возможность конвертации markdown во все популярные форматы (html,docx,pdf)
Также есть плагин для работы с markdown в Visual Studio и множество онлайн-инструментов

Какие проблемы решает markdown?
==

- Совместная работа над документацией

Поскольку markdown представляет собой текст, это дает возможность версионировать его любыми средствами контроля версий 

- Поддержание актуальности технической документации

За счет того, что операций по оформлению текста требуется минимум - то файлы с документацией включаются прямо в проект с кодом и версионируются по единой схеме с файлами проекта.
Кроме того все популярнее становится ведение всей документации в markdown в репозитории - например [документация Microsoft по Azure](https://github.com/Azure/azure-content)

Ссылки
==
- [Markdown home](http://daringfireball.net/projects/markdown/syntax) - описание формата и философия markdown от автора
- [Pandoc](http://johnmacfarlane.net/pandoc/) - конвертер markdown в другие форматы
- [Web Essentials](http://vswebessentials.com/) - плагин для Visual Studio, включает в себя поддержку markdown
- [MarkdownPad2](http://markdownpad.com/) - удобный markdown блокнот - бесплатный для частного использования.
- [Remark](http://gnab.github.io/remark/#1) - делаем презентации в markdown

Как включить расцветку в Notepad++
==

1. Сохраняем содержимое [отсюда](https://raw.githubusercontent.com/Edditoria/markdown_npp_zenburn/master/default_theme/userDefineLang.xml) в xml файл с произвольным именем
1. Запускаем npp
1. Нажимаем меню Language - > Define your language...
1. В появившемся окне нажимаем кнопку Import...
1. Выбираем xml файл который мы сохранили
1. Перезапускаем npp




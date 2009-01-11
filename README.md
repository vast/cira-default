##cira
Просто _микро_ css/html шаблон. __kind of `reset.css` for me ;-)__.

###Зачем?
Надоело копировать одни и те же шаблоны, доктайпы, надоело постоянно выискивать png-хаки для ие.

###Что в комплекте?
`cira` -- shell-скрипт. `cira mahcoolapp` сгенерирует следующую структуру файлов:

    mahcoolapp
        css/
            base.css
            ie6.css
            print.css
        i/
            0.gif
        index.html
        favicon.ico

Если добавить ключик __-i__ в конце `cira mahcoolapp -i`, то дополнительно будут сгенерированы
еще и .iml, .ipr файлы для Intellij Idea.

###По порядку

* `css/base.css` -- минимальный набор _начальных_ стилей;
* `css/ie6.css` -- немножко часто используемых хаков-шмаков для ie6. Почему только ие6?
Потому что именно с ним большинство проблем, а ie<6 мне редко приходится поддерживать;
* `css/print.css` -- стиль для печати с минимумом функционала;
* `i/0.gif` -- прозрачный однопиксельный gif;
* `favicon.ico` -- пустая faviconка;
* `index.html` -- html-темплейт с уже готовой небольшой рыбой.

###Благодарности

* [lusever'у](http://lusever.ru/) -- за expressionы в ie с новой, неожиданно клевой стороны;
* парням, сделавшим [idea-maven-plugin](http://maven.apache.org/plugins/maven-idea-plugin/index.html).
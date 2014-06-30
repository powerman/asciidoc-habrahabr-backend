# Habrahabr backend for AsciiDoc

An [AsciiDoc](http://asciidoc.org/) plugin for generating
[Habrahabr](http://habrahabr.ru/) friendly HTML markup from AsciiDoc
source.

Для установки плагина скачайте
[habrahabr.zip](https://github.com/powerman/asciidoc-habrahabr-backend/releases/download/0.1.0/habrahabr.zip)
и установите его через `asciidoc`:

```
asciidoc --backend install habrahabr.zip
```

HTML полученный после конвертации backend-ом 'habrahabr' можно сразу
вставлять в поле для ввода текста новой статьи на сайте, но при этом
необходимо включить чекбокс:

* [X] Отключить автоматические переносы строк и создание ссылок 

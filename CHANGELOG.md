## v1.5.0
* обновлены зависимости
* добавлен логер
* добавлены функции toolkit
## v1.4.4
* upgrade dependencies
## v1.4.3
* fix GC
## v1.4.1
* fix script timeout error (upgrade isp-lib)
## v1.4.0
* add uuid generation function
## v1.3.1
* fix wrap body of script by `function(){` ... `}`
## v1.3.0
* migrate from inbuilt wrapping of goja to new isp-lib/scripts package
## v1.2.6
* fix db source with parallel enabled and where clause in query
## v1.2.5
* add setting comma for csv reader
## v1.2.4
* add quoting `'` in estimating query
## v1.2.3
* fix an endless loop after error
* increase script timeout from 200ms to 1000ms
* remove source.db.cursor param; always use cursors
## v1.2.0
* add rabbitmq as data source
* update dependencies
## v1.1.2
* omit nil results from script
## v1.1.0
* add alternative concurrent db data sources

# lk-vcs
~~~
$php artisan larakit:vcs
~~~
Достаточно часто, в процессе разработки приходится влезать в свои же vendor-пакеты. 

Поэтому потребовалась возможность быстрого поиска измененных файлов.

Обязательное условие: при обновлении composer использовать опцию **--prefer-dist**
~~~
$composer install --prefer-dist
~~~
~~~
$composer update --prefer-dist
~~~

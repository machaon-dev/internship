# Стажировка в Махаон

Привет! Мы всегда рады талантливым разработчикам, поэтому сократили прием на работу до трех простых шагов:

1. Пообщаться с HR и получить от него ссылку на этот репозиторий

2. Решить небольшое тестовое задание

3. Пройти очное интервью в нашем офисе

После этого мы в течение недели дадим обратную связь и, возможно, сделаем оффер.

Сейчас у нас открыто три вакансии:

- [Junior Web Developer](https://kirov.hh.ru/vacancy/38023247)

- [Middle Frontend Developer](https://kirov.hh.ru/vacancy/37897775)

- [Middle Backend Developer](https://kirov.hh.ru/vacancy/37739587)

Если ты не узнаёшь в них себя, но хочешь у нас работать — смело откликайся. Мы открыты к диалогу и найдем применение твоим навыкам.

## Тестовое задание для Junior Web Developer

Нужно написать php-функцию `config($optionName, $defaultValue)` для получения неких настроек проекта.

Настройки пусть хранятся в php-файле примерно такого формата:

```php
<?php

// settings.php

return [
  "site_name" => "My site",
  "site_url" => "http://mysite.ru",
  "db" => [
    "user" => "admin",
    "password" => "ifghigh8y8rt347ghi",
    "name" => "my_database"
  ]
];
```

Функция должна уметь возвращать значения вложенных настроек:

```php
echo config("site_url"); // http://mysite.ru

echo config("db.user"); // admin
```

Должна быть возможность указать значение по-умолчанию, которое вернется, если опции в файле нет:

```php
echo config("db.host", "localhost"); // localhost
```

Если опции нет, и значение по-умолчанию не задано, следует бросать исключение.

Помимо правильности работы функции, мы будем учитывать стиль написания кода, общую логику и оптимальность решения.

Ждем от тебя ссылку на репозиторий или gist с решением. Удачи!

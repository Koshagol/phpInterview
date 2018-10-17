## Основные нововведения версий 7.*

## [7.0](http://www.php.net/ChangeLog-7.php#7.1.14)

1. возможность обработки исключения, вместо фатальной ошибки
2. новые операторы сравнения ( <=>, ?? и другие)
3. анонимные классы
4. указание типа возвращаемого значения (return type declaration)
5. группировка для оператора use
6. работа с замыканиями (closure)
7. скалярные типы аргументов функции (scalar type hints)
8. опционально доступный "строгий режим" работы с типами (stitict mode)
9. изменена трактовка переменных и выражений
10. улучшена работа с генераторами ( ключевое слово yield from и другие изменения )
11. конструктор класса в стиле php4 (когда имя класса совпадает с именем метод) теперь генерирует E_DEPRECATED и будет удален в php8
12. изменено поведение побитовых операторов <<, >>  и других
13. изменено поведение функций funct_get_args и funct_get_arg
14. функция языка unserialize принимает дополнительный аргумент
15. функция языка list изменила поведение
16. изменено поведение цикла foreach (например в работе с внутренним итератором)
17. новый синтаксис unicode последовательностей

[7.1](http://www.php.net/ChangeLog-7.php#7.1.14)

1. возвращаемый тип void
2. псевдотип iterable
3. null в типизированных и возвращаемых параметрах
4. возможность использовать отрицательное значение для смещения в строках
5. разрешено использовать строковые ключи в конструкци
6. конвертация callable выражений в замыкание
7. Поддержка модификаторов видимости для констант класса
8. Ловить исключения можно объединяя несколько типов исключений в один блок 

## [7.2](http://www.php.net/ChangeLog-7.php#7.2.2)

1. Добавлена возможность загружать расширения по имени
2. Добавлена возможность перегружать абстрактные функции(Liskov)
3. Запрещено number_format() возвращать -0
4. Добавлена возможность конвертировать нумерованные ключи при приведении типов object/array
5. Запрещено передавать null в качестве параметра для get_class()
6. Вызов Count с параметром, который нельзя посчитать
7. Возможность расширения типа параметра
8. Добавлена возможность указывать запятую в конце группированных неймспейсов
9. Реализовано семейство функций socket_getaddrinfo
10. Улучшены TLS-константы
11. Object typehint
12. LDAP EXOP
13. В ядро PHP добавлена Libsodium
14. Добавлен алгоритм Argon2 в хешировании пароля
15. HashContext as Object
16. Добавлен отладчик PDO Prepared statements
17. Добавлен отладчик PDO Prepared statements v2
18. Расширенные типы строк для PDO
19. Добавлены опции JSON_INVALID_UTF8_IGNORE и JSON_INVALID_UTF8_SUBSTITUTE

## 7.3

1. Смягчение требований к синтаксису Heredoc и Nowdoc
2. Поддержка конечных запятых в вызовах функций и методов
3. Ссылки в `list()`
4. Функция `image2wbmp()` объявлена устаревшей
5. Флаги `FILTER_FLAG_SCHEME_REQUIRED` и `FILTER_FLAG_HOST_REQUIRED` при использовании `FILTER_VALIDATE_URL` объявлены устаревшими
6. Регистро-независимые константы объявлены устаревшими
7. Опциональный выброс исключений при ошибках в функциях `json_encode` и `json_decode`
8. Добавление функции `is_countable()`
9. Добавление функций `array_key_first()` и `array_key_last()`
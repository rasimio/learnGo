# Путь изучения Go: от нуля до backend-разработчика

## Введение

Эта программа рассчитана на 30-40 дней интенсивного обучения (6-8 часов в день) или 2-3 месяца при обучении 2-3 часа в день. Каждый этап включает теорию, практику и реальные задачи.

## Этап 1: Основы программирования и синтаксис Go (5-7 дней)

### День 1-2: Установка и первые шаги

**Теория:**
- Установка Go: [Официальная инструкция по установке](https://golang.org/doc/install)
- Настройка среды разработки: [Установка Goland](https://www.jetbrains.com/go/?var=1)
- Понимание GOPATH и Go Modules: [Статья про Go Modules](https://blog.golang.org/using-go-modules)
- Структура Go-программы: [Tour of Go - Packages](https://tour.golang.org/basics/1)

**Практика:**
1. Напиши программу "Hello, World!"
2. Создай калькулятор для сложения двух чисел
3. Программа для конвертации температуры (Цельсий в Фаренгейт)

**Задачи:**
- LeetCode: [1. Two Sum](https://leetcode.com/problems/two-sum/) (Easy)
- LeetCode: [9. Palindrome Number](https://leetcode.com/problems/palindrome-number/) (Easy)

### День 3-4: Базовые типы данных и переменные

**Теория:**
- Типы данных: [Go by Example - Variables](https://gobyexample.com/variables)
- Объявление переменных: [Tour of Go - Variables](https://tour.golang.org/basics/8)
- Type inference: [Effective Go - Variables](https://golang.org/doc/effective_go#variables)
- Zero values: [Tour of Go - Zero Values](https://tour.golang.org/basics/12)
- Константы: [Go by Example - Constants](https://gobyexample.com/constants)

**Практика:**
1. Программа для расчета площади различных фигур
2. Конвертер валют с фиксированными курсами
3. Генератор случайных паролей заданной длины

**Задачи:**
- LeetCode: [7. Reverse Integer](https://leetcode.com/problems/reverse-integer/) (Easy)
- LeetCode: [13. Roman to Integer](https://leetcode.com/problems/roman-to-integer/) (Easy)

### День 5-7: Управляющие конструкции

**Теория:**
- Условные операторы if/else: [Go by Example - If/Else](https://gobyexample.com/if-else)
- Switch: [Tour of Go - Switch](https://tour.golang.org/flowcontrol/9)
- Циклы for: [Go by Example - For](https://gobyexample.com/for)
- Break и continue: [Golang.org - For statements](https://golang.org/ref/spec#For_statements)
- Defer: [Tour of Go - Defer](https://tour.golang.org/flowcontrol/12)

**Практика:**
1. FizzBuzz (классическая задача)
2. Поиск простых чисел до N
3. Игра "Угадай число"

**Задачи:**
- LeetCode: [412. Fizz Buzz](https://leetcode.com/problems/fizz-buzz/) (Easy)
- LeetCode: [202. Happy Number](https://leetcode.com/problems/happy-number/) (Easy)
- HackerRank: [Loops](https://www.hackerrank.com/challenges/golang-loops/problem)

## Этап 2: Функции и структуры данных (7-10 дней)

### День 8-10: Функции

**Теория:**
- Объявление функций: [Go by Example - Functions](https://gobyexample.com/functions)
- Multiple return values: [Go by Example - Multiple Return Values](https://gobyexample.com/multiple-return-values)
- Named return values: [Effective Go - Named Results](https://golang.org/doc/effective_go#named-results)
- Variadic functions: [Go by Example - Variadic Functions](https://gobyexample.com/variadic-functions)
- Анонимные функции: [Go by Example - Closures](https://gobyexample.com/closures)
- Рекурсия: [Go by Example - Recursion](https://gobyexample.com/recursion)

**Практика:**
1. Набор математических функций (факториал, НОД, НОК)
2. Функции для работы со строками (reverse, isPalindrome)
3. Рекурсивные функции (Фибоначчи, Ханойские башни)

**Задачи:**
- LeetCode: [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) (Easy)
- LeetCode: [509. Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) (Easy)
- Codewars: [Multiple of 3 or 5](https://www.codewars.com/kata/514b92a657cdc65150000006)

### День 11-13: Массивы и срезы (Slices)

**Теория:**
- Массивы: [Go by Example - Arrays](https://gobyexample.com/arrays)
- Срезы: [Go by Example - Slices](https://gobyexample.com/slices)
- Внутреннее устройство срезов: [Go Blog - Go Slices](https://blog.golang.org/slices-intro)
- Append и copy: [Tour of Go - Append](https://tour.golang.org/moretypes/15)
- Make и new: [Effective Go - Allocation](https://golang.org/doc/effective_go#allocation_new)

**Практика:**
1. Реализация стека на срезах
2. Функции для работы с массивами (поиск, сортировка)
3. Матричные операции

**Задачи:**
- LeetCode: [26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) (Easy)
- LeetCode: [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) (Easy)
- LeetCode: [121. Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) (Easy)

### День 14-15: Maps и структуры

**Теория:**
- Maps: [Go by Example - Maps](https://gobyexample.com/maps)
- Проверка наличия ключа: [Effective Go - Maps](https://golang.org/doc/effective_go#maps)
- Структуры: [Go by Example - Structs](https://gobyexample.com/structs)
- Встроенные структуры: [Effective Go - Embedding](https://golang.org/doc/effective_go#embedding)
- Методы: [Go by Example - Methods](https://gobyexample.com/methods)
- Struct tags: [Go Wiki - Struct Tags](https://github.com/golang/go/wiki/Well-known-struct-tags)

**Практика:**
1. Телефонная книга (CRUD операции)
2. Система учета товаров на складе
3. Частотный анализ текста

**Задачи:**
- LeetCode: [1. Two Sum](https://leetcode.com/problems/two-sum/) (повторно с использованием map)
- LeetCode: [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) (Easy)
- LeetCode: [242. Valid Anagram](https://leetcode.com/problems/valid-anagram/) (Easy)

### День 16-17: Указатели и интерфейсы

**Теория:**
- Указатели: [Go by Example - Pointers](https://gobyexample.com/pointers)
- Указатели vs значения: [Tour of Go - Pointers](https://tour.golang.org/moretypes/1)
- Интерфейсы: [Go by Example - Interfaces](https://gobyexample.com/interfaces)
- Пустой интерфейс: [Tour of Go - Empty Interface](https://tour.golang.org/methods/14)
- Type assertion: [Tour of Go - Type Assertions](https://tour.golang.org/methods/15)
- Type switch: [Tour of Go - Type Switches](https://tour.golang.org/methods/16)

**Практика:**
1. Реализация связанного списка
2. Система фигур с интерфейсом Shape
3. Универсальная функция печати любых типов

**Задачи:**
- LeetCode: [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) (Easy)
- LeetCode: [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) (Easy)

## Этап 3: Продвинутые концепции Go (5-7 дней)

### День 18-19: Обработка ошибок

**Теория:**
- Error interface: [Go Blog - Error Handling](https://blog.golang.org/error-handling-and-go)
- Создание ошибок: [Go by Example - Errors](https://gobyexample.com/errors)
- Panic и recover: [Go by Example - Panic](https://gobyexample.com/panic)
- Best practices: [Effective Go - Errors](https://golang.org/doc/effective_go#errors)
- Error wrapping: [Working with Errors in Go 1.13](https://blog.golang.org/go1.13-errors)

**Практика:**
1. Безопасный калькулятор (с обработкой деления на ноль)
2. Валидатор email-адресов
3. Парсер конфигурационных файлов с детальными ошибками

### День 20-22: Конкурентность

**Теория:**
- Goroutines: [Go by Example - Goroutines](https://gobyexample.com/goroutines)
- Channels: [Go by Example - Channels](https://gobyexample.com/channels)
- Buffered channels: [Go by Example - Channel Buffering](https://gobyexample.com/channel-buffering)
- Select: [Go by Example - Select](https://gobyexample.com/select)
- WaitGroup: [Go by Example - WaitGroups](https://gobyexample.com/waitgroups)
- Mutex: [Go by Example - Mutexes](https://gobyexample.com/mutexes)
- Паттерны конкурентности: [Go Concurrency Patterns](https://talks.golang.org/2012/concurrency.slide)

**Практика:**
1. Параллельная загрузка файлов
2. Worker pool для обработки задач
3. Простой web-crawler

**Задачи:**
- Реализовать concurrent map
- Producer-consumer pattern
- Rate limiter

### День 23-24: Работа с файлами и JSON

**Теория:**
- Работа с файлами: [Go by Example - Reading Files](https://gobyexample.com/reading-files)
- Запись файлов: [Go by Example - Writing Files](https://gobyexample.com/writing-files)
- JSON encoding: [Go by Example - JSON](https://gobyexample.com/json)
- Работа с CSV: [Пакет encoding/csv](https://golang.org/pkg/encoding/csv/)
- Работа с XML: [Go by Example - XML](https://gobyexample.com/xml)

**Практика:**
1. Менеджер задач с сохранением в JSON
2. Анализатор логов
3. Конвертер форматов данных

## Этап 4: Web-разработка (7-10 дней)

### День 25-27: HTTP и REST API

**Теория:**
- HTTP сервер: [Go by Example - HTTP Servers](https://gobyexample.com/http-servers)
- HTTP клиент: [Go by Example - HTTP Clients](https://gobyexample.com/http-clients)
- Routing: [Writing Web Applications](https://golang.org/doc/articles/wiki/)
- Middleware: [Making and Using HTTP Middleware](https://www.alexedwards.net/blog/making-and-using-middleware)
- Context: [Go Blog - Context](https://blog.golang.org/context)
- REST принципы: [RESTful Web Services](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)

**Практика:**
1. Простой HTTP сервер
2. REST API для управления книгами
3. Middleware для логирования и аутентификации

**Инструменты:**
- [Gorilla Mux Tutorial](https://gowebexamples.com/routes-using-gorilla-mux/)
- [Chi Router](https://github.com/go-chi/chi)

### День 28-30: Базы данных

**Теория:**
- database/sql: [Go database/sql tutorial](http://go-database-sql.org/)
- Подключение к PostgreSQL: [PostgreSQL Driver](https://github.com/lib/pq)
- Prepared statements: [Using Prepared Statements](http://go-database-sql.org/prepared.html)
- Транзакции: [Работа с транзакциями](http://go-database-sql.org/transactions.html)
- Миграции: [golang-migrate](https://github.com/golang-migrate/migrate)

**Практика:**
1. CRUD API с базой данных
2. Система регистрации и аутентификации
3. Блог с комментариями

**Инструменты:**
- [GORM - ORM библиотека](https://gorm.io/docs/)
- [sqlx - расширения для database/sql](https://github.com/jmoiron/sqlx)

## Этап 5: CLI приложения и финальные проекты (5-7 дней)

### День 31-32: CLI приложения

**Теория:**
- flag пакет: [Go by Example - Command-Line Flags](https://gobyexample.com/command-line-flags)
- Аргументы: [Go by Example - Command-Line Arguments](https://gobyexample.com/command-line-arguments)
- Cobra framework: [Cobra Getting Started](https://github.com/spf13/cobra/blob/master/user_guide.md)
- Viper для конфигураций: [Viper Tutorial](https://github.com/spf13/viper)
- Цветной вывод: [fatih/color](https://github.com/fatih/color)

**Практика:**
1. CLI todo-приложение
2. Утилита для работы с файлами
3. CLI клиент для твоего API

### День 33-35: Тестирование

**Теория:**
- testing пакет: [Go by Example - Testing](https://gobyexample.com/testing)
- Table-driven tests: [TableDrivenTests](https://github.com/golang/go/wiki/TableDrivenTests)
- Benchmarks: [How to write benchmarks](https://dave.cheney.net/2013/06/30/how-to-write-benchmarks-in-go)
- Testify: [stretchr/testify](https://github.com/stretchr/testify)
- Mocking: [GoMock](https://github.com/golang/mock)
- Coverage: [The cover story](https://blog.golang.org/cover)

**Практика:**
1. Покрой тестами предыдущие проекты
2. TDD разработка нового модуля
3. Benchmark критичных функций

## Финальные проекты

### Проект 1: URL Shortener (3-4 дня)
- REST API для сокращения ссылок
- Сохранение в БД
- Статистика переходов
- Rate limiting
- Кеширование (Redis)
- Референс: [Building a URL Shortener](https://www.digitalocean.com/community/tutorials/how-to-build-a-url-shortener-with-go-and-redis)

### Проект 2: Task Management System (4-5 дней)
- Полноценный REST API
- Аутентификация (JWT): [JWT in Go](https://github.com/dgrijalva/jwt-go)
- Роли пользователей
- WebSocket для real-time обновлений: [Gorilla WebSocket](https://github.com/gorilla/websocket)
- Swagger документация: [swaggo/swag](https://github.com/swaggo/swag)

### Проект 3: CLI DevOps Tool (3-4 дня)
- Мониторинг системных ресурсов: [gopsutil](https://github.com/shirou/gopsutil)
- Деплой приложений
- Работа с Docker API: [Docker SDK](https://docs.docker.com/engine/api/sdk/)
- Конфигурационные файлы

## Дополнительные ресурсы

### Книги:
1. ["The Go Programming Language"](https://www.gopl.io/) - Alan Donovan, Brian Kernighan
2. ["Go in Action"](https://www.manning.com/books/go-in-action) - William Kennedy
3. ["Concurrency in Go"](https://www.oreilly.com/library/view/concurrency-in-go/9781491941294/) - Katherine Cox-Buday

### Онлайн-курсы:
1. [Tour of Go](https://tour.golang.org/) - официальный интерактивный учебник
2. [Go by Example](https://gobyexample.com/) - примеры кода
3. [Effective Go](https://golang.org/doc/effective_go.html) - best practices
4. [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests/) - TDD подход

### YouTube каналы:
1. [TechWorld with Nana](https://www.youtube.com/channel/UCdngmbVKX1Tgre699-XLlUA)
2. [Nic Jackson](https://www.youtube.com/channel/UC0p5jTL6L6f5sREnBmOXmJQ)
3. [justforfunc](https://www.youtube.com/channel/UC_BzFbxG2za3bp5NRRRXJSw)

### Практика:
1. [Exercism Go Track](https://exercism.io/tracks/go)
2. [Gophercises](https://gophercises.com/) - практические упражнения
3. [Go Bootcamp](http://www.golangbootcamp.com/)
4. [Advent of Code](https://adventofcode.com/) - ежегодные задачи

### Сообщества:
1. [Gophers Slack](https://invite.slack.golangbridge.org/)
2. [r/golang](https://www.reddit.com/r/golang/)
3. [Go Forum](https://forum.golangbridge.org/)
4. [Telegram: @golang_ru](https://t.me/golang_ru) - русскоязычное сообщество

## Советы для успешного обучения

1. **Пиши код каждый день** - даже 30 минут практики лучше, чем ничего
2. **Читай чужой код** - изучай [awesome-go](https://github.com/avelino/awesome-go) проекты
3. **Не пропускай error handling** - это важная часть Go
4. **Используй go fmt и golint** - следуй стандартам с первого дня
5. **Участвуй в code review** - проси обратную связь
6. **Веди блог или заметки** - документируй свой прогресс

## Чек-лист готовности к junior позиции

- [ ] Понимаю основные типы данных и структуры Go
- [ ] Умею работать с goroutines и channels
- [ ] Могу создать REST API с использованием стандартной библиотеки
- [ ] Умею работать с базами данных
- [ ] Понимаю как писать тесты
- [ ] Могу читать и понимать чужой код
- [ ] Знаю основные паттерны и best practices
- [ ] Имею 2-3 завершенных проекта на GitHub
- [ ] Умею работать с Git
- [ ] Базовое понимание Docker

Удачи в изучении Go! Помни, что программирование - это навык, который развивается только через практику.
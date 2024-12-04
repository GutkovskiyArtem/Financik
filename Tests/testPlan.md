
# План тестирования

---

## Содержание
1. [Введение](#introduction)  
2. [Объект тестирования](#items)  
3. [Атрибуты качества](#quality)  
4. [Риски](#risk)  
5. [Аспекты тестирования](#features)  
6. [Подходы к тестированию](#approach)  
7. [Представление результатов](#pass)  
8. [Выводы](#conclusion)

<a name="introduction"/>

## Введение

Данный документ описывает план тестирования приложения "Financik". Документ предназначен для людей, выполняющих тестирование данного проекта. Цель тестирования — проверка соответствия реального поведения программы проекта и ее ожидаемого поведения, которое описано в требованиях.

<a name="items"/>

## Объект тестирования

В качестве объектов тестирования можно выделить следующие функциональные требования:

- Вход в аккаунт;
- Регистрация нового аккаунта;
- Отображение текущего баланса;
- Просмотр истории транзакций;
- Редактирование баланса;
- Настройка параметров приложения;
- Добавление новой категории расходов;
- Добавление новой транзакции;
- Отображение списка транзакций за текущий день.

<a name="quality"/>

## Атрибуты качества

1. **Функциональность**:
    - Функциональная полнота: приложение должно выполнять все заявленные функции;
    - Функциональная корректность: приложение должно выполнять все заявленные функции корректно.
   
2. **Удобство использования**:
    - Все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента.

<a name="risk"/>

## Риски

К рискам можно отнести:
- Потерю соединения с сервером, что может привести к некорректному отображению баланса или истории транзакций.

<a name="features"/>

## Аспекты тестирования

В ходе тестирования планируется проверить реализацию основных функций приложения. Аспекты, подвергаемые тестированию: 
- Запуск приложения;  
- Регистрация нового пользователя;  
- Вход в существующий аккаунт;  
- Отображение текущего баланса;  
- Просмотр истории транзакций;  
- Редактирование баланса;  
- Настройки приложения;  
- Добавление новой категории расходов;  
- Добавление новой транзакции;  
- Отображение списка транзакций за текущий день.  

### Запуск приложения
Необходимо протестировать:
- Запуск приложения;
- Отображение окна приложения.

### Регистрация нового пользователя
Необходимо протестировать:
- Добавление данных о пользователе в базу данных;
- Корректное отображение нового пользователя.

### Вход в существующий аккаунт
Необходимо протестировать:
- Корректный переход на главное меню с данными пользователя.

### Отображение текущего баланса
Необходимо протестировать:
- Корректное отображение текущего баланса на главном экране.

### Просмотр истории транзакций
Необходимо протестировать:
- Отображение всех транзакций по месяцам.

### Редактирование баланса
Необходимо протестировать:
- Обновление суммы баланса и ее корректное отображение на главном экране.

### Настройки приложения
Необходимо протестировать:
- Открытие настроек и доступность всех параметров.

### Добавление новой категории расходов
Необходимо протестировать:
- Добавление новой категории и отображение ее в списке категорий.

### Добавление новой транзакции
Необходимо протестировать:
- Ввод и сохранение новой транзакции в список транзакций.

### Отображение списка транзакций за текущий день
Необходимо протестировать:
- Корректное отображение списка транзакций за текущий день на главном экране.

<a name="approach"/>

## Подходы к тестированию

При тестировании будет использован ручной подход.

<a name="pass"/>

## Представление результатов

Результаты представлены в документе "Результаты тестирования".

<a name="conclusion"/>

## Выводы

Данный тестовый план позволяет протестировать основной функционал приложения "Financik". Успешное прохождение всех тестов не гарантирует полной работоспособности на всех версиях платформ и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.
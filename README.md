# goit-rdb-hw-02
Домашнє завдання до Теми 2. Проектування баз даних з використанням семантичних моделей

**Структура файлів та опис виконання завдання**

1. Скріншоти "1_Diagram_початкова_ненормалізована" та "1_Table_початкова_ненормалізована" відображають оригінальну ненормалізовану таблицю та відповідну ER-діаграму.
2. Скріншоти "2_Diagram_1НФ" та "2_Table_1НФ" відображають таблицю та відповідну ER-діаграму, нормалізовані до першої форми.
3. Скріншоти "3_Diagram_2НФ", "3_Table_order_items_2НФ" та "3_Table_orders_2НФ" відображають таблицю та відповідну ER-діаграму, нормалізовані до другої форми. Перетворення до другої нормальної форми включало розділення попередньої таблиці у першій нормальній формі на дві таблиці: order_items (включає інформацію про склад замовлення) та orders (інша інформація про замовлення, така як дані клієнта та дата).
4. Скріншоти "4_Diagram_3НФ", "4_Table_clients_3НФ", "4_Table_order_items_3НФ" та "4_Table_orders_3НФ" відображають таблицю та відповідну ER-діаграму, нормалізовані до третьої форми. Нормалізація до третьої форми включала розділення двох попередніх таблиць у другій нормальній формі на три таблиці: clients (інформація про клієнтів, включаючи ідентифікатор клієнта, ім'я та адресу), order_items (інформація про товари, що складають замовлення; включає ідентифікатор товара та посилання на номер замовлення у вигляді зовнішнього ключа), orders (включає інформацію про саме замовлення, ідентифікатор клієнта, що є зовнішнім ключем відносно первинного ключа у таблиці clients) і дату замовлення.

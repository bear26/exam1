Задание на экзамен (расписание автомойки)
===========
Написать программу, которая состоит из следующих частей:<br>
1. Окно ввода параметров мойки (название и количество окон). Дефолтное название - "автомойка у дяди Вани", количество окон - 3. Показывается только при первом запуске приложения.<br>
2. Список заказов, отсортированный по времени (3 колонки: марка+цвет, время, номер окна).<br>
3. Окно добавления заказа (марка автомобиля, цвет, госномер, номер телефона и выбор времени комбобоксом), открывается по клику на кнопку "добавить"/"+". Комбобокс с выбором времени показывает только свободное время.<br>
4. Окно с подробностями заказа (+номер машины и номер телефона), окрывается по клику на заказ. В этом окне данные редактировать нельзя.<br>
5. Окно редактирования времени, открывается из контекстного меню по длинному клику на заказ. В том же меню должно быть и удаление заказа (с подтверждением).<br>
6. Заказы распределяются по окнам автоматически.

Режим работы мойки с 8:00 до 22:00, каждая мойка занимает ровно полчаса.

Все данные должны храниться в sqlite базе данных.

Система оценок:
- Программа, в которой реализованы пункты 1-3 и 6: 10 балла
- Пункт 4: 5 балла
- Пункт 5: 5 балла
- Дополнительные баллы могут быть поставлены за хороший код и красивый дизайн.
 
Суммарный балл может быть снижен за плохой код, так то русский в коде/комментариях, незакрытые ресурсы, строчки в коде вместо strings.xml, wrap_content для ListView итд, неполная ширина для клика на кнопку, равно как и плохой кастомный дизайн.

Ничего из указанного выше не отменяет здравый смысл.

Задание необходимо сдавать в виде пулл-реквеста (код+apk) к https://github.com/IFMO-MobDev-2013/exam1 до 18:20 14.01.14.

<h4>Запускать файл start.html, все нужные скрипты лежат в папках, ничего дополнительно делать не нужно </h4>
Это некий симулятор Windows 95. Не полноценный Windows конечно, но я очень старался сделать как можно больше функций :) <br>

=====


Что удалось реализовать: <br>
    - Запуск Windows <br>
    - Перетаскивание значков <br>
    - Все значки на рабочем столе открываются при двойном клике <br>
    - Калькулятор (был написан ранее на нативном JS, так его и оставил) <br>
    - Блокнот (возможность редактирования текста, при изменении текста <br>
    перед закрытием спрашивает: "Сохранить ли изменения") <br>
    Дополнительные функции блокнота (написано на чистом JS + кроссбраузерность) <br>
    - (Файл - Создать) Создать новый блокнот;<br>
    - (Файл - Сохранить) Сохранение текущих изменений;<br>
    - (Файл - Сохранить как) Cоздание нового блокнота с введеным именем, если такое имя есть - выдает запрос на перезапись, <br>
        если имя пустое - не дает сохранить и фокусирует на инпуте ввода, при подтверждении перезаписи он перезаписывает существующий файл <br>
    - (Файл - Выход) Выход, тут понятно <br>
    - (Вид - настройки шрифта) Настройка шрифта в блокнотах, размер, стиль, семейство <br>
    Остальные функции: <br>
    - Игра Сапер <br>
    - Плеер Winamp <br>
    - Шри Галлерея - это мое решение экзаменационного задания предыдущего курса ШРИ <br>
    - Удаление (перетаскивание) в корзину <br>
    - Очистка корзины (Корзина - Файл - Очистить корзину) <br>
    - Выключение, перезагрузка <br>
    - Управление открытыми окнами: Перемещение, Сворачивание, Разворачивание (нажатие на задачу в таскбаре внизу) <br>
    Активация нужного окна, т.е. перенос окна выше остальных по оси Z (аналогично - нажатие на задачу в таскбаре внизу) <br>
    и наоборот активация задачи в таскбаре при нажатии на другое открытое окно, <br>
    увеличение на весь экран и возвращение к начальному размеру, <br>
    ресайз окна мышкой(например: зажатие мышкой в правом нижнем углу открытого окна) <br>
    - Часы <br>
    - Меню Пуск, кроме кнопки Завершение работы, декоративное (в проекте его расширение и увеличение функций) <br>

Это пока beta версия, я еще буду допиливать некоторые моменты :) <br>
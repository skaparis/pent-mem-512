# О проекте

В рамках проекта была разработана плата расширения памяти, описанной изначально тут:
https://www.8bit.lt/ru/pentagon/pentagon-128k/rasshirenie-pamjati-do-512k-na-sram
Была произведена адапация платы под проект платы Pentagon 2023 от gdv2002.
Несколько основных изменений
- переход на микросхемы в корпусах SOIC, SMD элементы и более компактный монтаж
- выравнивание ножек под ровное расположение РУ5 (схема Pentagon 2023)
- использование зоны макетирования на плате, для стыковк с дополнитлеьными сигналами

Проект выполнен в программе DipTrace. Содержит как схему, так и разведенную плату (DCH + DIP).

Два варианта SIP и DIP

## Компоненты

Набор для для корпусов SOIC
* BS62LV4006SIP55
* 74HC244D
* 74HC374D
* 74HC08D
* 74HC74D

Набор для DIP (не доделано)
* BS62LV4006PIP70
* 74HC244 / 1533АП5
* 74HC374 / 1533ИР23
* 74HC08 / 1533ТМ2
* 74HC74 / 1533ЛИ1

## Изображения
Плата свеху
![Макет платы](/images/pcb.jpg)
Плата снизу
![Макет платы](/images/pcb_back.jpg)


# Информация о плате Pentagon 128
Данное рашсширение выполнено для Pentagon 2023 от gdv2002 
Информацию можно найти тут: t.me/Pentagon_ZX_Chat

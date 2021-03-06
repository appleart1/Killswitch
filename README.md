# Killswitch

## Описание проекта
Killswitch - это комплекс из приложения и аппаратного токена (маяка), предназначенный для локальной инициации вайпа Android-устройства в случае, когда пользователь потерял контроль. Например, телефон отобрали сотрудники правоохранительных органов и пытаются разблокировать для получения компрометирующей информации. 
## Какую проблему решает проект
Очистка устройства, содержащего чувствительные данные в случае утери физического доступа и связности через Интернет.
## В проект нужны:
AVR/Cortex-M C/C++ разработчик со знанием USB и умением в схемотехнику.
## Текущее состояние проекта
- минимальный функционал приложения-контроллера под Android (проверено на версиях 8.0 и 9.0)
- реализована рабочая прошивка BLE-маяка под ESP32
- устойчивая двусторонняя связь с BLE-маяком
- работает управление светодиодным индикатором BLE-маяка (выключен - нет связи с телефоном, включен - сработал вайп, мигает - идет мониторинг состояния маяка)
- сохраняется состояние после перезагрузки телефона
## Ближайшие планы
- реализация обратной совместимости с Android до версии 5.0 включительно.
- портирование прошивки BLE-маяка на кристаллы Nordic Semiconductor nRF51822
- реализация работы с USB-шлейфом
- исследование перспектив реализации работы с BLE-браслетами, имеющими фотоплетизмографический датчик (считывание показаний сердцебиения)
- исследование перспектив реализации отправки уведомлений перед вайпом.
- исследование расширения функционала для устройств с root-доступом
--- 

## Контакты
Майк
* cyberspacelabs@gmail.com
* https://t.me/MikeLambert
* https://github.com/mike-lambert 

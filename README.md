# Ultra 4IFIR

[4IFIR Group в телеграме](https://t.me/For4ifir)

**ВНИМАНИЕ! Автор не несет ответственности за последствия установки Ultra 4IFIR, вы все делаете на свой страх и риск.**
**Но, по моему опыту, разгон консоли абсолютно безопасен для железа консоли, но он может представлять опасность для ваших данных, портить файлы игр, сохранения или даже повредить системные файлы, поэтому крайне рекомендуется пользоваться разгоном только на Эмунанде, и всегда делать своевременные бэкапы сейвов.**

## Описание проекта
Ультимативное решение для максимального разгона и его конфигурации под вашу консоль!
Сделано на основе [4IFIR](https://github.com/rashevskyv/4IFIR)

Включает в себя Ultra Tuner на основе [Ultrahand](https://github.com/ppkantorski/Ultrahand-Overlay)
- Позволяет настроить андервольт гпу как пакетно, переключая `ГПУ` с базы на ст или обратно, так и точечно выбрать вольтаж любой из частот.
- Возможность изменить лимит вольтажа `ЦПУ` как для эристы, так и для марико, что увеличит потолок разгона ЦПУ (Или при понижении может поправить вылеты игр)
- Выбор частоты и изменение вольтажей `РАМ`.

## Установка

1. Распакуйте архив [AIO](https://github.com/redraz/Ultra-4ifir/raw/main/AIO/AIO.zip) в корень SD карты с заменой/слиянием файлов.
2. Открываем `hb menu` (Через запуск игры с зажатой R), запускаем `All-in-One Switch Updater`, спускаемся в пункт `Сторонние загрузки` (`Custom downloads` в оригинале).
3. Сначала, на всякий случай выбираем `Refresh AIO`, на вопрос отвечаем `yes`, это обновит ссылки в AIO.
4. Опять заходим в `Сторонние загрузки`, выбираем `Ultra 4IFIR`, на первый вопрос отвечаем `yes`, на второй `no`.

### Чистая установка
Если у вас возникли проблемы с установкой через `AIO`, то можно произвести чистую установку:
- Удаляем с карты памяти всё, кроме папок `Nintendo` и `emuMMC`, а потом распаковываем архив [Ultra 4IFIR](https://github.com/redraz/Ultra-4ifir/releases/latest/download/Ultra.4IFIR.zip) на карту.
- Это удалит все моды для игр и хоумбрю программы, но не затронет ваши игры и сохранения.


## Использование
Для смены стейджей/настройки
1. Открываем тесла-меню (L+R+вверх) - вместо него теперь `Ultrahand`, нажимаем вправо для перехода к плагинам. Заходим в `Ultra Tuner`, выбираем свою консоль, `Mariko` или `Erista`, и нажимаем B.
2. Так будет происходить вся дальнейшая настройка: заходим в нужный вам пункт меню, выбираем нужную настройку и нажимаем B для выхода назад. Пункты меню в это время обновляются, и на главной странице появляются новые меню.
3. Заходим в `Ultra Tuner` снова, он обновился и нам доступны новые пункты. Выбираем `Create Backup`, после выбираем `Initialization Ultra`, и выбрав нужный нам стейдж, снова выходим назад, пару раз нажимая B.
4. На выбор предлагается `Base`, `Mega`, `Ultra`. Стейджи отличаются друг от друга кучей параметров, но только тайминги можно поменять сменой стейджа, остальное меняется и через тюнер внутри стейджа.
- Для марико:`Base` - 2565мгц, `Mega` - 2700мгц и `Ultra` - 2773мгц.
- Для эристы:`Base` - 1996мгц, `Mega` - 2131мгц и `Ultra` - 2131мгц.
5. Если сравнивать с оригинальным Чифиром:
- `База 1.6` = `Base`
- `ст8 1.6`  = `Base 2700ram + ST gpu`
- `ст8+ 1.6` = `Mega`
- `ст9 1.6`  = `Ultra 2828ram + overvolt GPU`
- Актуально для марико, для эристы стейджи остались теми же.
6. После конца настройки, заходим обратно в `Ultra Tuner` и выбираем `Complete Tuning`, это очистит лишние пункты меню и перезагрузит консоль.
7. Если вы переборщили с разгоном/стейджем, и у вас не загружается консоль - просто войдите в `Hekate`, и выберите загрузку в `Safe Mode`, в отличии от `Semi Stock` в "безопасном режиме" не подгружается loader.kip разгона, так что можно без проблем в него загрузиться и восстановить бэкап/поставить базовый стейдж.


### Дополнение

Теперь `4ifir Micro` вшит в сам `Ultra Tuner` - достаточно распаковать архив [AIO](https://github.com/redraz/Ultra-4ifir/raw/main/AIO/AIO.zip), установить через него Тюнер + Апдейтер, перезагрузить консоль и провести инициализацию стейджа. После этого, разгон от Чифира будет работать на Кефире/ОС Сьюте.

В `Ultra Updater` так же возможна установка разных Hombrew-приложений, как из состава оригинального 4ifir, так и других, а так же доступны моды созданные самим Кулером.


## Благодарность

Если вам понравились результаты моих стараний, и у вас появилось желание закинуть мне на шаву (или на аксессуары для свитча), то буду очень благодарен.
Сбер: 2202200513345833

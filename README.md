# Ultra 4IFIR

[4IFIR Group в Телеграме](https://t.me/For4ifir)

**ВНИМАНИЕ! Автор не несет ответственности за последствия установки Ultra 4IFIR, вы все делаете на свой страх и риск.**
**Но, по моему опыту, разгон консоли абсолютно безопасен для железа консоли, но он может представлять опасность для ваших данных, портить файлы игр, сохранения или даже повредить системные файлы, поэтому крайне рекомендуется пользоваться разгоном только на Эмунанде, и всегда делать своевременные бэкапы сейвов.**

## Описание проекта
Ультимативное решение для максимального разгона и его конфигурации под вашу консоль!
Сделано на основе [4IFIR](https://github.com/rashevskyv/4IFIR), все лицензии от исходного проекта.

Основой сборки является Ultra Tuner, который был сделан благодаря [Ultrahand](https://github.com/ppkantorski/Ultrahand-Overlay).
- Позволяет настроить андервольт гпу как пакетно, переключая `ГПУ` с кор на стейдж или обратно, так и точечно выбрать вольтаж любой из частот.
- Возможность изменить лимит вольтажа `ЦПУ` как для эристы, так и для марико, что увеличит потолок разгона ЦПУ (Или при понижении может поправить вылеты игр). Так же позволяет настраивать силу андервольта процессора.
- Выбор частоты, таймингов и изменение вольтажей `РАМ`.


## Установка
1. Распакуйте архив [AIO](https://github.com/redraz/Ultra-4ifir/raw/main/AIO/AIO.zip) в корень SD карты с заменой/слиянием файлов.
2. Открываем `hb menu` (Через запуск игры с зажатой R), запускаем `All-in-One Switch Updater`, спускаемся в пункт `Сторонние загрузки`.
3. Сначала, на всякий случай выбираем `Refresh AIO`, на вопрос отвечаем `yes`, это обновит ссылки в AIO.
4. Опять заходим в `Сторонние загрузки`, выбираем `[PACK] Ultra 4IFIR`, на вопрос отвечаем `yes`.

### Чистая установка
Если у вас возникли проблемы с установкой через `AIO`, то можно произвести чистую установку:
- Удаляем с карты памяти всё, кроме папок `Nintendo` и `emuMMC`, а потом распаковываем архив [Ultra 4IFIR](https://github.com/redraz/Ultra-4ifir/raw/main/Ultra%204IFIR/Ultra%204IFIR.zip) на карту.
- Это удалит все моды для игр и хоумбрю программы, но не затронет ваши игры и сохранения.


## Использование
**Для смены стейджей/настройки**
1. Открываем тесла-меню (L+R+вверх) - вместо него теперь `4esla`, нажимаем вправо для перехода к плагинам.
2. Заходим в `Ultra`, и на всякий случай создаем бэкап - `Backup - Create`.
3. Теперь вы вольны настраивать систему как вам угодно, или выбрать из списка предложенных пресетов.
4. После конца настройки, заходим в `Ultra` - `Tuner` - `Complete`, это перезагрузит консоль.
5. Если вы переборщили с разгоном/стейджем, и у вас не загружается консоль - просто войдите в `Hekate`, и выберите загрузку в `Safe Mode`, в отличии от `Semi Stock` в "безопасном режиме" не подгружается loader.kip разгона, так что можно без проблем в него загрузиться и восстановить бэкап/поставить базовый стейдж.


### Standalone
Отдельный Тюнер для OS Suite можно скачать через специальный [Updater](https://github.com/redraz/Ultra-4ifir/raw/main/Packages/Standalone%20Pack.zip). Для установки - распаковать архив на консоль и перезагрузить для работы плагина.


### Дополнение
`Updater` в составе `Ultra` предоставляет много дополнительных возможностей.
Что есть в апдейтере:
1. Установка разных Hombrew-приложений, все из состава оригинального чифира а так же все что выкладывал Кулер. Так же есть дополнительные полезные хоумбрю.
2. Возможность скачать любой мод из 4MODS от Кулера, плюс пару бонусных модов.
3. Включение/Отключение фоновых онлайн синхронизаций. По умолчанию они отключены, что уменьшает потребление консоли в режиме сна. Но если вы часто играете в лицензию, то имеет смысл их включить. Что бы лицензионные игры во время сна обновлялись, приходили оповещения от друзей, и нормально заходило в нинтендо шоп.
4. Настройка частоты фоновой записи видео, и ее битрейта. Требуется применять после каждого включения/отключения фоновых сервисов из-за особенности работы.
5. Изменение комбинации открытия 4esla, что влияет на оверлеи и статус монитор.


## Благодарность
Если вам понравились результаты моих стараний, и у вас появилось желание закинуть мне на шаву, то буду очень благодарен.
Сбер: 2202200513345833

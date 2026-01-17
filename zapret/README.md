# zapret

## Кастомный конфиг для программы обхода блокировок [zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube) на Windows.

Мне помогло разблокировать всё, что мне надо без потери скорости (Apex Legends, YouTube, Discord и тд.). Так как это зависит от провайдера за работоспособность и эффективность я не ручаюсь. Возможно их появятся больше.

### Инструкция по установке кастомного конфига

1. Скачать и распаковать [zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube) последней версии (1.9.3 версия проверена)
2. Скопировать в корень папки с программой zapret кастомный конфиг файл [custom.bat](./configs/custom.bat)
3. Запустить батник с моим конфигом, перезапускаете компьютер и радуетесь жизни без запретов от РКН

> [!WARNING]
>
> Если запускать как сервис (через service.bat), то **ОБЯЗАТЕЛЬНО** выключать Game Filter и IPSet Filter поставить на none

---

Также есть некоторый список сайтов, которые мне нужно разблокировать помимо дефолтных, они находятся в [list-general.txt](./list-general.txt).

### Инструкция по установке

1. Перейти из корневой папки программы в папку `list`
2. Открыть или создать `list-general.txt`
3. Добавить список адресов из моего [list-general.txt](./list-general.txt) в `list-general.txt`

## Второй способ Apex Legends обхода с помощью warp (работает хуже и не у всех)

1. Обновить zapret до последней версии (1.9.3 минимум)
2. Добавить правила в папке list в файле list-general.txt из [list-general_apex.txt](./list-general_apex.txt).
3. Включить в zapret функции Game Filter и IPSet Filter (any)
4. Включить подходящую для вас стратегию в zapret, чтобы работало всё что вам нужно
5. Только после этого скачиваем и устанавливаем [warp](https://developers.cloudflare.com/cloudflare-one/team-and-resources/devices/warp/download-warp/)

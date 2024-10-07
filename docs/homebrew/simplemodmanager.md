# SimpleModManager

SimpleModManager — это [homebrew](index.md#terminologies), которое позволяет легко добавлять и удалять моды в директории layeredFS из другой директории на SD-карте.

#### Общие случаи использования SimpleModManager:

- Переключение между большими модпаками
- Включение и отключение отдельных модов

!!! warning "Чего **не** следует делать с SimpleModManager."
    SimpleModManager не следует использовать для некоторых конкретных игр, таких как Super Smash Bros. Ultimate, The Legend of Zelda: Breath of the Wild и Tears of the Kingdom. Это связано с тем, как эти игры обрабатывают моды иначе, чем другие.

-----

#### Требования к установке:
- Последняя версия [SimpleModManager](https://github.com/nadrino/SimpleModManager/releases/latest) (файл `SimpleModManager.nro`)

#### Инструкция по установке:
1. Загрузитесь в Hekate и перейдите в `Tools` > `USB Tools` > `SD Card`, затем подключите вашу консоль к ПК через USB.
2. Ваша microSD карта теперь должна быть доступна на вашем ПК, откройте её.
3. Скопируйте файл `SimpleModManager.nro` в папку `/switch/` на вашей microSD карте.
4. Загрузитесь в CFW.

#### Инструкция по использованию:
1. Создайте директорию с именем `mods/<имя игры>/<имя мода>/` в корне SD-карты.
    - Имя мода не обязательно должно соответствовать чему-либо, можете назвать его как угодно!
2. Создайте директорию layeredFS для вашего мода, которую можно найти на странице [моддинг игр](../extras/game_modding.md), пропустив папку `atmosphere` внутри папки `<имя мода>`.
3. Запустите SimpleModManager через Homebrew меню, и ваши игры появятся. Нажмите A на них, чтобы увидеть доступные моды.

![Пример использования SimpleModManager](img/simplemodmanager1.jpg){ width="600" }
![Пример использования SimpleModManager](img/simplemodmanager2.jpg){ width="600" }

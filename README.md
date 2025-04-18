<<<<<<< HEAD
<!--<p align="center"> <img alt="Rayten" width="880" height="300" src="https://raw.githubusercontent.com/space-wizards/asset-dump/de329a7898bb716b9d5ba9a0cd07f38e61f1ed05/github-logo.svg" /></p>-->
=======
<div class="header" align="center">  
<img alt="Space Station 14" width="880" height="300" src="https://raw.githubusercontent.com/space-wizards/asset-dump/de329a7898bb716b9d5ba9a0cd07f38e61f1ed05/github-logo.svg">  
</div>
>>>>>>> 259ac00c29e6cef4aae0df276cbf07393a8a778a

<h1 align="center">🌌 Rayten 🌌</h1>
Это репозиторий русскоязычного сервера по игре Space Station 14.

**Данный репозиторий включает в себя неполный исходный код нашей сборки.**
## Ссылки

[Наш Discord](https://discord.gg/W3Ep2esrzc) | [Наша Вики](https://vanilla-station.ru/) | [Официальный репозиторий](https://github.com/space-wizards/space-station-14)

## Документация

<<<<<<< HEAD
На официальном сайте с [документацией](https://docs.spacestation14.io/) имеется вся необходимая информация о контенте SS14, движке, дизайне игры и многом другом. Также имеется много информации для начинающих разработчиков.
=======
<div class="header" align="center">  

[Website](https://spacestation14.com/) | [Discord](https://discord.ss14.io/) | [Forum](https://forum.spacestation14.com/) | [Mastodon](https://mastodon.gamedev.place/@spacestation14) | [Lemmy](https://lemmy.spacestation14.com/) | [Patreon](https://www.patreon.com/spacestation14) | [Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Standalone Download](https://spacestation14.com/about/nightlies/)  

</div>
>>>>>>> 259ac00c29e6cef4aae0df276cbf07393a8a778a

## Контрибьют

<<<<<<< HEAD
Мы рады принять вклад от любого человека. Заходите в Discord и пишите, если хотите помочь. У нас есть [список проблем](https://github.com/VanillaStation14/VanillaStation/issues), которые нужно решить, и любой может за них взяться. Не бойтесь просить о помощи!
Только убедитесь, что ваши изменения и PRы соответствуют [руководству по контрибьюту](https://docs.spacestation14.com/en/general-development/codebase-info/pull-request-guidelines.html).
=======
Our [docs site](https://docs.spacestation14.com/) has documentation on SS14's content, engine, game design, and more.  
Additionally, see these resources for license and attribution information:  
- [Robust Generic Attribution](https://docs.spacestation14.com/en/specifications/robust-generic-attribution.html)  
- [Robust Station Image](https://docs.spacestation14.com/en/specifications/robust-station-image.html)

We also have lots of resources for new contributors to the project.
>>>>>>> 259ac00c29e6cef4aae0df276cbf07393a8a778a

## Сборка

1. Склонируйте этот репозиторий локально.
2. Запустите `RUN_THIS.py` для инициализации подмодулей и скачивания движка.
3. [Скомпилируйте](https://docs.spacestation14.com/en/general-development/setup/server-hosting-tutorial.html#level-2-server-with-custom-code) проект.

<<<<<<< HEAD
### Консольные команды
=======
We are not currently accepting translations of the game on our main repository. If you would like to translate the game into another language, consider creating a fork or contributing to a fork.
>>>>>>> 259ac00c29e6cef4aae0df276cbf07393a8a778a

```bash
# Скопировать репозиторий
git clone https://github.com/VanillaStation14/VanillaStation.git

<<<<<<< HEAD
# Перейти в скачанный репозиторий
cd VanillaStation
=======
1. Clone this repo:
```shell
git clone https://github.com/space-wizards/space-station-14.git
```
2. Go to the project folder and run `RUN_THIS.py` to initialize the submodules and load the engine:
```shell
cd space-station-14
python RUN_THIS.py
```
3. Compile the solution:  

Build the server using `dotnet build`.
>>>>>>> 259ac00c29e6cef4aae0df276cbf07393a8a778a

# Запустить RUN_THIS.py
python ./RUN_THIS.py

# Скомпилировать проект под Windows
dotnet build Content.Packaging --configuration Release
```

<<<<<<< HEAD
[Более подробная инструкция по запуску проекта.](https://docs.spacestation14.com/en/general-development/setup.html)

## Лицензия
Весь код данного [pr](https://github.com/RaytenCorp/VanillaStation/pull/132) лицензирован под AGPLv3.

Весь прочий код репозитория лицензирован под [MIT](https://github.com/space-syndicate/space-station-14/blob/master/LICENSE.TXT), включая код Vanilla Station и их контрибутеров.

Большинство ассетов лицензированы под [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/), если не указано иное. Ассеты имеют свою лицензию и авторские права в файле метаданных. [Пример](https://github.com/space-syndicate/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Обратите внимание, что некоторые ассеты лицензированы на некоммерческой основе [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) или аналогичной некоммерческой лицензией, и их необходимо удалить, если вы хотите использовать этот проект в коммерческих целях.

P.S. Спасибо что выбрали Rayten!
=======
All code for the content repository is licensed under the [MIT license](https://github.com/space-wizards/space-station-14/blob/master/LICENSE.TXT).  

Most assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and copyright specified in the metadata file. For example, see the [metadata for a crowbar](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).  

> [!NOTE]
> Some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.
>>>>>>> 259ac00c29e6cef4aae0df276cbf07393a8a778a

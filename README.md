<!-- Header -->
<div align="center">

  <a href="https://discord.gg/jZHxYdF">
    <img src="https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/git_assets/comrem_logo_shadow.png" alt="ComRem logo" width="400">
  </a>
  <h3 align="center">Комьюнити Ремастер / Комьюнити Патч</h3>

  ![Ru Readme](git_assets/in_russian_selected.png)   [![Eng Readme](git_assets/in_english.png)](https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/README_EN.md)

  <p align="center">
    Проект пользовательского ремастера / патча для игры Ex Machina.
    <br />
    <a href="https://discord.gg/jZHxYdF"><img src="https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/git_assets/discord_logo_xs.png" alt="Discord link"><strong>  Следить за разработкой на нашем Discord сервере »</strong></a>
    <br />
    <br />
    <a href="https://github.com/DeusExMachinaTeam/EM-CommunityPatch/issues" alt="Report bug on GitHub">🐛Создать багрепорт</a>
    ·
    <a href="https://deuswiki.com/w/Community_Remaster"><img src="https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/git_assets/dem_logo_xs.png"> Страница на DeusWiki (только VPN)</a>
  </p>
</div>

<!-- About the project -->
# Про КомРем и КомПатч

![ComRem main menu Screen shot](src/assets/screen_1.jpg)
*На скриншоте главное меню Комьюнити Ремастера*<br /><br />

&#128312;**Community Patch** - базовая версия, подходящая для играющих на ПК с 4:3 экранами и желающих получить максимально близкий к оригиналу опыт:
* повышает стабильность игры, существенно снижает число вылетов
* исправляет фризы при спавне врагов
* исправляет сюжетные ошибки, катсцены и квесты
* возвращает небольшое количество вырезанного "vanilla-friendly" контента
* улучшена физика авто, убрана "лунная гравитация"
* исправлен сломанный в оригинале широкий FOV
* увеличена максимальная дальность отрисовки
* исправлены ошибки моделей и анимаций

&#128992; **Community Remaster** - расширение Комьюнити Патча, идеален для ПК с широкоформатными экранами. Помимо всех исправлений КомПатча, так же:
* переработан интерфейс игры для адаптации под 16:9 разрешения вплоть до 4K
* добавлены новые, высококачественные модели и анимации для части оружия и авто, больше красок для новых авто
* улучшена графика, шейдеры, некоторые текстуры оригинала
* автором оригинального саундтрека записан ремастер части музыки

...и множество других изменений!

Исчерпывающий список доступен при установке в мод менеджере ComMod или в файле [change_list_ru.md на Github](https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/src/assets/change_list_ru.md)

</br>

&#x1F53B; Важно! &#x1F53B;
* Установка Community Patch / Remaster возможна **только на no-DRM версию 1.02** и только с помощью менеджера модов ComMod! Это необходимо, потому как мы побайтово патчим exe игры, и все доступные изменения возможны только на 1.02. **Мы рекомендуем использовать русскую Steam версию для установки**. Другой вариант: распакованная версия с Антологии Ex Machina.
* Установка Community Patch / Remaster возможна **только на 64 битных версиях Windows 8, 10 или 11**!

<p align="right">(<a href="#top">перейти наверх</a>)</p>

# Установка
## Простая установка
В целом нет ничего сложного в установке КомРема/Патча и совместимых с ним модов.

* Скачайте архив с модом и мод менеджер ComMod, не распаковывайте архив с модом самостоятельно

* Создайте папку где будет храниться менеджер модов и его файлы.

* Запустите менеджер модов ![DeusExMachina logo](git_assets/dem_logo_xs.png)  **commod.exe**, на экране настроек укажите папку где в дальнейшем будут храниться файлы менеджера модов, в том числе моды, например ту же самую куда вы поместили сам commod.exe.

* Укажите путь к распакованной игре версии 1.02. Если игру вы установили из Steam, то можно будет выбрать её из списка автоматически найденных копий игры.

* Добавьте в библиотеку скачанный архив с Community Remaster/Patch на странице локальных модов. (Если вы распаковали архив, то можете вручную скопировать распакованную папку в папку "mods" появившуюся в выбранном вами ранее пути хранилища файлов ComMod)

* Нажмите кнопку "Распаковать", затем "Установить" - выберите вариант и опции которые вам нравятся.

После установки, запускать игру можно из ComMod, а можно из Steam или по ярлыку.

Установка других модов совместимых с ComMod и Community Remaster/Patch проводится точно так же.

<hr>
<div align="center">
  <b>Свежий релиз:</b>

  [![Eng Readme](git_assets/download_ru.png)](https://github.com/DeusExMachinaTeam/EM-CommunityPatch/releases/tag/v1.14.1-240403a)

</div>

![Community Remaster installation](git_assets/patcher_tutorial.gif)

*Процесс установки Community Remaster с помощью ComMod.*

## Видео про установку
Если у вас возникнут затруднения с установкой, мы можете обратиться к видео записанному ютубером **Скиталец**, показывающим процесс в деталях. **ОБРАТИТЕ ВНИМАНИЕ: видео слегка устарело, в данный момент не нужно ничего вручную распаковывать во время установки. Вы скачиваете два файла: менеджер и архив с модом, архив за вас распакует сам менеджер в процессе установки!**

[![youtube][youtube_logo_sml] Смотреть на YouTube](https://www.youtube.com/watch?v=VhNGPhU_5mk)


</br>
&#x1F53B; Важно! &#x1F53B;
<ol>
<b>commod.exe</b> - инсталлятор и менеджер модов, который может вызывать ложные срабатывания антивирусов.
Инсталлятор в процессе работы побайтово патчит оригинальный exe игры, копирует файлы патча\ремастера в правильном порядке, а также редактирует некоторые игровые файлы. К сожалению, как специфика работы (редактирование другого exe), так и то, что инсталлятор написан на Python, означает, что вам, возможно, понадобится добавить файл в исключения антивируса. Приносим свои извинения за неудобства, вирусов файл не содержит.
</ol>
<p align="right">(<a href="#top">перейти наверх</a>)</p>



# Скриншоты:
> ![Van and HD interface](src/assets/screen_2.jpg)
*Новый Вэн, новый ПКТ, все элементы интерфейса отображаются в высоком качестве и не растянуты [HD машины, HD пушки - опции при установке КомРема]*

<br />

> ![Lorry and new weapons](src/assets/screen_3.jpg)
*Новый Молоковоз с дополнительной оранжевой раскраской, новый Спектр и Рейнметалл<br />[HD машины, HD пушки - опция при установке КомРема]*

<br />

> ![Shop's HD interface](src/assets/screen_4.jpg)
*HD 16:9 интерфейс магазина и новые иконки товаров Комьюнити Ремастера*

<br />

> ![HD cutscene](src/assets/screen_5.jpg)
*Вступительная катсцена, заметны корректный широкий FOV, качественная отрисовка шрифтов, портрет персонажа не растянут [КомРем]*

<br />

> ![HD dialogs](src/assets/screen_6.jpg)
*HD интерфейс диалогов, портрет персонажа теперь отображается в высоком разрешении [КомРем]* 

<br />

<a href="https://discord.gg/jZHxYdF"><img src="https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/git_assets/dem_logo_xl.png" alt="DEM logo" width="350"/></a>
<a href="https://vk.com/em2ch"><img src="https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/git_assets/em2ch_logo.png" alt="em2ch logo" width="130"/></a>
<a href="https://www.youtube.com/c/rpggameland"><img src="https://github.com/DeusExMachinaTeam/EM-CommunityPatch/blob/main-cleaner/git_assets/pavlikrpg_logo.png" alt="PavlikRPG logo" width="125"/></a>

**Присоединяйтесь к нашим сообществам!**
<p align="right">(<a href="#top">перейти наверх</a>)</p>


## Лицензирование:
<details>
<summary>Информация о лицензии</summary>

<ol>
Проект распространяется в полном виде только на Github.com.
Распространение полных файлов установки и результатов работы установщика Community Patch на других сайтах не разрешено.

Исходный код проекта(все файлы кроме commod.exe) - лицензированы под MIT-подобной лицензией(исключая коммерческое использование) и может быть свободно использован как основа для создания ваших собственных модов. Пожалуйста, не забывайте сохранять текст лицензии и ссылку на проект, если используете его части.

DEM Community Mod Manager (commod.exe) распространяется под собственной лицензией, информация о ней находится в репозитории ComMod.
Для подробностей, пожалуйста, ознакомьтесь с полным текстом лицензии в файле LICENSE.
</ol>
</details>

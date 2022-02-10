# 🎯 Занятие 1: установка и знакомство с интерфейсом

## Скачивание Unity Hub

Переходим на сайт [Unity](https://unity.com/ru) и нажимаем кнопку **Начать**

![unity_site_main.png](/week1/unity_site_main.png)

После перехода на выбор тарифа открываем вкладку **Физическое Лицо** и выбираем вариант **Personal**

![unity_site_tarif](/week1/unity_site_tarif.png)

Далее нам предложит скачать Unity Hub Beta, вместо это отправляемся чуть ниже и качаем стабильную версию для Windows

![unity_site_download](/week1/unity_site_download.png)

После этого устанавливаем и запускаем Unity Hub

## Настройка Unity Hub

Высветится уведомление что нам нужно активировать лицензию:

![unity_hub_no_license](/week1/unity_hub_no_license.png)

Для начала нужно зайти в свой аккаунт Unity (или зарегистрироваться)

![unity_hub_sign_in](/week1/unity_hub_sign_in.png)

Выбирайте нужный вам пункт, после чего произойдет переход в браузер для ввода данных для входа. После входа вас перебросит обратно в Unity Hub, где будет указан ваш аккаунт

Далее нажимаем кнопку **Manage Licenses** и видим список активных лицензий _(верно, он пуст)_

![unity_hub_licenses](/week1/unity_hub_licenses.png)

Тыкаем на **Add license** и выбираем **Personal License**

![unity_hub_activate_licenses](/week1/unity_hub_activate_licenses.png)

Соглашаемся со всеми лицензионными соглашениями и персональная лицензия появляется у нас в списке

## Установка Unity и Visual Stidio

Unity Hub - лишь программа для установки редактора Unity и управления проектами.\
Теперь перейдем к установке нужной версии Unity

> Мы будем использовать LTS версию _(долгосрочная поддержка)_ 2019 года

Открываем вкладку **Installs** - тут будут располагаться все установленные версии Unity\
Затем нажимаем кнопку **Install Editor** для добавления новой версии Unity

![unity_hub_installs](/week1/unity_hub_installs.png)

После этого жмем **Install** напротив нужной нам версии - **2019 LTS**

![unity_hub_version_select](/week1/unity_hub_version_select.png)

Выбираем поддержку разработки под **Android**, и не забудем установить **Visual Studio**, если все еще этого не сделали. После этого жмем привычное **Continue**, одновременно соглашаясь со всеми ~~кругами ада~~ юридическими нюансами :sunglasses:

![unity_hub_modules_select](/week1/unity_hub_modules_select.png)

> Скачивание и установка Unity обычно занимает менее **30 минут**

## Создание своего первого проекта

Во вкладке **Projects** собраны все все проекты которые вы создали либо же открыли\
Для создания нового проект нажмите кнопку **Net Project**

![unity_hub_projects](/week1/unity_hub_projects.png)

Нам предложат выбрать шаблон - пустой 3D проект идеально подойдет.\
Также нам нужно указать название проекта и путь, куда он будет сохранен.

![unity_hub_template_select](/week1/unity_hub_template_select.png)

> Лучше сохранять проект на SSD, чтобы в последующем он открывался максимально быстро

Нажимаем кнопку **Create Project** и ждем создания проект. Он автоматически откроется в редакторе

## Настройка редактора

![unity_editor_main](/week1/unity_editor_main.png)

Наконец мы добрались до самого интересного - редактора Unity :tada: именно тут будет протекать 90% нашей работы

### Рабочая среда по умолчанию

Если панели расположены не так как на скрине (_или вы случайно все сломали_), то неплохо будет выбрать в верхнем меню **Window -> Layout (_комбинацию окон_) -> Default (_по умолчанию_)**

![set_default_layout](/week1/set_default_layout.png)

### Изменение темы редактора

Если же у вас не устраивает светлая тема или наоборот хочется ее поставить :grimacing: то перейдите в верхнее меню **Edit -> Preferences -> Editor Theme -> Light/Dark**

![set_theme](/week1/set_theme.png)

### Связь Unity c Visual Studio

Для этого перейдем в верхнее меню **Edit -> Preferences -> External Tools**\
В открывшемся окне выберем в качестве **External Script Editor** (_редактора кода_) **Visual Studio 2019** и нажмем кнопку **Regenerate Project Files** - это позволит редактору не только открывать отдельные скрипты в Visual Studio, но и воспринимать их как единый проект, а также отображать подсказки по коду (_Intellisense_).

![external_tools](/week1/external_tools.png)

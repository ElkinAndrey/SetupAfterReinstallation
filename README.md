# Настройка после переустановки

## Настройка Windows

### Установка Windows 11 через флешку

#### Создание установочного носителя



#### Установка Windows

1. Через "BIOS" откройте "Boot Menu" (на фото пример с Lenovo IP Gaming 3)  
&nbsp;<img style="max-width: 400px" src="./Images/InstallingWindows/1.jpg">
2. В открывшемся меню выбираем флешку с Windows (здесь выбирается флешка "EFI USB Device (General USB Flash Disk)")  
&nbsp;<img src="./Images/InstallingWindows/2.jpg">
3. Затем откроется меню установщика Windows, где нужно выбрать нужные языки и нажать кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/3.jpg">
4. В открывшемся окне нажмите на кнопку "Установить"  
&nbsp;<img src="./Images/InstallingWindows/4.jpg">
5. В окне с активацией Windows жмете на кнопку "У меня нет ключа продукта"  
&nbsp;<img src="./Images/InstallingWindows/5.jpg">
6. Выбираете операционную систему, которую хотите установить и нажимаете на кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/6.jpg">
7. Принимаете соглашение и нажимаете на кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/7.jpg">
8. Выбираете тип установки "Выборочная: только установка Windows (для опытных пользователей)"  
&nbsp;<img src="./Images/InstallingWindows/8.jpg">  
9. Форматируете все диски нажатием на нужный диск, а затем на кнопку "Форматировать"   
&nbsp;<img src="./Images/InstallingWindows/9.jpg">
10. Сочетанием клавишь "Shift + F10" (для некоторых ноутбуков "Shift + Fn + F10"), запускаете командную строку   
&nbsp;<img src="./Images/InstallingWindows/10.jpg">
11. В консоли вводите команду "diskpart" и нажимаете клавишу "Enter"   
&nbsp;<img src="./Images/InstallingWindows/11.jpg">
12. В консоли вводите команду "list disk" и нажимаете клавишу "Enter"   
&nbsp;<img src="./Images/InstallingWindows/12.jpg">
13. В консоль выведутся все диски компьютера (в моем случае диск с 476 гигабайтами, на который будет установлена Windows и диск на 14 гигабайт, на котором находится установщик Windows). Найдите номер диска, на который хотите установить Windows (в моем случае это "0"). В консоль введите команду "select disk N", где N - это номер диска (в моем случае было введено "select disk 0"). Нажмите клавишу "Enter"   
&nbsp;<img src="./Images/InstallingWindows/13.jpg">
14. Введите в консоль "clean" и нажмите клавишу "Enter"   
&nbsp;<img src="./Images/InstallingWindows/14.jpg">
15. Закройте консоль нажав на красный крестик в правом верхнем углу   
&nbsp;<img src="./Images/InstallingWindows/15.jpg">
16. Нажмите на кнопку "Обновить"   
&nbsp;<img src="./Images/InstallingWindows/16.jpg">
17. После проделанных действий диск будет полностью отформатирован, с диска будут удалены ненужные директории. Нажмите на кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/17.jpg">
18. После этого начнется установка Windows. Дождитесь, когда Windows будет установлена  
&nbsp;<img src="./Images/InstallingWindows/18.jpg">

#### Настройка Windows

1. Выберете страну и нажмите на кнопку "Да"  
&nbsp;<img src="./Images/InstallingWindows/19.jpg">
2. Выберете раскладку клавиатуры и нажмите на кнопку "Да"  
&nbsp;<img src="./Images/InstallingWindows/20.jpg">
3. В открывшемся окне нажмите на кнопку "Пропустить"  
&nbsp;<img src="./Images/InstallingWindows/21.jpg">
4. Подключитесь к нужному Wifi и нажмите на кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/22.jpg">
5. Нажмите кнопку "Пока пропустить"  
&nbsp;<img src="./Images/InstallingWindows/23.jpg">
6. В разделе "Выбор способа настройки устройства" выберете пункт "Настроить для личного использования"  
&nbsp;<img src="./Images/InstallingWindows/24.jpg">
7. Нажмите кнопку "Войти"  
&nbsp;<img src="./Images/InstallingWindows/25.jpg">
8. Введите адрес электронной почты и нажмите кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/26.jpg">
9. Введите пароль и нажмите кнопку "Вход"  
&nbsp;<img src="./Images/InstallingWindows/27.jpg">
10. Снова введите адрес электронной почты и нажмите кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/28.jpg">
11. Введите код безопасности, который пришел вам на почту и нажмите кнопку "Далее"  
&nbsp;<img src="./Images/InstallingWindows/29.jpg">
12. Нажмите на кнопку "Создать ПИН-код"  
&nbsp;<img src="./Images/InstallingWindows/30.jpg">
13. Введите ПИН-код и нажмите на кнопку "Ок"  
&nbsp;<img src="./Images/InstallingWindows/31.jpg">
14. Снимите все галочки на странице "Выберете параметры конфиденциальности для этого устройства" и нажмите кнопку "Принять"  
&nbsp;<img src="./Images/InstallingWindows/32.jpg">
15. Нажмите на кнопку "Пропустить"  
&nbsp;<img src="./Images/InstallingWindows/33.jpg">
16. Нажмите на кнопку "Пропустить"  
&nbsp;<img src="./Images/InstallingWindows/34.jpg">
17. Дождитесь загрузки Windows  
&nbsp;<img src="./Images/InstallingWindows/35.jpg">
18. После проделанных действий откроется рабочий стол Windows
&nbsp;<img src="./Images/InstallingWindows/36.jpg">

### Настроить Google Chrome

* Установить Chrome [[Скачать](https://www.google.ru/intl/ru/chrome/)]
* Войти в аккаунт an...ir@gmail.com
* Удалить аккаунт Гость
* Сделать браузер по умолчанию 
    * Параметры
    * Приложения
    * Приложения по умолчанию
    * Google Chrome
    * Сделать браузером по умолчанию
* Добавить панель закладок 
    * Открыть настройки в Chrome 
    * Внешний вид
    * Панель закладок
* Добавить все нужные закладки  
  <img src="./Images/CustomizeGoogleChrome/1.png">
* Зайти во все аккаунты на сайтах в закладках
* Скачать расширение для rutracker.org [[Скачать](https://chrome.google.com/webstore/detail/%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF-%D0%BA-%D1%80%D1%83%D1%82%D1%80%D0%B5%D0%BA%D0%B5%D1%80%D1%83/lbdmhpkmonokeldelekgfefldfboblbj/related?hl=ru)]
* Скрыть ярлыки на главной
    * На главной странице нажать "Настроить Chrome" (в правом нижнем углу)
    * Ярлыки
    * Скрыть ярлыки
* Изменить путь загрузки на рабочий стол
    * Открыть настройки в Chrome
    * Скачанные файлы

### Скачивание программ

* Adobe Photoshop CS6  
    * Поменять размерность на пиксели
        * Нажать Ctrl + R
        * Нажать ПКМ на открывшейся линейке
        * Выбрать пиксели
    * Поменять размерность при создании
        * Нажать Ctrl + N
        * Поменять размер ширины и высоты на пиксели
        * Ввести новую ширину и высоту
* Aida 64
* Bandicam
* Blue Stacks [[Скачать](https://www.bluestacks.com/ru/index.html)]
* Compass 3D
    * Открыть папку KOMPAS-3D v21 x64
    * Установить при помощи Setup.exe
    * Открыть папку "!Crack!"
    * Открыть архив "Base_21.0.0_x64_noHASP_2022.07.30"
    * В архиве лежать папки
    * Нужно перейти к файлам в корень каждой из папок
    * Файлы нужно перенести в соответствующие папки в компасе
    * Запустить компас
* CpuZ [[Скачать](https://cpu-z.ru.uptodown.com/windows)] 
* CS GO [   [Скачать](https://store.steampowered.com/app/730/CounterStrike_Global_Offensive/)]
* Da Vinci Resolve [[Скачать](https://www.blackmagicdesign.com/products/davinciresolve)]
* Desk Pins [[Скачать](https://deskpins.softonic.ru/)]
    * Запустить после установки
* Discord [[Скачать](https://discord.com/)]
    * Войти в аккаунт an...ir@gmail.com
* Epic Games [[Скачать](https://www.epicgames.com/store/ru/)]
    * Войти в аккаунт...
* Git [[Скачать](https://git-scm.com/downloads)]
* Inno Setup [[Скачать](https://jrsoftware.org/isdl.php)]
* Minecraft [[Скачать не официально](https://tlauncher.org/)]
* Mini Bin [[Скачать](https://minibin.ru.uptodown.com/windows)]
* Mp3tag [[Скачать](https://www.mp3tag.de/en/download.html)]
* Msi Afterburner [[Скачать](https://ru.msi.com/page/AFTERBURNER)]
* NotePad++ [[Скачать](https://notepad-plus-plus.org/downloads/)]
* OBS [[Скачать](https://obsproject.com/ru)]
* PyCharm [[Скачать](https://www.jetbrains.com/ru-ru/)]
* Python [[Скачать](https://www.python.org/downloads/)]
* QBitTorrent [[Скачать](https://www.fosshub.comqBittorrent.html)]
* QTTapBar [[Скачать](http://qttabbar.wikidot.com/)]
* Resource Hacker [[Скачать](http://www.angusj.com/resourcehacker/)]
* SD Card Formatter [[Скачать](https://www.sdcard.org/downloads/formatter/)]
* ShareX [[Скачать](https://getsharex.com/)]
    * Запустить приложение
    * Поменять папку со скриншотами
        * Настройки приложения
        * В открывшемся окне "Каталоги"
        * Нажать на галочку "Пользовательская папка для скриншотов"
        * Нажать "Обзор" и выбрать нужную папку
    * Изменить задачи после захвата
        * На главной странице нажать на "Задачи после захвата"
        * Выбрать пункты
            * Открыть в редакторе изображений
            * Скопировать изображение в буфер обмена
            * Сохранить изображение в файл
    * Горячие клавиши
        * На главной нажать на "Горячие клавиши"
        * В открывшемся окне дать все разрешения
* SketchUP
* Steam [[Скачать](https://store.steampowered.com/?l=russian)]
    * Войти в аккаунт...
* Sublime Text [[Скачать](https://www.sublimetext.com/download)]
* Vegas Pro 17 [[Скачать](https://www.sublimetext.com/download)]
    * Запустить setup.exe
    * Указать папку установки
    * После установки не запускать файл
    * Открыть файл activation.exe
    * В разделе, в котором нужно указать папку, ввести в ручную папку, в которую была установлена программа
* Visual Studio [[Скачать](https://visualstudio.microsoft.com/ru/)]
* Visual Studio Code [[Скачать](https://code.visualstudio.com/)]
    * Расширения
        * Markdown All in One
* Wallpaper Engine [[Скачать](https://store.steampowered.com/app/431960/Wallpaper_Engine/)]
* Warface [[Скачать](https://ru.warface.com/)]
* Win Rar
* Wiz Tree [[Скачать](https://diskanalyzer.com/)]
* Zoom [[Скачать](https://zoom.us/download)]

### Настройка оформления Windows

#### Оформление

* Изменить панель задач
    1. Открыть настройки параметров
        * Персонализация
        * Панель задачи
    2. Отключить
        * Поле поиска
        * Представление задач
        * Мини-приложения
        * Чат
    3. Включить только дополнительные значки
        * DeskPins
        * MiniBin
    4. Переместить панель в центр
        * Поведение панели задач
        * Выравнивание панели : слева
    5. Оставить только значки
    <img src="./Images/\CustomizingWindowsAppearance/1.png">
* Изменить пуск
    * Открепить от начального экрана все приложения
    * Изменить настройки
        * Параметры
        * Персонализация
        * Пуск
        * Оключить
            * Показ приложений
            * Показ предложений
        * Включить
            * Открывать пуск в полноэкранном режиме
    * Добавить все нужные приложения
* Изменить обои
* Перекинуть с флешки все старые файлы

#### Инструкции

* Поменять открытие "Проводника" на открытие "Этого компьютера"
    * Открыть проводник
    * Нажать на 3 точки (Подробнее)
    * Параметры
    * В новом окне выбрать вкладку общие
    * В разделе "Открыть проводник для" установить значение "Этот компьютер"
* Отключить автоматический запуск приложений
    * Диспетчер задач
    * Автозагрузка приложений
* Отключить уведомления
    * Система
    * Уведомления
* Показывать расширения файлов
* Отключить анимации
    * Зайти в этот компьютер
    * Свойства
    * Дополнительные параметры
    * Быстродействие
* Открепить от рабочего стола корзину
    * Параметры
    * Персонализация
    * Темы
    * Параметры значков рабочего стола
* Выключить автоматическое погасание экрана
    * Панель управления
    * Оборудование и звук
    * Электропитание
    * Настройка отключения дисплея
* Поставить выключение на кнопку
    * Панель управления
    * Оборудование и звук
    * Электропитание
    * Действия кнопок питания
* Поменять букву диска
    * Нажать Win + R
    * Ввести diskmgmt.msc
* Выйти с учетной записи Microsoft
    * Параметры
    * Учетная запись
    * Ваши данные
    * Выйти из учетной записи
* Поменять тему Windows	
    * Параметры
    * Персонализация
    * Цвета
    * Выбор цвета
* Поменять время
* Поменять имя администратора
    * Ввести "⠀"
* Добавить "Этот компьютер" на панель задач
    1. На рабочем столе нажать ПКМ и выбрать "Создать -> Ярлык"
    2. Указать в расположении объекта explorer.exe "::{20D04FE0-3AEA-1069-A2D8-08002B30309D}"
    3. Если не удалось, то:  
        a) Открыть "Этот компьютер"  
        b) Нажать ПКМ на строку с путем файла, где написано "Этот компьютер"  
        c) В выпадающем меню выбрать "Копировать адрес"  
        d) Вставить адрес в окне создания ярлыка  
        e) В этом же окне заменить надписть "Этот компьютер" на надпись "explorer.exe " (обязательно с пробелом в конце) (пример: explorer.exe "::{20D04FE0-3AEA-1069-A2D8-08002B30309D}")  
    4. Нажать далее
    5. Нажать готово
    6. Нажмите на созданный ярлык ПКМ и выберете "Свойства"
    7. Нажмите "Сменить значок"
    8. В строку "Искать значки в следующем файле" введите "%SystemRoot%\System32\SHELL32.dll"
    9. Выберете нужный значок 
    10. Нажмите "Ок"
    11. Нажмите на ярлык ПКМ, выберите "Показать дополнительные параметры", нажмите на "Закрепить на панели задач"
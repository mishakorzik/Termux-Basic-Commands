---
  #### Основні команди.
  * `Ls - список файлів і каталогов`
  * `Ls -al - форматований список з прихованими каталогами та файламі`
  * `Cd dir - змінити директорію на dir`
  * `Cd - змінити на домашній Каталог`
  * `Pwd - показати поточний Каталог`

  ---
  #### команди з файлами.
  * `Mkdir dir - створити каталог dir`
  * `Rm file - видалити файл`
  * `Rm -r dir - видалити каталог dir`
  * `Rm -r -f / path - видалити каталог dir`
  * `Rm -f file - видалити форсовано файл`
  * `Rm -rf dir - видалити форсовано каталог dir`
  * `Cp file1 file2 - скопіювати file1 в file2`
  * `Cp -r dir1 dir2 - скопіювати dir1 в dir2;  створить каталог dir2, якщо він не существует`
  * `Mv file1 file2 - перейменувати або перемістити file1 в file2.  якщо file2 існуючий каталог - перемістити file1 в каталог file2`
  * `Ln -s file link - створити символічне посилання link до файлу file`
  * `Touch file - створити файл`

  ---
  #### інформація про файлах
  * `Cat> file - направити стандартний ввід в файл`
  * `More file - вивести вміст файла`
  * `Head file - вивести перші 10 рядків файла`
  * `Tail file - вивести останні 10 рядків файла`
  * `Tail -f file - вивести файл у міру зростання, починає з останніх 10 строк`

  ---
  #### команди для управління процессамі`
  * `Ps - вивести ваші поточні активні процесси`
  * `Top - показати всі запущені процесси`
  * `Kill pid - вбити процес з id pid`
  * `Killall proc - вбити всі процеси з ім'ям proc`
  * `Bg - список зупинених і фонових завдань;  продовження виконання зупиненої завдання в фоне`
  * `Fg - виносить на передній план останні задачі`
  * `Fg n - винести завдання n на передній план`
  * Восьмирічний файл `chmod - змінити права файлу на восьмеричний, окремо для користувача, групи і для всіх додаванням:`
  4 - читання (r)
  2 - запис (ш)
  1 - виконання (x)

  ---
  #### приклад
  * `Chmod 777 - читання, запис, виконання для всех`
  * `Chmod 755 - rwx для власників, rx для групи і`
  Додаткові опції: man chmod.

  ---
  #### команди для SSH

  * `Ssh user @ host - підключиться до host як user`
  * `Ssh -p port user @ host - підключиться до host на порт порт як user`
  * `Ssh-copy-id user @ host - ваш ключ на host, щоб додати логін без пароля і по ключам`

  ---
  #### команди пошуку
  * `Grep pattern files - шукати файли шаблонов`
  * `Grep -r pattern dir - шукати рекурсивно pattern в dir`
  * `Команда |  grep pattern - шукати шаблон у висновку command`
  * `Locate file - знайти усі файли з ім'ям file`

  ---
  #### системна інформація
  * `Date - вивести поточну дату і время`
  * `Cal - вивести календар на поточний месяц`
  * `Uptime - показати поточний аптайм`
  * `Whoami - ім'я, під яким ви залогінени`
  * `Uname -a - показати інформацію про ядре`
  * `Cat / proc / cpuinfo - інформація ЦПУ`
  * `Cat / proc / meminfo - інформація про памяті`
  * `Man command - показати мануал для command`
  * `Df - показати інф.  про пам'ять дісков`
  * `Du - вивести« вагу »поточного каталога`
  * `Free - використання пам'яті і swap`
  * `Whereis app - можливе розташування програми app`
  * `Which app - яка програма буде запущено по умолчанію`

  ---
  #### архівування
  * `Tar cf file.tar files - створити tar-архів з файлом під іменем tar.tar наруш files`
  * `Tar xf file.tar - розпакувати file.tar`
  * `Tar czf file.tar.gz files - створити архів tar з стисненням Gzip`
  * `Tar xzf file.tar.gz - розпакувати tar з Gzip`
  * `Tar cjf file.tar.bz2 - створити архів tar з стисненням Bzip2`
  * `Tar xjf file.tar.bz2 - розпакувати tar з Bzip2`
  * `Gzip file - стиснути файл і перейменувати в file.gz`
  * `Gzip -d file.gz - розтиснути file.gz в файл`

  ---
  #### мережа
  * `Ping host - пропінгувати хост і вивести результат`
  * `Whois domain - отримати інформацію whois для домена`
  * `Dig domain - отримати DNS інформацію про домене`
  * `Dig -x host - реверсивно шукати хост`
  * `Wget file - завантажити файл`
  * `Wget -c file - продовжити зупинену закачку`

  ---
  #### установка пакетів і робота з ними
  * `Pkg install package - встановлює пакет`
  * `Pkg remove package - видаляє пакет`
  * `Pkg search package - шукає в репозиторії пакет`
  * `Pkg list-installed - виведе список загрузок`

  ---
  #### установка з початкових кодів.
  * `./configure`
  * `Make`
  * `Make install`

  установка пакетів deb

  * `Dpkg -i pkg.deb - встановити пакет (Debian)`

  ---
  #### команди з android
  * `Adb (Android Debug Bridge) - утиліта для налагодження Андроїд пристроїв з ПК`
  * `Pm - менеджер пакетов`
  * `Pm list packages (дивимося список завантажених пакетів)`
  * `Am - менеджер для запуску і зупинки пріложеній`

  ---
  #### гарячі клавіші
  * `Ctrl + C завершити - поточну команду`
  * `Ctrl + Z - зупинити поточну команду, продолжть з fg на передньому плані або bg в фоне`
  * `Ctrl + D - разлогініться, те ж саме, що і exit`
  * `Ctrl + W - видалити одне слово в поточній строке`
  * `Ctrl + U - видалити строку`
  * `!!  - повторити останню команду`
  * `Exit - разлогініться`

#### Basic commands with termux.
#### if you want to translate the page then click on the view on github button and you will be redirected to the github site and will write se laungles and select the desired language. Thanks for understanding.

----
#### Basic commands.

* `ls – список файлов и каталогов`
* `ls -al – форматированный список со скрытыми каталогами и файлами`
* `cd dir – сменить директорию на dir`
* `cd – сменить на домашний каталог`
* `pwd – показать текущий каталог`

---
#### commands with files.
* `mkdir dir – создать каталог dir`
* `rm file – удалить file`
* `rm -r dir – удалить каталог dir`
* `rm -r -f /path – удалить каталог dir`
* `rm -f file – удалить форсированно file`
* `rm -rf dir – удалить форсированно каталог dir`
* `cp file1 file2 – скопировать file1 в file2`
* `cp -r dir1 dir2 – скопировать dir1 в dir2; создаст каталог dir2, если он не существует`
* `mv file1 file2 – переименовать или переместить file1 в file2. если file2 существующий каталог — переместить file1 в каталог file2`
* `ln -s file link – создать символическую ссылку link к файлу file`
* `touch file – создать file`

---
#### files info
* `cat > file – направить стандартный ввод в file`
* `more file – вывести содержимое file`
* `head file – вывести первые 10 строк file`
* `tail file – вывести последние 10 строк file`
* `tail -f file – вывести содержимое file по мере роста, начинает с последних 10 строк`

---
#### commands for process management`
* `ps – вывести ваши текущие активные процессы`
* `top – показать все запущенные процессы`
* `kill pid – убить процесс с id pid`
* `killall proc – убить все процессы с именем proc`
* `bg – список остановленных и фоновых задач; продолжить выполнение остановленной задачи в фоне`
* `fg – выносит на передний план последние задачи`
* `fg n – вынести задачу n на передний план`
*`chmod octal file – сменить права file на octal, раздельно для пользователя, группы и для всех добавлением:`
4 – чтение (r)
2 – запись (w)
1 – исполнение (x)

---
#### example
* `chmod 777 – чтение, запись, исполнение для всех`
* `chmod 755 – rwx для владельца, rx для группы и остальных`
Дополнительные опции: man chmod.

---
#### commands for SSH

* `ssh user@host – подключится к host как user`
* `ssh -p port user@host – подключится к host на порт port как user`
* `ssh-copy-id user@host – добавить ваш ключ на host для user чтобы включить логин без пароля и по ключам`

---
#### search commands
* `grep pattern files – искать pattern в files`
* `grep -r pattern dir – искать рекурсивно pattern в dir`
* `command | grep pattern – искать pattern в выводе command`
* `locate file – найти все файлы с именем file`

---
#### system info
* `date – вывести текущую дату и время`
* `cal – вывести календарь на текущий месяц`
* `uptime – показать текущий аптайм`
* `whoami – имя, под которым вы залогинены`
* `uname -a – показать информацию о ядре`
* `cat /proc/cpuinfo – информация ЦПУ`
* `cat /proc/meminfo – информация о памяти`
* `man command – показать мануал для command`
* `df – показать инф. о использовании дисков`
* `du – вывести “вес” текущего каталога`
* `free – использование памяти и swap`
* `whereis app – возможное расположение программы app`
* `which app – какая app будет запущена по умолчанию`

---
#### archiving
* `tar cf file.tar files – создать tar-архив с именем file.tar содержащий files`
* `tar xf file.tar – распаковать file.tar`
* `tar czf file.tar.gz files – создать архив tar с сжатием Gzip`
* `tar xzf file.tar.gz – распаковать tar с Gzip`
* `tar cjf file.tar.bz2 – создать архив tar с сжатием Bzip2`
* `tar xjf file.tar.bz2 – распаковать tar с Bzip2`
* `gzip file – сжать file и переименовать в file.gz`
* `gzip -d file.gz – разжать file.gz в file`

---
#### network
* `ping host – пропинговать host и вывести результат`
* `whois domain – получить информацию whois для domain`
* `dig domain – получить DNS информацию domain`
* `dig -x host – реверсивно искать host`
* `wget file – скачать file`
* `wget -c file – продолжить остановленную закачку`

---
#### installation of packages and work with them
* `pkg install package - устанавливает package`
* `pkg remove package - удаляет package`
* `pkg search package - ищет в репозитории package`
* `pkg list-installed - выведет список установленных пакетов`

---
#### installation from source codes.
* `./configure`
* `make`
* `make install`

installation of deb packages

* `dpkg -i pkg.deb – установить пакет (Debian)`

---
#### commands with android
* `adb (Android Debug Bridge) — утилита для отладки Андроид устройств с ПК`
* `pm — менеджер пакетов`
* `pm list packages (смотрим список установленных пакетов)`
* `am — менеджер для запуска и остановки приложений`

---
#### keyboard shortcuts
* `Ctrl+C – завершить текущую команду`
* `Ctrl+Z – остановить текущую команду, продолжть с fg на переднем плане или bg в фоне`
* `Ctrl+D – разлогиниться, тоже самое, что и exit`
* `Ctrl+W – удалить одно слово в текущей строке`
* `Ctrl+U – удалить строку`
* `!! — повторить последнюю команду`
* `exit – разлогиниться`

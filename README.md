## Краткое описание функционала скрипта:

Этот скрипт предназначен для копирования всех файлов из исходной директории в целевую директорию.
Если файл с таким же именем уже существует в целевой директории, то к имени файла добавляется метка времени, чтобы избежать перезаписи.


## Требования

Для работы скрипта требуется наличие интерпретатора bash и операционная система, поддерживающая его выполнение (например, Linux или MacOS).


## Использование

1. Откройте терминал.
2. Перейдите в директорию, где находится скрипт.
3. Выполните скрипт, передав ему два аргумента:
4. Первый аргумент: путь к исходной директории, откуда будут копироваться файлы.
5. Второй аргумент: путь к целевой директории, куда будут копироваться файлы.
6. Пример команды для запуска скрипта:


## Пример команды для запуска скрипта:


Представим, что у нас есть директория /home/user/Documents с такой структурой:
/home/user/Documents/

├── report.txt

├── data.csv

└── notes/

    ├── meeting_notes.txt

    └── ideas.txt
    


Запуск скрипта для копирования файлов из /home/user/Documents в /home/user/Backup выглядел бы так:
./bash_script.sh /home/user/Documents /home/user/Backup/

После выполнения скрипта структура целевой директории /home/user/Backup может выглядеть так:

/home/user/Backup/

├── report.txt

├── data.csv

├── meeting_notes.txt

├── ideas.txt


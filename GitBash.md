1) Посмотреть где я
   pwd
2) Создать папку
    mkdir dir_1
3) Зайти в папку
   cd dir_1
4) Создать 3 папки
   mkdir dir_2, dir_3, dir_4
5) Зайти в любую папку
    cd dir_3
6) Создать 5 файлов (3 txt, 2 json)
    touch test_1.txt, test_2.txt, test_3.txt
    touch test_4.json, test_5.json
7) Создать 3 папки
   mkdir dir_5
   mkdir dir_6
   mkdir dir_7
8) Вывести список содержимого папки
    ls -la
9) + Открыть любой txt файл
   cat > test_1.txt
10) + написать туда что-нибудь, любой текст
    + сохранить и выйти
    test test
    ctrl + D
12) Выйти из папки на уровень выше
    cd ..
13) переместить любые 2 файла, которые вы создали, в любую другую папку
     mv test_1.txt test_2.txt dir_5
14) скопировать любые 2 файла, которые вы создали, в любую другую папку
    cp test_4.json test_5.json dir_5
15) Найти файл по имени
    find -name test_3.txt
6) просмотреть содержимое в реальном времени (команда grep)
    grep -R test_1 dir_3
17) вывести несколько первых строк из текстового файла
    grep -R t dir_3/dir_5

    dir_3/dir_5/test_1.txt:the firso
    dir_3/dir_5/test_1.txt:the first two
18) вывести несколько последних строк из текстового файла
    grep -R l dir_3/dir_5

    dir_3/dir_5/test_1.txt:fdgdslkfmfls
    dir_3/dir_5/test_1.txt:fjknklhg
    dir_3/dir_5/test_1.txt:kfrgl
    dir_3/dir_5/test_1.txt:fmblkmhklg
    dir_3/dir_5/test_1.txt:fdkgmfl
    dir_3/dir_5/test_1.txt:flgmh
    dir_3/dir_5/test_1.txt:hmfl
19) просмотреть содержимое длинного файла (команда less)
    less test_1.txt

    the firso
    the first two
    ghfh
    eeeeeeeee
    4wreggg
    hjk
    fdgdslkfmfls
    fd;;;;;;;;;;;
    bmbmvbb
    sadkfdg
    dkfjkg
    fdkgmfb
    fjknklhg
    kfrgl
    dkmvkb
    dkejfkfmg
    fmblkmhklg
    fdkgmfl
    flgmh
    hmfl
20) вывести дату и время
    date



   
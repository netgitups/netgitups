# Домашнее задание к занятию "`Git`" - `Азимов Руслан`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`https://github.com/netgitups/first_git.git ---> commit = a4cecab5c6d27fe80a95a9cee04ffdd961f0686e `

1. `Клонируем репозиторий на локальную машину`
2. `Редактируем README.md`
3. `Вносим изменения`
4. `Создаем коммит`
5. `Отправляем изменения в репозиторий`

```
Код...
#git clone https://github.com/netgitups/first_git.git
Редактируем README.md
#git add README.md
#git commit -m 'First commit'
#git push
```

`При необходимости прикрепитe сюда скриншоты
![1.Задание](https://github.com/netgitups/netgitups/blob/main/img/1.png)`


---

### Задание 2

`https://github.com/netgitups/first_git.git  ---> 97580644be52af403d1d0733464192216781a352`

1. `Создание файла .gitignore`
2. `Добавляем значение в .gitignore`
3. `Добавляем файл`
4. `Комитем`
5. `Пушим`


```
Код...

#touch .gitignore
#*.рус,cache/
#git add .gitignore
#git commit -m 'Second commit'
#git push
```

`При необходимости прикрепитe сюда скриншоты
![2.Задание](https://github.com/netgitups/netgitups/blob/main/img/2.png)`


---

### Задание 3

`https://github.com/netgitups/first_git.git  ---> ветка main: 3d19f5071bfd182dba2fcda04da66f6e3ed0b4f1 - 7db88c54a1a5227aa2b30d8e1886d36397ff1a9c ветка dev: 97580644be52af403d1d0733464192216781a352 - 79233618c56f657ffce0ce8a6a5faf4d97c4afed `         

1. `Создаем новую ветку dev`
2. `Переключаемся на ветку dev`
3. `Создаем файл test.sh`
4. `Комитем 3 раза`
5. `Переключаемся на ветку main`
6. `Создаем файл main.sh`
7. `Комитем, обьединяем ветки`

```
Код...
#git checkout -b dev 
#git push -u https://github.com/netgitups/first_git.git  dev
#git branch
#touch test.sh   ---> редактируем и вносим изменения
#git add test.sh
#git commit -m 'Third commit'
#git push
#git add test.sh
#git commit -m 'Third commit_1'
#git push
#git add test.sh
#git commit -m 'Third commit_2'
#git push
#git switch main
#touch main.sh   ---> редактируем и вносим изменения
#git add main.sh 
#git commit -m 'Third commit_main'
#git push
#git remote add origin https://github.com/netgitups/first_git.git
#git push origin main
#git merge dev
#git add .
#git commit -m 'мердж dev ветки в основную'
#git push origin main
```

`При необходимости прикрепитe сюда скриншоты
![3_1.Задание](https://github.com/netgitups/netgitups/blob/main/img/3_1.png)
![3_2.Задание](https://github.com/netgitups/netgitups/blob/main/img/3_2.png)`

### Задание 4

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

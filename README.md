# LR6
Лабораторная работа №6

Создание копии в личное хранилище из https://github.com/Kurtyanik/LR6/.

![Безымянный](https://user-images.githubusercontent.com/118631634/202870008-545bf4d3-741d-4c97-a6bb-1de30109f56d.png)

![Безымянный 1](https://user-images.githubusercontent.com/118631634/202870051-7ab8eb66-132a-4cfa-b244-63f0117e96bf.png)

Использование команд git config —global user.name и git config —global user.email для клиента Git и вывод своих данных из GitHub.

![2](https://user-images.githubusercontent.com/118631634/202870060-a07b5085-2765-4674-a7a2-469aa5730ac3.png)

Клонирование удаленного репозитория, используя команду git clone.

![3](https://user-images.githubusercontent.com/118631634/202870068-6b25e334-14c0-43f1-98dc-9a0cb07fd205.png)

Добавление файла через интерфейс GitHub. Далее переход в директорию LR6 командой cd LR6 для дальнейшей работы с файлами.

![4](https://user-images.githubusercontent.com/118631634/202870076-0d4b6f4b-e882-407b-a332-2674f75089ad.png)

Подтягивание изменения из веб-интерфейса GitHub для клиента Git с помощью команды git pull.

![5](https://user-images.githubusercontent.com/118631634/202870115-cde004b2-bef9-434c-92fd-eb93d1ead47f.png)

Просмотр коммитов ветки master, используя команду git log.

![6](https://user-images.githubusercontent.com/118631634/202870179-126f9cf7-e73f-4675-8cf0-6e9d489c53da.png)

Просмотр задержания ветки в текущем репозитории команды git branch.

![7](https://user-images.githubusercontent.com/118631634/202870191-aecae337-0abe-4776-8bc5-fe7f0f5f11ef.png)

Переход в ветку branch1 командой git checkout branch1.


![8](https://user-images.githubusercontent.com/118631634/202870222-d065e5ff-749e-422f-9faf-a713a23cc32e.png)

Просмотр коммитов ветки branch1 с помощью команды git log.


![9](https://user-images.githubusercontent.com/118631634/202870229-6e1a30fe-eb07-4715-a8a8-ae0682ee8dd9.png)

Подробный просмотр коммитов с помощью команды git log -p.

![10](https://user-images.githubusercontent.com/118631634/202870232-863650f3-3386-40a6-9d09-83b0cd8dede6.png)

Возвращение в ветку мастера.

![11](https://user-images.githubusercontent.com/118631634/202870235-ee4a004f-8ffb-44ac-b50b-f10f09f45ddf.png)

Выполнение слияния в ветке master, используя команду git merge branch1.

![12](https://user-images.githubusercontent.com/118631634/202870259-9e24e5d4-a1ef-4aa1-b107-ba284fcf1276.png)

Из-за того, что файл mergefile.txt не отслеживается используется команда git status для отображения состояния рабочего каталога.

![13](https://user-images.githubusercontent.com/118631634/202870272-34e0d008-81cf-4170-9d2b-9fa6cba47d67.png)

Добавление файла для создания git add mergefile.txt.

![14](https://user-images.githubusercontent.com/118631634/202870279-ef1ad341-4bf3-45c2-a560-908346df0e6a.png)

Проверка отслеживания файла.

![15](https://user-images.githubusercontent.com/118631634/202870321-35d62caa-0d8e-40b4-9230-110f802a130d.png)

После разрешения конфликта оставляем коммит при помощи команды git commit -m "Ветки".

![16](https://user-images.githubusercontent.com/118631634/202870330-8c4c918f-c2b9-4462-9309-226848197a32.png)

Удаление побочной ветки после успешного слияния при помощи команды git branch -d branch1

![17](https://user-images.githubusercontent.com/118631634/202870337-1ef36158-61d3-4784-9a64-dd989a670d47.png)

Создание текстовых файлов и комментариев для них через терминал. При создании текстов используется команда echo hello > change1.txt, зафиксируем его git add change_1.txt. Написание комментария с помощью команды git commit -m "Change_1.txt". Повторение алгоритма еще раз, название публикации - change_2.txt.

![18](https://user-images.githubusercontent.com/118631634/202870340-e32db3df-46d3-4549-8307-7f9507e60ccd.png)

Просмотр комментариев, исользуя команду git log.

![19](https://user-images.githubusercontent.com/118631634/202870348-79f3750a-3de4-4750-b011-911e4fc13c66.png)

Создание "хард" отката коммита. Ввод git reset —hard HEAD~1

![20](https://user-images.githubusercontent.com/118631634/202870353-1b962008-3ee3-423b-b9fe-e5ff3d25e89c.png)

Создание ветки для отчета и переход в git branch report.


![22](https://user-images.githubusercontent.com/118631634/202870906-82246e16-a94a-424e-8772-11f56fc8c400.png)

Получившаяся итоговая история операций.

![23](https://user-images.githubusercontent.com/118631634/202870909-db34af36-1edd-4416-b576-480b48acac41.png)

В конце работы необходимо отправить все локальные изменения в сетевое хранилище GitHub командой git push.

=)

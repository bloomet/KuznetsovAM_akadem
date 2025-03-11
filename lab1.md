## Лабораторная работа 1

# 1. Cоздать файл.
   Ввожу команду
   ```bash
   touch script.bash
   ```
   Файл создается

   
![image](https://github.com/user-attachments/assets/832ee1d7-b20e-446e-b267-a30c0ee77735)


# 2. Открываю файл
   Ввожу команду
   ```bash
   gedit script.bash
   ```
   Команду вывести не выходит - терминал не находит команду и рекомендует ее докачать, что я и делаю с помощью команды
   ```bash
   sudo apt install gedit
   ```
   После чего еще раз пробую ввести ту же самую команду. В этот раз все получается)

   
![image](https://github.com/user-attachments/assets/582ed952-d869-4b88-a2a4-91edaa2ff3c4)


# 3. Создание скрипта и его запуск
   В файле пишу команду echo "Welcome to ITMO University"
   После чего сохраняю файл и приступаю к его запуску, вписав в терпинал команду bash script.bash
   На терминал выводиться текст из файла

   ![image](https://github.com/user-attachments/assets/7a689162-8815-431e-841a-094366001456)

# 4. Решение задачи
   После поиска информации в гугле открываю файл, задаю в него переменную name, благодаря $*, в name будет записана строчка, которую я введу в терминале при вызове этого скрпита.

    ![image](https://github.com/user-attachments/assets/fb23b117-9299-4ad1-ad09-59c1dea80a55)

   После чего запускаю свой скрипт и фиксирую результат 

   ![image](https://github.com/user-attachments/assets/948a219a-5cc4-48ae-aebd-818bb8413ab6)



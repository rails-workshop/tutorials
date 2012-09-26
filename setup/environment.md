# Настройка окружения

Это руководство позволит поможет Вам настроить окружение для успешной работы в рамках курса обучения языку Ruby и/или фреймворку Ruby on Rails

## Цель

В конечном итоге на Вашем компьютере должны быть установлены:

  * Git
  * Ruby v1.9
  * Rails 3.2
  * Текстовый редактор (желательно предназначенный для работы с исходным кодом)
  
## Windows

Установить необходимое ПО на Windows довольно просто. Скачайте с сайта http://railsinstaller.org/ railsinstaller-2.1.0.exe и запуститете его. Далее следуйте инструкции:
  
   1.  Нажмите кнопку Next.
    
       ![Шаг 1](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step0.png "Шаг 1")

   1.  Выбирите I accept all of the Licenses и нажмите кнопку Next.

       ![Шаг 2](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step1.png "Шаг 2")

   1.  Выберити путь куда будет произведена установка. *NB* путь не должен соджержать пробелы. Нажмите кнопку Install.
    
       ![Шаг 3](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step2.png "Шаг 3")
        
   1.  Дождитесь окончания копирования файлов.
    
       ![Шаг 4](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step3.png "Шаг 4")
        
   1.  Снемите отметку с Configure git and ssh when installation has completed и нажмите кнопку Next.
    
       ![Шаг 5](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step4.png "Шаг 5")
        
Что бы проверить, что все установилось корректно сделайте следующее:

   1.  Запустите командную строку Windows (cmd.exe)

       ![Командная строка](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step5.png)
        
   1.  Выполните следующие команды:
       * ruby -v
       * gem -v
       * rails -v
        
   1.  Результат должен быть примерно таким:
        
       ![Результат работы](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step6.png)
        

# Настройка окружения

Это руководство позволит поможет Вам настроить окружение для успешной работы в рамках курса обучения языку Ruby и/или фреймворку Ruby on Rails.

## Цель

В конечном итоге на Вашем компьютере должны быть установлены:

  * Git
  * Ruby v1.9
  * Rails 3.2
  * Текстовый редактор (желательно предназначенный для работы с исходным кодом)

## Текстовый редактор

[IDE](http://ru.wikipedia.org/wiki/IDE) не очень популярны среди разработчиков на Ruby. Подавляющее большинство разработчиков используют редакторы 
[Vim](http://www.vim.org/) или [Emacs](http://www.gnu.org/software/emacs/). Вы можете использовать любой текстовый редактор к которому вы привыкли и который вы хорошо знаете.
Лучше если в нем будет реализована подсветка синтаксиса (Ruby) и удобная навигация по дереву каталогов. 

Я рекомендую обратить внимание на редактор [Sublime Text](http://www.sublimetext.com/). Это кроссплатформенный редактор с большими возможностями и неограниченным периодом пробного использования.

## Windows

### Ruby и Rails

Установить Ruby и Rails на Windows довольно просто. Скачайте с сайта http://railsinstaller.org/ railsinstaller-2.1.0.exe и запуститете его. Далее следуйте инструкции:
  
1. Нажмите кнопку Next.
    
    ![Шаг 1](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step0.png "Шаг 1")

1. Выбирите I accept all of the Licenses и нажмите кнопку Next.

    ![Шаг 2](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step1.png "Шаг 2")

1. Выберити путь куда будет произведена установка. *NB* путь не должен соджержать пробелы. Нажмите кнопку Install.
    
    ![Шаг 3](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step2.png "Шаг 3")
        
1. Дождитесь окончания копирования файлов.
    
    ![Шаг 4](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step3.png "Шаг 4")
        
1. Снемите отметку с Configure git and ssh when installation has completed и нажмите кнопку Next.
    
    ![Шаг 5](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step4.png "Шаг 5")
    

Что бы проверить, что все установилось корректно сделайте следующее:

1. Запустите командную строку Windows (cmd.exe)

    ![Командная строка](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step5.png "Командная строка")
        
1. Выполните следующие команды:

        ruby -v
        gem -v
        rails -v
        
1. Результат должен быть примерно таким:
        
    ![Результат работы](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step6.png "Результат работы")
    

## Mac OS

### Ruby и Rails

Следуйте этой инструкции:

1. Поставить [Command Line Tools for XCode](https://developer.apple.com/downloads). Для этого вы должны иметь Apple ID.

1. Поставить [Homebrew](http://mxcl.github.com/homebrew/). Homebrew это менеджер пакетов для Mac OS.

 1. Запустить программу Terminal. Она находиться в Applications\Utilities.

 1. Вставить команду ```ruby -e "$(curl -fsSkL raw.github.com/mxcl/homebrew/go)"``` в Terminal и выполнить ее

 1. Что бы проверить правильность установки выполните эту комманду ```brew --version```. Если все установилось успешно вы увидите номер версии, например ```0.9.3```

1. Поставить [Git](http://git-scm.com/). Git это система контроля версий.

    Запустите команду

        brew install git

1. Поставить [RVM](https://rvm.beginrescueend.com/). RVM это менеджер версий Ruby

 1. Запустите команду ```curl -L https://get.rvm.io | bash -s stable --rails```

 1. Закройте Terminal и откройте его вновь

 1. Запустите команду ```rvm install 1.9.3```

 1. Запустите команду ```rvm use 1.9.3 --default```


Что бы проверить, что все установилось корректно сделайте следующее:

1. Запустить программу Terminal.

1. Выполните следующие команды:

        ruby -v
        gem -v
        rails -v

1. Результат должен быть примерно таким:
        
    ![Результат работы](https://raw.github.com/rails-workshop/tutorials/master/setup/images/step6mac.png "Результат работы")

## Другие ОС

Инструкции для других ОС будут добавлены в ближайшее время.



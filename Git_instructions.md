![gitLogo](1280px-Git-logo.svg.png)
# <center>Работа с **Git**</center>

## <center>1. Проверка наличия установленного **Git**

В терминале необходимо выполнить команду *`git version`*. Если **Git** установлен - появится сообщение с информацией о версии программы. Иначе появится сообщение об `ошибке`.
<center> 

![gitVersion](gitVersionTrue.png) 


## <center>2. Установка **Git** 
</center>

Загружаем последнюю версию **Git** с [сайта](https://git-scm.com/downloads) *(https://git-scm.com/downloads)*.

![gitDownload](gitDownload.png)

Инструкция по установке **Git** на различных ОС - [Инструкция](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git).
## <center>3. Настройка **Git**</center>

При первом использовании **Git** необходимо *`представиться`*. Для этого используйте следующие команды: 
<center>

```
git config --global user.name "Ваше имя (Никнейм)"
git config --global user.email "Ваша почта (user@example.com)"
```
</center>

## 4. Инициализация репозитория

Для инициализации репозитория используйте команду `git init`, чтобы **Git** смог работать с вашей папкой/файлами.
<center>

![GitInitTrue](gitInitTrue.png)

</center>

Если использовать команды для работы с **Git** без инициализации - вы получите `ошибку`!

<center>

![GitInitFalse](gitInitFalse.png)

</center>





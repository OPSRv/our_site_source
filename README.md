# Git та GitHub

>**Git** – *це система контролю версій, що дозволяє 
>ефективно керувати історією вихідного коду.*
- [Встановлення Git](https://git-scm.com/downloads)

> Github – *сервіс, який дозволяє працювати з твоїми Git проектами. 
> Це називається репозиторії. 
> Крім Github є інші сервіси (наприклад Bitbucket, GitLab).*

- [Веб-застосунок Github](https://github.com/)


### Основні команди

|  |  |
|--|--|
| ```git init 
| дозволяє проініціалізувати репозиторій у поточній теці |
|--|--|
| 
git status
  | показує поточний статус |
|--|--|
| 
git add
  | відстежує зміни файлів |
|--|--|
| 
git add index.html
 | додає index.html |
|--|--|
| 
git add .  
| додає всі файли |
|--|--|
| 
git add -A 
| додає всі файли |
|--|--|
| 
git push 
| заливає поточні локальні коміти у віддалений репозиторій |
|--|--|
| 
git pull 
| забирає зміни з віддаленого репозиторію до локального |
|--|--|
| 
git clone 
| клонує проект з віддаленого репозиторію |
|  |  |

| git remote add origin https://** | підключення до дистанційного репозиторію |
|--|--|
|  |  |

### git commit -зберігає зміни до коміту

|  |  |
|--|--|
| 
git commit -m 'commit message'
 | створює коміт із повідомленням |
|  |  |

### git branch - робота з гілками у репозиторії
|  |  |
|--|--|
| 
git branch
 |показує список гілок |
|--|--|
| 
git branch branch-name
 |створює нову гілку branch-name  |
|--|--|
| 
git branch -D branch-name
 | видаляє гілку branch-name |
|  |  |
### git checkout - перемикається на іншу гілку
|  |  |
|--|--|
| 
git checkout branch-name
 | перемикається на останній коміт у гілці branch-name|
|--|--|
| 
git checkout -b branch-name
 | створює і перемикається на гілку branch-name |
|  |  |

### git merge - поєднує поточну гілку з обраною
|  |  |
|--|--|
| 
git merge branch-name
 | поєднує поточну гілку з branch-name |
|  |  |

### git config - конфігурація та параметри git
|  |  |
|--|--|
| 
git config --global user.name
 | показує ім'я користувача |
|--|--|
| 
git config --global user.name 'new user'
 | змінює ім'я користувача |
|--|--|
| 
git config --global user.email 
|показує email користувача  |
|--|--|
| 
git config --global user.email 
'test@ukr.net' | змінює email користувача |
|  |  |
(Практика: "Командная работа")

## Задача: "Конфликт при push'е"

### Легенда

Вы с коллегой вдвоём работаете над функцией определения геолокации посетителя лендинга NeuroStartUp. Вы сделали ряд изменений и пытатесь запушить их в репозиторий. Но в этот момент выясняется, что ваш коллега тоже не сидел без дела и успел запушить свои изменения раньше вас. Вам необходимо разрешить кофликт и залить свои изменения на GitHub. 

### Реализация

1. Сделайте форк репозитория [по ссылке](https://github.com/netology-code/git-homeworks-neuro-fork);
1. Скачайте [архив изменений](https://github.com/netology-code/git-homeworks/blob/master/remote/src/neuro-push.zip);
1. Свяжите локальный репозиторий из архива с форком репозитория из п.1;
1. Выполните команду `push -u origin main`, удостоверьтесь, что конфликт произошёл;
1. Заберите актуальную версию данных из удалённого репозитория при помощи команды `git pull origin main`;
1. Разрешите появившийся конфликт и отправьте сделанные вами изменения на GitHub.

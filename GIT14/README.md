# GIT 14: Создание pull requests в сторонний репозиторий

## Описание

Одной из важных причин роста популярности хостингов `git`-репозиториев стала возможность клонировать репозитории внутри хостинга без необходимости выполнять `git clone`/`git push`. Благодаря инструменту `fork` вы можете взять любой проект на `gitlab`, выполнить его `fork` в свой аккаунт и внести необходимые правки, если вас не устраивает код основного проекта.

Так же после внесения правок вы можете предложить добавить исправления обратно в основной проект. То есть сделать `pull request` между репозиториями. Это возможно, поскольку история двух репозиториев полностью идентична - вы же выполнили `fork` в самом начале. :)

Именно так и развиваются `open source` проекты. Есть основной репозиторий, в нем вы можете найти много открытых `issue` - различных багов или проблем, которые существуют в проекте. Вы выполняете `fork` репозитория, исправляете ошибку и создаете `pull request` обратно в `open source` проект. После проверки вашего кода авторами он принимается (или не принимается) в основную ветку.

## Полезные ссылки

[Как вносить изменения в сторонние проекты](/GIT14/Git_Внесение_собственного_вклада_проекты.html)

## Задание

1. Выполнить `fork` репозитория <https://gitlab.com/viktor-bushmin/git-lessons-checkout.git>
1. Переключиться в ветку `feature` и добавить в нее новый файл с интересной информацией отдельным коммитом.
1. Создать `pull request` в основной проект: <https://gitlab.com/viktor-bushmin/git-lessons-checkout.git>.
1. В ответе прислать ссылку на созданный `pull request`.

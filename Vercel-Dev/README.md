# Deploying Git Repositories with Vercel

> Vercel забезпечує автоматичне розгортання під час кожного push та об’єднується з виробничою гілкою ваших проектів GitHub, GitLab і Bitbucket.

Using Git with Vercel provides the following benefits:
+ [Preview Deployments](https://vercel.com/docs/deployments/preview-deployments) for every push.
+ [Production Deployments](https://vercel.com/docs/deployments/environments#production) for the most recent changes from the Production Branch.
+ Instant rollbacks when reverting changes assigned to a custom domain.

Працюючи з Git, майте гілку, яка працює як production branch, яку часто називають main. 
Після створення запиту на pull request (PR) до цієї гілки Vercel створює унікальне розгортання, яке можна використовувати для попереднього перегляду будь-яких змін. 
Коли ви задоволені змінами, ви можете об’єднати (merge) свій PR із основною гілкою, і Vercel створить production deployment.

> For example, if your Production Branch is main, then all the Git branches that are not main are considered Preview Branches.
> That means there can be many Preview Branches, but only a single Production Branch.


**Preview Deployments** дозволяють вам попередньо переглядати зміни у вашій програмі live deployment без об’єднання цих змін із робочою гілкою вашого проекту Git. 
Члени вашої команди та люди, з якими ви ділитеся попередніми переглядами, можуть залишити відгук про ці зміни за допомогою коментарів, якщо це ввімкнено.

> Якщо ви не хочете генерувати розгортання попереднього перегляду, ви можете вимкнути їх.
> 1. Виберіть проект на інформаційній панелі (dashboard)
> 2. Перейдіть до вкладки Параметри (Settings), а потім зайдіть у пункт меню Git.
> 3. У розділі Ignored Build Step виберіть потрібну поведінку.







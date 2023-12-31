# Full-Stack-Development


## YouTube

* Ulbi TV: [SOLID ПРИНЦИПЫ простым языком](https://www.youtube.com/watch?v=TxZwqVTaCmA)
* Ulbi TV: [ООП на простых примерах. Объектно-ориентированное программирование](https://www.youtube.com/watch?v=-6DWwR_R4Xk)
* Ulbi TV: [MVC, MVVM Архитектура. Наглядная теория и примеры](https://www.youtube.com/watch?v=X85soC5evw0)
* Ulbi TV: [CI CD наглядные примеры](https://www.youtube.com/watch?v=ANj7qUgzNq4)
* Ulbi TV: [BACKEND на Node.js. Nest js ПОЛНЫЙ КУРС & Docker](https://www.youtube.com/watch?v=dDeWWQWMM-Y)








- - -

## [rxjs](https://rxjs.dev/)
> _Reactive Extensions Library for JavaScript_

RxJS (Reactive Extensions for JavaScript) - це бібліотека на основі реактивного програмування з подіями, яка розроблена для JavaScript. Вона базується на патерні реактивного програмування (Reactive Programming), який спрощує асинхронне програмування та керування потоками даних, роблячи їх більш прогнозованими та керованими.

#### Основні поняття та особливості RxJS:

* Observable:
  - представляє потік асинхронних даних або подій, що виникають з часом.
  - Він може бути сприйнятий багатьма споживачами (subscribers), які можуть реагувати на дані або події, що надходять з Observable.
* Operators:
  - надає багато операторів для обробки даних в Observable.
  - дозволяють трансформувати, фільтрувати, з'єднувати та агрегувати дані в Observable
  - дозволяє зручно та ефективно маніпулювати потоками даних.
* Subscription:
  - це процес підписки на Observable, який дозволяє реагувати на події або дані, що надходять з Observable.
  - Коли підписка більше не потрібна, її можна скасувати для уникнення витоків пам'яті та непотрібного виконання коду.
* Hot і Cold Observables:
  - "Холодний" Observable генерує дані лише при активації підписки, тоді як "гарячий" Observable генерує дані, навіть якщо немає підписок.
* Широка підтримка:
  - RxJS має широку підтримку і може використовуватися як на стороні клієнта, так і на стороні сервера,
  - дозволяє розробникам зручно використовувати його в різних веб-додатках.

> _RxJS дозволяє легко керувати асинхронними операціями, такими як обробка HTTP-запитів, робота з подіями клієнтського інтерфейсу, зв'язок між компонентами у фронтенді та багато іншого. Він стає дуже потужним інструментом для реалізації складних логік та маніпуляцій з потоками даних._

### [rxjs-lecture](https://github.com/hiddenroadss/rxjs-lecture)

* Intro.md
* Subject.md
* Observer.md
* Operators.md
* Scheduler.md
* Subscription.md

Розробники React.js використовують RxJS для реалізації асинхронних операцій та керування станом додатків. RxJS допомагає здійснювати запити до сервера, обробляти дані, що повертаються, реагувати на події, які відбуваються в інтерфейсі користувача, та багато іншого. Завдяки широкому спектру операторів RxJS, розробники можуть зручно і потужно маніпулювати потоками даних у своїх додатках.

Node.js розробники також використовують RxJS для забезпечення ефективного керування асинхронними операціями, такими як робота з базами даних, обробка HTTP-запитів або створення власних потоків даних. RxJS може спростити код та забезпечити чистоту та логічність взаємодії з асинхронними операціями, дозволяючи більш просто зберігати та використовувати дані у потоці роботи.

#### [RxJS-fruits](https://www.rxjs-fruits.com/subscribe)
> _A game for learning RxJS_ 🍎🍌



- - -

## Prisma ORM. 
> &emsp;_Next-generation Node.js and TypeScript ORM unlocks a new level of developer experience when working with databases thanks to its intuitive data model, automated migrations, type-safety & auto-completion._

Prisma - це сучасний ORM (Object-Relational Mapping) для Node.js та TypeScript, який допомагає розробникам зручно і ефективно взаємодіяти з базами даних в програмах Full Stack Development. "ORM" - це підхід програмування, який дозволяє використовувати об'єктно-орієнтований підхід для роботи з реляційними базами даних, що дозволяє зменшити зайвий код та спростити взаємодію з даними.

#### Основні функції та особливості Prisma:

+ Моделі даних:
  - Ви можете описати структуру даних вашої бази даних за допомогою моделей.
  - Надає можливість визначати моделі з використанням декларативного синтаксису, який дозволяє швидко описати схему бази даних.
+ Міграції:
  - Дозволяє здійснювати міграції бази даних, щоб легко і безпечно вносити зміни до схеми даних без втрати інформації.
+ Запити до бази даних:
  - Prisma допомагає забезпечити безпечний доступ до бази даних за допомогою генератора запитів.
  - Вам не потрібно писати SQL-запити вручну.
  - Використовуючи Prisma Client, ви можете виконувати запити за допомогою чистого, типізованого JS коду.
+ Підтримка різних баз даних:
  - Prisma підтримує популярні реляційні бази даних, такі як PostgreSQL, MySQL та SQLite, що дозволяє легко перехід від одного провайдера до іншого.
+ Перформанс:
  - Prisma намагається мінімізувати кількість виконаних запитів до бази даних та оптимізує взаємодію з нею, що допомагає поліпшити продуктивність вашого додатку.

> _Причина використання Prisma полягає в тому, що вона спрощує розробку програм з використанням баз даних, забезпечує безпеку при взаємодії з ними та пропонує зручний і потужний інтерфейс для доступу до даних. Завдяки цим перевагам Prisma стає популярним вибором для проектів Full Stack Development._

### [Get started](https://www.prisma.io/docs/getting-started)
* Which tutorial is right for me?
  + _Quickstart guide - using a plain TypeScript project and a local SQLite database file_
  + _create a project with Prisma from scratch_
* Prisma with different tooling
  + _The easiest way to work with a database in Next.js_
  + _Fully type-safe ORM for NestJS_
  + _Easy, type-safe database access in Express servers_
 
#### [One-to-one relations](https://www.prisma.io/docs/concepts/components/prisma-schema/relations/one-to-one-relations)
> _One-to-one (1-1) relations refer to relations where at most one record can be connected on both sides of the relation. _

- - -

## [VERCEL](https://vercel.com/)
> _Vercel's frontend cloud gives developers the frameworks, workflows, and infrastructure to build a faster, more personalized Web._

Vercel - це хмарний сервіс для хостингу та розгортання веб-додатків, спроектований спеціально для сучасних стеків технологій, таких як React.js, Next.js, Vue.js, Angular, інші фреймворки та бібліотеки для фронтенду та бекенду. Він надає простий та потужний спосіб розгортати ваші додатки з нульовими зусиллями зі сторони розробника, що робить його популярним вибором для команд розробників та стартапів.

#### Основні особливості Vercel:

+ Спрощене розгортання:
  - Завантажте свій проект на Vercel, і він автоматично розпізнає конфігурацію вашого додатку та забезпечує миттєве розгортання.
  - Вам не потрібно конфігурувати веб-сервери або вручну налаштовувати інфраструктуру.
+ Керування доменами:
  - Дозволяє легко налаштувати доменні імена для вашого додатку.
  - Ви можете легко додати свої домени або використовувати доменні імена Vercel за замовчуванням.
+ Попередній перегляд віток:
  - Ви можете побачити попередній перегляд вашого додатку на окремій URL для кожної гілки ваших репозиторіїв.
  - Це дозволяє легко перевіряти новий код до його об'єднання з основною гілкою.
+ Масштабованість:
  - Забезпечує автоматичне масштабування вашого додатку в залежності від його завантаження.
  - Гарантує швидку та надійну роботу, навіть під час значного трафіку.
+ Інтеграції з Git:
  - Ви можете налаштувати автоматичне розгортання додатку при кожному пуші в Git, що робить процес розробки більш зручним і швидким.

> _Vercel добре інтегрується з багатьма популярними системами керування версіями, такими як GitHub, GitLab, та Bitbucket, що робить його привабливим вибором для команд, які використовують ці сервіси._

Цей сервіс дозволяє розгортати фронтенд та бекенд додатки, що забезпечує ще більшу гнучкість при розробці та розгортанні повноцінних проектів.

- - -

## [NETLIFY](https://www.netlify.com/)
> _Netlify is the modern web development platform for Enterprises to realize the full potential of a scalable, customizable web architecture._

Netlify" - це платформа для розгортання та хостингу веб-сайтів із використанням сучасних технологій розробки. Вона надає зручність і швидкість у розгортанні, управлінні та оптимізації веб-додатків, роблячи процес розробки та публікації більш простим та ефективним.

#### Основні особливості та використання "Netlify":

+ Швидке Розгортання:
  - "Netlify" дозволяє вам дуже швидко розгортати веб-сайти та додатки.
  - Зазвичай, це вимагає всього кількох кліків або команд у терміналі.
+ Статичні та Динамічні Сайти:
  - Платформа відмінно підходить для розгортання статичних сайтів;
  - також підтримує можливість розгортання динамічних додатків з використанням серверних функцій.
+ Continuous Deployment (CI/CD):
  - "Netlify" підтримує CI/CD автоматизацію, що дозволяє вам автоматично розгортати сайт на сервері при зміні коду репозиторії GitHub.
  - Це полегшує ведення інтеграції та розгортання.
+ Домен та SSL:
  - "Netlify" дозволяє безкоштовно реєструвати та налаштовувати домени для ваших сайтів.
  - Крім того, вони також автоматично надають безкоштовні SSL-сертифікати для вашого сайту.
+ Performance Optimization:
  - Платформа автоматично використовує різні техніки оптимізації для поліпшення продуктивності вашого сайту, включаючи кешування, зжимання зображень, HTTP/2 та інші.
+ Форми та Збереження Даних:
  - "Netlify" надає можливість легко обробляти форми на вашому сайті та зберігати їхні дані.
+ Prerendering та Previews:
  - Платформа підтримує prerendering, що може поліпшити індексацію ваших сторінок пошуковими системами.
  - Також ви можете створювати попередні перегляди (previews) сайту для тестування перед публікацією.

"Netlify" може бути корисною платформою для розробників, які шукають швидке та просте рішення для розгортання, управління та оптимізації веб-сайтів та додатків.

#### ви можете розміщувати як React, так і Node.js-застосунки

* React-застосунки:
  - ви зазвичай використовуєте статичний сайт.
  - Ваш застосунок буде збудований в HTML, CSS та JavaScript, і ці файли будуть розміщені на сервері. 
* Node.js-застосунки:
  - ви можете використовувати Serverless Functions або розгортати Node.js-додатки за допомогою "Netlify Functions".
  - Це дозволяє вам створювати API-точки, які можуть бути викликані з вашого клієнтського React-застосунку.


- - -




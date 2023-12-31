### популярні архітектурні підходи в Node.js та їх використання

# Model-View-Controller (MVC)
> _ця архітектура є стандартною для багатьох веб-фреймворків, таких як Express.js для Node.js і React для фронтенду_

### Опис: 
Модель-Вид-Контролер (MVC) - це популярний архітектурний підхід, який розділяє додаток на три основні компоненти: Модель (Model), Вид (View) і Контролер (Controller).\
Модель відповідає за роботу з даними і бізнес-логікою, Вид - за відображення інформації користувачу, а Контролер - за обробку запитів та взаємодію між моделлю і видом.

```go
📁 project/
├── 📁 models/
│   ├── user.js
│   ├── post.js
│   └── ...
├── 📁 views/
│   ├── index.html
│   ├── user_profile.html
│   └── ...
├── 📁 controllers/
│   ├── userController.js
│   ├── postController.js
│   └── ...
├── 📁 routes/
│   ├── index.js
│   ├── userRoutes.js
│   └── ...
├── 📁 middleware/
│   ├── auth.js
│   ├── validation.js
│   └── ...
├── 📁 services/
│   ├── authService.js
│   ├── emailService.js
│   └── ...
├── 📁 utils/
│   ├── helpers.js
│   ├── dateUtils.js
│   └── ...
├── app.js
└── package.json
```

### Використання: 
MVC є добрим вибором для веб-додатків з класичною структурою, де потрібно чітко розділити логіку додатку на окремі компоненти. Це допоможе зберігати код організованим і легше розширювати проект.


# RESTful API
> _добре підходить для створення публічних API та інтеграції з іншими системами_

### Опис: 
REST (Representational State Transfer) - це архітектурний стиль для створення веб-служб, який базується на стандартних HTTP-методах (GET, POST, PUT, DELETE) і робить акцент на ресурсах, що представляють стан додатку.\
RESTful API використовується для створення веб-служб, які дозволяють іншим додаткам взаємодіяти з вашим додатком через HTTP-запити.

```go
📁 project/
├── 📁 routes/
│   ├── userRoutes.js
│   ├── postRoutes.js
│   └── ...
├── 📁 controllers/
│   ├── userController.js
│   ├── postController.js
│   └── ...
├── 📁 models/
│   ├── user.js
│   ├── post.js
│   └── ...
├── 📁 middleware/
│   ├── authMiddleware.js
│   ├── validationMiddleware.js
│   └── ...
├── server.js
└── package.json
```

### Використання: 
RESTful API часто використовується для створення серверних компонентів, які надають доступ до даних і функціоналу вашого додатку для інших клієнтських додатків, включаючи веб-сайти, мобільні додатки і інші сервіси. Він є популярним вибором для створення API в Node.js.


# GraphQL
> _надає більшу гнучкість у виборі даних_

### Опис: 
GraphQL - це запитова мова та середовище виконання для створення більш гнучких і потужних API. Замість того, щоб отримувати передбачуваний набір даних як в REST, ви можете запитувати лише ті дані, які вам потрібні, що дозволяє уникнути "перенасичення" даними та покращити продуктивність.

```go
📁 project/
├── 📁 schemas/
│   ├── userSchema.graphql
│   ├── postSchema.graphql
│   └── ...
├── 📁 resolvers/
│   ├── userResolvers.js
│   ├── postResolvers.js
│   └── ...
├── 📁 models/
│   ├── user.js
│   ├── post.js
│   └── ...
├── 📁 middleware/
│   ├── authMiddleware.js
│   ├── validationMiddleware.js
│   └── ...
├── server.js
└── package.json
```

### Використання: 
GraphQL особливо корисний, коли потрібна гнучка система запитів для отримання даних з сервера. Це підходить для сучасних веб-додатків, де клієнти можуть вимагати різні дані для різних компонентів інтерфейсу.







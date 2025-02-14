<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио - Приют для животных</title>
    <!-- Подключение CSS Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Подключение собственных стилей -->
    <link rel="stylesheet" href="css/тк4.css">
</head>
<body>
    <!-- Шапка сайта (Navbar) -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <!-- Логотип или название сайта -->
                <a class="navbar-brand" href="#">Приют для животных</a>
                <!-- Кнопка для мобильных устройств -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <!-- Меню навигации -->
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Главная</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">О нас</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Животные</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Контакты</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <!-- Блок контента с приветствием и изображением -->
    <section class="py-5">
        <div class="container text-center">
            <div class="row">
                <!-- Текстовый блок -->
                <div class="col-md-6">
                    <h1>Добро пожаловать в наш приют!</h1>
                    <p>Мы заботимся о животных и ищем для них новый дом.</p>
                </div>
                <!-- Изображение -->
                <div class="col-md-6">
                    <img src="https://avatars.mds.yandex.net/i?id=90f3ed6c8c720bbf0d3bda445453de30_sr-4575978-images-thumbs&n=13" class="img-fluid" alt="Приют для животных">
                </div>
            </div>
        </div>
    </section>
    <!-- Секция с каруселью изображений -->
    <section class="py-5">
        <div class="container">
            <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <!-- Первый слайд (активный) -->
                    <div class="carousel-item active">
                        <img src=" https://cdnn21.img.ria.ru/images/07e4/08/04/1575337370_0:78:3071:1805_1920x0_80_0_0_7d1de0d1ac0b2ca5b72ded1f776ca99f.jpg " class="d-block w-100" alt="Животное 1">
                    </div>
                    <!-- Второй слайд -->
                    <div class="carousel-item">
                        <img src=" https://s12.stc.yc.kpcdn.net/share/i/12/9695396/wr-960.webp " class="d-block w-100" alt="Животное 2">
                    </div>
                    <!-- Третий слайд -->
                    <div class="carousel-item">
                        <img src=" https://avatars.mds.yandex.net/i?id=316bcc0a65fb9f1767c2f35910f01a6062fe3f35-12538251-images-thumbs&n=13 " class="d-block w-100" alt="Животное 3">
                    </div>
                </div>
                <!-- Кнопки управления каруселью -->
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Предыдущий</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Следующий</span>
                </button>
            </div>
        </div>
    </section>
    <!-- Секция с карточками животных -->
    <section class="py-5">
        <div class="container">
            <div class="row">
                <!-- Карточка 1 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://www.ferra.ru/imgs/2024/05/08/05/6460496/c2150453d059e8999c5f0b211ce334f7c869147c.jpg" class="card-img-top" alt="Кошка">
                        <div class="card-body">
                            <h5 class="card-title">Пушок</h5>
                            <p class="card-text">Добрый и ласковый кот.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
              <!-- Карточка 2 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://avatars.mds.yandex.net/i?id=3b1039adc7c95f06f5a1758db98c121129e586eb-9181946-images-thumbs&n=13" class="card-img-top" alt="Собака">
                        <div class="card-body">
                            <h5 class="card-title">Дружок</h5>
                            <p class="card-text">Верный и социализированный пёс.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
                <!-- Карточка 3 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://avatars.dzeninfra.ru/get-zen_doc/5289413/pub_638e77e778df2941efb0a894_638e78376727e34f42b46823/scale_1200" class="card-img-top" alt="Кот">
                        <div class="card-body">
                            <h5 class="card-title">Вася </h5>
                            <p class="card-text">Замечательный, спокойный кот.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Секция с формой для связи -->
    <section class="py-5">
        <div class="container">
            <h2>Свяжитесь с нами</h2>
            <form>
                <!-- Поле для имени -->
                <div class="mb-3">
                    <label for="name" class="form-label">Ваше имя</label>
                    <input type="text" class="form-control" id="name">
                </div>
                <!-- Поле для email -->
                <div class="mb-3">
                    <label for="email" class="form-label">Ваш email</label>
                    <input type="email" class="form-control" id="email">
                </div>
                <!-- Поле для сообщения -->
                <div class="mb-3">
                    <label for="message" class="form-label">Сообщение</label>
                    <textarea class="form-control" id="message" rows="3"></textarea>
                </div>
                <!-- Кнопка отправки формы -->
                <button type="submit" class="btn btn-primary">Отправить</button>
            </form>
        </div>
    </section>
    <!-- Подвал сайта -->
    <footer class="bg-light py-4">
        <div class="container text-center">
            <p>Адрес: ул. Печерская д.3А</p>
            <p>Телефон: +7 (999) 999-99-99</p>
            <p>Email: info@gmail.com</p>
        </div>
    </footer>
    <!-- Подключение JS Bootstrap -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

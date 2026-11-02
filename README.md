<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Промо: Красота в деталях</title>
    <link rel="stylesheet" href="styles.css">
    <!-- Подключение иконок (например, Font Awesome) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

    <!-- Микроразметка для главной страницы интернет-магазина -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebSite",
      "name": "Бьюти Маркет",
      "url": "https://example-beauty-shop.ru",
      "potentialAction": {
        "@type": "SearchAction",
        "target": "https://example-beauty-shop.ru/search?q={search_term_string}",
        "query-input": "required name=search_term_string"
      }
    }
    </script>

    <section class="promo-block">
        <div class="container">
            <div class="promo-content">
                <div class="promo-text">
                    <span class="promo-badge">Акция недели</span>
                    <h1>Идеальный тон и сияние: полный ритуал ухода</h1>
                    <p>Подберите профессиональную косметику для дома или доверьте свою кожу экспертам в нашей студии.</p>

                    <!-- Вкладки для переключения -->
                    <div class="tabs">
                        <button class="tab-link active" data-tab="home">Домашний уход</button>
                        <button class="tab-link" data-tab="salon">Салонные процедуры</button>
                    </div>

                    <!-- Контент вкладки "Домашний уход" -->
                    <div id="home" class="tab-content active">
                        <ul class="product-list">
                            <li>Увлажняющая сыворотка с гиалуроновой кислотой</li>
                            <li>Энзимная пудра для умывания</li>
                            <li>Крем с витамином С для сияния кожи</li>
                        </ul>
                        <a href="/catalog/skincare" class="btn btn-primary">Собрать бокс со скидкой 20%</a>
                    </div>

                    <!-- Контент вкладки "Салонные процедуры" -->
                    <div id="salon" class="tab-content">
                        <ul class="service-list">
                            <li>Атравматичная чистка лица</li>
                            <li>Карбокситерапия</li>
                            <li>LED-терапия для снятия воспалений</li>
                        </ul>
                        <a href="/booking" class="btn btn-secondary">Записаться онлайн</a>
                    </div>
                </div>
                <div class="promo-image">
                    <!-- Изображение можно заменить на свое -->
                    <img src="https://images.unsplash.com/photo-1541982704-9c4a937a82c2?q=80&w=1000" alt="Бьюти косметика и процедуры">
                </div>
            </div>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>

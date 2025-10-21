<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kshatri Beauty Studio — Салон красоты в Москве</title>
    <meta name="description" content="Профессиональный салон красоты Kshatri. Маникюр, педикюр, наращивание ресниц. Запись онлайн.">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Навигация -->
    <nav class="navbar" id="navbar">
        <div class="container">
            <div class="nav-content">
                <a href="#home" class="logo">KSHATRI</a>
                <button class="menu-toggle" id="menuToggle">
                    <span></span>
                    <span></span>
                    <span></span>
                </button>
                <ul class="nav-menu" id="navMenu">
                    <li><a href="#home" class="nav-link">Главная</a></li>
                    <li><a href="#services" class="nav-link">Услуги</a></li>
                    <li><a href="#gallery" class="nav-link">Работы</a></li>
                    <li><a href="#reviews" class="nav-link">Отзывы</a></li>
                    <li><a href="#contacts" class="nav-link">Контакты</a></li>
                </ul>
                <a href="#booking" class="btn-primary btn-nav">Записаться</a>
            </div>
        </div>
    </nav>

    <!-- Главный экран -->
    <section class="hero" id="home">
        <div class="hero-overlay"></div>
        <div class="container">
            <div class="hero-content">
                <h1 class="hero-title">
                    <span class="title-line">Красота</span>
                    <span class="title-line">в каждой</span>
                    <span class="title-line">детали</span>
                </h1>
                <p class="hero-subtitle">Профессиональный уход и безупречный сервис в центре Москвы</p>
                <div class="hero-buttons">
                    <a href="#booking" class="btn-primary btn-large">Онлайн-запись</a>
                    <a href="#services" class="btn-secondary btn-large">Наши услуги</a>
                </div>
            </div>
        </div>
        <div class="scroll-indicator">
            <span>Листайте вниз</span>
            <div class="scroll-line"></div>
        </div>
    </section>

    <!-- О студии -->
    <section class="about">
        <div class="container">
            <div class="about-grid">
                <div class="about-text">
                    <h2 class="section-title">О студии Kshatri</h2>
                    <p class="about-description">
                        Мы создали пространство, где профессионализм встречается с комфортом. 
                        Наша команда мастеров с многолетним опытом использует только премиальные 
                        материалы и современные техники.
                    </p>
                    <p class="about-description">
                        Каждый визит к нам — это не просто процедура, а момент заботы о себе 
                        в атмосфере уюта и внимания к деталям.
                    </p>
                    <div class="about-features">
                        <div class="feature-item">
                            <div class="feature-number">5+</div>
                            <div class="feature-text">лет опыта</div>
                        </div>
                        <div class="feature-item">
                            <div class="feature-number">2000+</div>
                            <div class="feature-text">довольных клиентов</div>
                        </div>
                        <div class="feature-item">
                            <div class="feature-number">100%</div>
                            <div class="feature-text">качество</div>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <div class="image-placeholder">
                        <img src="https://images.unsplash.com/photo-1560066984-138dadb4c035?w=800" alt="Интерьер салона">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Услуги и цены -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Наши услуги</h2>
                <p class="section-subtitle">Полный спектр beauty-процедур для вашей красоты</p>
            </div>

            <div class="services-grid">
                <!-- Маникюр -->
                <div class="service-card">
                    <div class="service-icon">
                        <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                            <path d="M12 2L15.09 8.26L22 9.27L17 14.14L18.18 21.02L12 17.77L5.82 21.02L7 14.14L2 9.27L8.91 8.26L12 2Z"/>
                        </svg>
                    </div>
                    <h3 class="service-title">Маникюр</h3>
                    <ul class="service-list">
                        <li>
                            <span class="service-name">Классический маникюр</span>
                            <span class="service-price">1 500 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Аппаратный маникюр</span>
                            <span class="service-price">1 800 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Покрытие гель-лак</span>
                            <span class="service-price">2 200 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Маникюр + покрытие</span>
                            <span class="service-price">3 500 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Дизайн ногтей (1 ноготь)</span>
                            <span class="service-price">от 100 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Укрепление ногтей</span>
                            <span class="service-price">500 ₽</span>
                        </li>
                    </ul>
                    <a href="#booking" class="btn-outline">Записаться</a>
                </div>

                <!-- Педикюр -->
                <div class="service-card">
                    <div class="service-icon">
                        <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                            <circle cx="12" cy="12" r="10"/>
                            <path d="M12 6v6l4 2"/>
                        </svg>
                    </div>
                    <h3 class="service-title">Педикюр</h3>
                    <ul class="service-list">
                        <li>
                            <span class="service-name">Классический педикюр</span>
                            <span class="service-price">2 000 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Аппаратный педикюр</span>
                            <span class="service-price">2 500 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Покрытие гель-лак</span>
                            <span class="service-price">2 000 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Педикюр + покрытие</span>
                            <span class="service-price">4 000 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">SPA-педикюр</span>
                            <span class="service-price">3 500 ₽</span>
                        </li>
                    </ul>
                    <a href="#booking" class="btn-outline">Записаться</a>
                </div>

                <!-- Ресницы -->
                <div class="service-card">
                    <div class="service-icon">
                        <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                            <path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/>
                            <circle cx="12" cy="12" r="3"/>
                        </svg>
                    </div>
                    <h3 class="service-title">Ресницы и брови</h3>
                    <ul class="service-list">
                        <li>
                            <span class="service-name">Наращивание ресниц классика</span>
                            <span class="service-price">2 500 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Наращивание 2D-3D</span>
                            <span class="service-price">3 000 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Объем 4D-5D</span>
                            <span class="service-price">3 500 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Коррекция ресниц</span>
                            <span class="service-price">2 000 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Ламинирование ресниц</span>
                            <span class="service-price">2 800 ₽</span>
                        </li>
                        <li>
                            <span class="service-name">Оформление бровей</span>
                            <span class="service-price">1 200 ₽</span>
                        </li>
                    </ul>
                    <a href="#booking" class="btn-outline">Записаться</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Галерея работ -->
    <section class="gallery" id="gallery">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Наши работы</h2>
                <p class="section-subtitle">Портфолио наших мастеров</p>
            </div>

            <div class="gallery-grid">
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1604654894610-df63bc536371?w=600" alt="Маникюр 1">
                    <div class="gallery-overlay">
                        <span class="gallery-title">Нюдовый маникюр</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1610992015732-2449b76344bc?w=600" alt="Маникюр 2">
                    <div class="gallery-overlay">
                        <span class="gallery-title">Французский маникюр</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1632345031435-8727f6897d53?w=600" alt="Ресницы">
                    <div class="gallery-overlay">
                        <span class="gallery-title">Наращивание ресниц</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1519014816548-bf5fe059798b?w=600" alt="Маникюр 3">
                    <div class="gallery-overlay">
                        <span class="gallery-title">Дизайн с блестками</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1599948128020-9a44a0b8a8a5?w=600" alt="Педикюр">
                    <div class="gallery-overlay">
                        <span class="gallery-title">Педикюр</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1487412947147-5cebf100ffc2?w=600" alt="Маникюр 4">
                    <div class="gallery-overlay">
                        <span class="gallery-title">Яркий дизайн</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Отзывы -->
    <section class="reviews" id="reviews">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Отзывы клиентов</h2>
                <p class="section-subtitle">Что говорят о нас</p>
            </div>

            <div class="reviews-slider">
                <div class="reviews-container" id="reviewsContainer">
                    <div class="review-card">
                        <div class="review-stars">★★★★★</div>
                        <p class="review-text">
                            "Прекрасный салон! Мастера настоящие профессионалы. Делала наращивание ресниц - результат превзошел все ожидания. Очень уютная атмосфера и приятные цены."
                        </p>
                        <div class="review-author">
                            <div class="author-avatar">А</div>
                            <div class="author-info">
                                <div class="author-name">Анна Петрова</div>
                                <div class="author-date">2 недели назад</div>
                            </div>
                        </div>
                    </div>

                    <div class="review-card">
                        <div class="review-stars">★★★★★</div>
                        <p class="review-text">
                            "Хожу сюда уже больше года. Маникюр держится отлично, мастера внимательные и аккуратные. Всегда чисто, стерильно. Рекомендую!"
                        </p>
                        <div class="review-author">
                            <div class="author-avatar">М</div>
                            <div class="author-info">
                                <div class="author-name">Мария Иванова</div>
                                <div class="author-date">1 месяц назад</div>
                            </div>
                        </div>
                    </div>

                    <div class="review-card">
                        <div class="review-stars">★★★★★</div>
                        <p class="review-text">
                            "Отличное место! Записалась на педикюр и маникюр - все сделали быстро и качественно. Мастер посоветовала хороший дизайн. Обязательно вернусь!"
                        </p>
                        <div class="review-author">
                            <div class="author-avatar">Е</div>
                            <div class="author-info">
                                <div class="author-name">Екатерина Смирнова</div>
                                <div class="author-date">3 недели назад</div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="slider-controls">
                    <button class="slider-btn" id="prevBtn">←</button>
                    <button class="slider-btn" id="nextBtn">→</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Онлайн-запись -->
    <section class="booking" id="booking">
        <div class="container">
            <div class="booking-content">
                <div class="booking-info">
                    <h2 class="section-title">Онлайн-запись</h2>
                    <p class="booking-description">
                        Запишитесь на процедуру прямо сейчас. Мы свяжемся с вами для подтверждения времени.
                    </p>
                    <div class="booking-benefits">
                        <div class="benefit-item">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polyline points="20 6 9 17 4 12"/>
                            </svg>
                            <span>Удобное время</span>
                        </div>
                        <div class="benefit-item">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polyline points="20 6 9 17 4 12"/>
                            </svg>
                            <span>Опытные мастера</span>
                        </div>
                        <div class="benefit-item">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polyline points="20 6 9 17 4 12"/>
                            </svg>
                            <span>Премиум материалы</span>
                        </div>
                    </div>
                </div>

                <form class="booking-form" id="bookingForm">
                    <div class="form-group">
                        <input type="text" class="form-input" placeholder="Ваше имя" required>
                    </div>
                    <div class="form-group">
                        <input type="tel" class="form-input" placeholder="Телефон" required>
                    </div>
                    <div class="form-group">
                        <select class="form-input" required>
                            <option value="">Выберите услугу</option>
                            <option value="manicure">Маникюр</option>
                            <option value="pedicure">Педикюр</option>
                            <option value="lashes">Ресницы</option>
                            <option value="brows">Брови</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <input type="date" class="form-input" required>
                    </div>
                    <div class="form-group">
                        <input type="time" class="form-input" required>
                    </div>
                    <div class="form-group">
                        <textarea class="form-input" placeholder="Комментарий (необязательно)" rows="3"></textarea>
                    </div>
                    <button type="submit" class="btn-primary btn-large btn-full">Отправить заявку</button>
                    <p class="form-note">Нажимая кнопку, вы соглашаетесь с политикой конфиденциальности</p>
                </form>
            </div>
        </div>
    </section>

    <!-- Контакты -->
    <section class="contacts" id="contacts">
        <div class="container">
            <div class="contacts-grid">
                <div class="contacts-info">
                    <h2 class="section-title">Контакты</h2>
                    <div class="contact-items">
                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/>
                                    <circle cx="12" cy="10" r="3"/>
                                </svg>
                            </div>
                            <div class="contact-text">
                                <div class="contact-label">Адрес</div>
                                <div class="contact-value">Москва, ул. Примерная, д. 1</div>
                            </div>
                        </div>

                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
                                </svg>
                            </div>
                            <div class="contact-text">
                                <div class="contact-label">Телефон</div>
                                <div class="contact-value">+7 (999) 123-45-67</div>
                            </div>
                        </div>

                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <circle cx="12" cy="12" r="10"/>
                                    <polyline points="12 6 12 12 16 14"/>
                                </svg>
                            </div>
                            <div class="contact-text">
                                <div class="contact-label">Режим работы</div>
                                <div class="contact-value">Ежедневно с 10:00 до 21:00</div>
                            </div>
                        </div>

                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/>
                                    <polyline points="22,6 12,13 2,6"/>
                                </svg>
                            </div>
                            <div class="contact-text">
                                <div class="contact-label">Email</div>
                                <div class="contact-value">info@kshatri.ru</div>
                            </div>
                        </div>
                    </div>

                    <div class="social-links">
                        <a href="#" class="social-link" aria-label="Instagram">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                <rect x="2" y="2" width="20" height="20" rx="5" ry="5"/>
                                <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" fill="none" stroke="#1a1a1a" stroke-width="2"/>
                                <circle cx="17.5" cy="6.5" r="1.5" fill="#1a1a1a"/>
                            </svg>
                        </a>
                        <a href="#" class="social-link" aria-label="WhatsApp">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
                            </svg>
                        </a>
                        <a href="#" class="social-link" aria-label="Telegram">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                <path d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm5.894 8.221l-1.97 9.28c-.145.658-.537.818-1.084.508l-3-2.21-1.446 1.394c-.14.18-.357.295-.6.295-.002 0-.003 0-.005 0l.213-3.054 5.56-5.022c.24-.213-.054-.334-.373-.121l-6.869 4.326-2.96-.924c-.64-.203-.658-.64.135-.954l11.566-4.458c.538-.196 1.006.128.832.941z"/>
                            </svg>
                        </a>
                    </div>
                </div>

                <div class="map-container">
                    <iframe 
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2245.6087064818477!2d37.61766831592448!3d55.75582998055641!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46b54a50b315e573%3A0xa886bf5a3d9b2e68!2z0JzQvtGB0LrQstCw!5e0!3m2!1sru!2sru!4v1234567890123!5m2!1sru!2sru" 
                        width="100%" 
                        height="100%" 
                        style="border:0;" 
                        allowfullscreen="" 
                        loading="lazy">
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">KSHATRI</div>
                <div class="footer-text">
                    <p>&copy; 2024 Kshatri Beauty Studio. Все права защищены.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Кнопка "Наверх" -->
    <button class="scroll-top" id="scrollTop">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <polyline points="18 15 12 9 6 15"/>
        </svg>
    </button>

    <script src="script.js"></script>
</body>
</html>
/* ===== ОБЩИЕ СТИЛИ ===== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #d4af37;
    --secondary-color: #1a1a1a;
    --text-color: #333;
    --text-light: #666;
    --bg-light: #f8f8f8;
    --white: #ffffff;
    --transition: all 0.3s ease;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    color: var(--text-color);
    line-height: 1.6;
    overflow-x: hidden;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* ===== ТИПОГРАФИКА ===== */
.section-title {
    font-size: clamp(2rem, 5vw, 3.5rem);
    font-weight: 300;
    letter-spacing: -1px;
    margin-bottom: 1rem;
    color: var(--secondary-color);
}

.section-subtitle {
    font-size: 1.1rem;
    color: var(--text-light);
    font-weight: 300;
}

.section-header {
    text-align: center;
    margin-bottom: 4rem;
}

/* ===== КНОПКИ ===== */
.btn-primary,
.btn-secondary,
.btn-outline {
    display: inline-block;
    padding: 14px 32px;
    text-decoration: none;
    border-radius: 2px;
    font-size: 0.95rem;
    font-weight: 500;
    letter-spacing: 0.5px;
    transition: var(--transition);
    border: none;
    cursor: pointer;
    text-align: center;
}

.btn-primary {
    background: var(--primary-color);
    color: var(--secondary-color);
}

.btn-primary:hover {
    background: #c9a02e;
    transform: translateY(-2px);
    box-shadow: 0 10px 25px rgba(212, 175, 55, 0.3);
}

.btn-secondary {
    background: transparent;
    color: var(--white);
    border: 1px solid var(--white);
}

.btn-secondary:hover {
    background: var(--white);
    color: var(--secondary-color);
}

.btn-outline {
    background: transparent;
    color: var(--primary-color);
    border: 1px solid var(--primary-color);
}

.btn-outline:hover {
    background: var(--primary-color);
    color: var(--secondary-color);
}

.btn-large {
    padding: 18px 40px;
    font-size: 1rem;
}

.btn-full {
    width: 100%;
}

/* ===== НАВИГАЦИЯ ===== */
.navbar {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
    background: transparent;
    transition: var(--transition);
    padding: 20px 0;
}

.navbar.scrolled {
    background: rgba(255, 255, 255, 0.98);
    box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
    padding: 15px 0;
}

.nav-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: 600;
    letter-spacing: 2px;
    color: var(--white);
    text-decoration: none;
    transition: var(--transition);
}

.navbar.scrolled .logo {
    color: var(--secondary-color);
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2.5rem;
    align-items: center;
}

.nav-link {
    color: var(--white);
    text-decoration: none;
    font-size: 0.95rem;
    font-weight: 400;
    transition: var(--transition);
    position: relative;
}

.navbar.scrolled .nav-link {
    color: var(--text-color);
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--primary-color);
    transition: var(--transition);
}

.nav-link:hover::after {
    width: 100%;
}

.btn-nav {
    padding: 10px 24px;
}

.menu-toggle {
    display: none;
    flex-direction: column;
    gap: 5px;
    background: none;
    border: none;
    cursor: pointer;
    padding: 5px;
}

.menu-toggle span {
    width: 25px;
    height: 2px;
    background: var(--white);
    transition: var(--transition);
}

.navbar.scrolled .menu-toggle span {
    background: var(--secondary-color);
}

/* ===== ГЛАВНЫЙ ЭКРАН ===== */
.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
    overflow: hidden;
}

.hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('https://images.unsplash.com/photo-1560066984-138dadb4c035?w=1920') center/cover;
    opacity: 0.15;
    z-index: 0;
}

.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: radial-gradient(circle at center, transparent 0%, rgba(26, 26, 26, 0.7) 100%);
    z-index: 1;
}

.hero-content {
    position: relative;
    z-index: 2;
    text-align: center;
    color: var(--white);
}

.hero-title {
    font-size: clamp(3rem, 8vw, 6rem);
    font-weight: 300;
    line-height: 1.1;
    margin-bottom: 1.5rem;
    letter-spacing: -2px;
}

.title-line {
    display: block;
    animation: fadeInUp 0.8s ease forwards;
    opacity: 0;
}

.title-line:nth-child(1) {
    animation-delay: 0.2s;
}

.title-line:nth-child(2) {
    animation-delay: 0.4s;
}

.title-line:nth-child(3) {
    animation-delay: 0.6s;
    color: var(--primary-color);
}

.hero-subtitle {
    font-size: 1.3rem;
    font-weight: 300;
    margin-bottom: 3rem;
    opacity: 0;
    animation: fadeInUp 0.8s ease 0.8s forwards;
}

.hero-buttons {
    display: flex;
    gap: 1.5rem;
    justify-content: center;
    opacity: 0;
    animation: fadeInUp 0.8s ease 1s forwards;
}

.scroll-indicator {
    position: absolute;
    bottom: 40px;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
    color: var(--white);
    font-size: 0.85rem;
    letter-spacing: 1px;
    z-index: 2;
    opacity: 0;
    animation: fadeIn 1s ease 1.5s forwards;
}

.scroll-line {
    width: 1px;
    height: 40px;
    background: var(--white);
    margin: 10px auto 0;
    animation: scrollLine 2s ease-in-out infinite;
}

@keyframes fadeInUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
    from {
        transform: translateY(30px);
    }
}

@keyframes fadeIn {
    to {
        opacity: 1;
    }
}

@keyframes scrollLine {
    0%, 100% {
        transform: scaleY(0);
        transform-origin: top;
    }
    50% {
        transform: scaleY(1);
        transform-origin: top;
    }
}

/* ===== О СТУДИИ ===== */
.about {
    padding: 120px 0;
    background: var(--white);
}

.about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    align-items: center;
}

.about-description {
    font-size: 1.1rem;
    line-height: 1.8;
    color: var(--text-light);
    margin-bottom: 1.5rem;
}

.about-features {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
    margin-top: 3rem;
}

.feature-item {
    text-align: center;
}

.feature-number {
    font-size: 2.5rem;
    font-weight: 300;
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

.feature-text {
    font-size: 0.9rem;
    color: var(--text-light);
}

.about-image {
    position: relative;
}

.image-placeholder {
    position: relative;
    padding-bottom: 120%;
    overflow: hidden;
    border-radius: 2px;
}

.image-placeholder img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: var(--transition);
}

.image-placeholder:hover img {
    transform: scale(1.05);
}

/* ===== УСЛУГИ ===== */
.services {
    padding: 120px 0;
    background: var(--bg-light);
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 2rem;
}

.service-card {
    background: var(--white);
    padding: 3rem 2rem;
    border-radius: 2px;
    transition: var(--transition);
    border: 1px solid transparent;
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
    border-color: var(--primary-color);
}

.service-icon {
    width: 60px;
    height: 60px;
    background: var(--bg-light);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 1.5rem;
    color: var(--primary-color);
}

.service-title {
    font-size: 1.8rem;
    font-weight: 400;
    margin-bottom: 2rem;
    color: var(--secondary-color);
}

.service-list {
    list-style: none;
    margin-bottom: 2rem;
}

.service-list li {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0;
    border-bottom: 1px solid #eee;
}

.service-name {
    font-size: 0.95rem;
    color: var(--text-color);
}

.service-price {
    font-weight: 600;
    color: var(--primary-color);
    font-size: 1.1rem;
}

/* ===== ГАЛЕРЕЯ ===== */
.gallery {
    padding: 120px 0;
    background: var(--white);
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
}

.gallery-item {
    position: relative;
    padding-bottom: 100%;
    overflow: hidden;
    border-radius: 2px;
    cursor: pointer;
}

.gallery-item img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: var(--transition);
}

.gallery-overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(26, 26, 26, 0.8);
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    transition: var(--transition);
}

.gallery-title {
    color: var(--white);
    font-size: 1.2rem;
    font-weight: 300;
    letter-spacing: 1px;
}

.gallery-item:hover img {
    transform: scale(1.1);
}

.gallery-item:hover .gallery-overlay {
    opacity: 1;
}

/* ===== ОТЗЫВЫ ===== */
.reviews {
    padding: 120px 0;
    background: var(--bg-light);
}

.reviews-slider {
    position: relative;
    max-width: 900px;
    margin: 0 auto;
}

.reviews-container {
    display: flex;
    gap: 2rem;
    overflow-x: auto;
    scroll-snap-type: x mandatory;
    scroll-behavior: smooth;
    -webkit-overflow-scrolling: touch;
    scrollbar-width: none;
    padding: 1rem 0;
}

.reviews-container::-webkit-scrollbar {
    display: none;
}

.review-card {
    flex: 0 0 100%;
    scroll-snap-align: start;
    background: var(--white);
    padding: 3rem;
    border-radius: 2px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
}

.review-stars {
    color: var(--primary-color);
    font-size: 1.5rem;
    margin-bottom: 1.5rem;
}

.review-text {
    font-size: 1.1rem;
    line-height: 1.8;
    color: var(--text-color);
    margin-bottom: 2rem;
    font-style: italic;
}

.review-author {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.author-avatar {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: var(--primary-color);
    color: var(--secondary-color);
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 600;
    font-size: 1.2rem;
}

.author-name {
    font-weight: 600;
    color: var(--secondary-color);
}

.author-date {
    font-size: 0.9rem;
    color: var(--text-light);
}

.slider-controls {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 2rem;
}

.slider-btn {
    width: 50px;
    height: 50px;
    border: 1px solid var(--primary-color);
    background: transparent;
    color: var(--primary-color);
    border-radius: 50%;
    cursor: pointer;
    font-size: 1.5rem;
    transition: var(--transition);
}

.slider-btn:hover {
    background: var(--primary-color);
    color: var(--secondary-color);
}

/* ===== ОНЛАЙН-ЗАПИСЬ ===== */
.booking {
    padding: 120px 0;
    background: var(--secondary-color);
    color: var(--white);
}

.booking .section-title {
    color: var(--white);
}

.booking-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    align-items: center;
}

.booking-description {
    font-size: 1.1rem;
    line-height: 1.8;
    color: rgba(255, 255, 255, 0.8);
    margin-bottom: 2rem;
}

.booking-benefits {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.benefit-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    color: rgba(255, 255, 255, 0.9);
}

.benefit-item svg {
    color: var(--primary-color);
}

.booking-form {
    background: rgba(255, 255, 255, 0.05);
    padding: 3rem;
    border-radius: 2px;
    backdrop-filter: blur(10px);
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-input {
    width: 100%;
    padding: 15px;
    background: rgba(255, 255, 255, 0.1);
    border: 1px solid rgba(255, 255, 255, 0.2);
    border-radius: 2px;
    color: var(--white);
    font-size: 1rem;
    transition: var(--transition);
}

.form-input::placeholder {
    color: rgba(255, 255, 255, 0.5);
}

.form-input:focus {
    outline: none;
    border-color: var(--primary-color);
    background: rgba(255, 255, 255, 0.15);
}

.form-input option {
    background: var(--secondary-color);
    color: var(--white);
}

.form-note {
    font-size: 0.85rem;
    color: rgba(255, 255, 255, 0.6);
    text-align: center;
    margin-top: 1rem;
}

/* ===== КОНТАКТЫ ===== */
.contacts {
    padding: 120px 0;
    background: var(--white);
}

.contacts-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
}

.contact-items {
    display: flex;
    flex-direction: column;
    gap: 2rem;
    margin-bottom: 3rem;
}

.contact-item {
    display: flex;
    gap: 1.5rem;
}

.contact-icon {
    width: 50px;
    height: 50px;
    background: var(--bg-light);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--primary-color);
    flex-shrink: 0;
}

.contact-label {
    font-size: 0.9rem;
    color: var(--text-light);
    margin-bottom: 0.3rem;
}

.contact-value {
    font-size: 1.1rem;
    color: var(--secondary-color);
    font-weight: 500;
}

.social-links {
    display: flex;
    gap: 1rem;
}

.social-link {
    width: 50px;
    height: 50px;
    border: 1px solid var(--primary-color);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--primary-color);
    transition: var(--transition);
}

.social-link:hover {
    background: var(--primary-color);
    color: var(--secondary-color);
}

.map-container {
    height: 500px;
    border-radius: 2px;
    overflow: hidden;
}

/* ===== ФУТЕР ===== */
.footer {
    background: var(--secondary-color);
    color: var(--white);
    padding: 3rem 0;
}

.footer-content {
    text-align: center;
}

.footer-logo {
    font-size: 1.5rem;
    font-weight: 600;
    letter-spacing: 2px;
    margin-bottom: 1rem;
    color: var(--primary-color);
}

.footer-text {
    color: rgba(255, 255, 255, 0.6);
    font-size: 0.9rem;
}

/* ===== КНОПКА "НАВЕРХ" ===== */
.scroll-top {
    position: fixed;
    bottom: 30px;
    right: 30px;
    width: 50px;
    height: 50px;
    background: var(--primary-color);
    color: var(--secondary-color);
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    visibility: hidden;
    transition: var(--transition);
    z-index: 999;
}

.scroll-top.visible {
    opacity: 1;
    visibility: visible;
}

.scroll-top:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(212, 175, 55, 0.3);
}

/* ===== АДАПТИВНОСТЬ ===== */
@media (max-width: 1024px) {
    .about-grid,
    .booking-content,
    .contacts-grid {
        grid-template-columns: 1fr;
        gap: 3rem;
    }

    .about-features {
        grid-template-columns: repeat(3, 1fr);
    }
}

@media (max-width: 768px) {
    .nav-menu {
        position: fixed;
        top: 0;
        right: -100%;
        width: 70%;
        height: 100vh;
        background: var(--white);
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 2rem;
        transition: var(--transition);
        box-shadow: -5px 0 20px rgba(0, 0, 0, 0.1);
    }

    .nav-menu.active {
        right: 0;
    }

    .nav-menu .nav-link {
        color: var(--secondary-color);
        font-size: 1.2rem;
    }

    .btn-nav {
        display: none;
    }

    .menu-toggle {
        display: flex;
        z-index: 1001;
    }

    .menu-toggle.active span:nth-child(1) {
        transform: rotate(45deg) translate(8px, 8px);
    }

    .menu-toggle.active span:nth-child(2) {
        opacity: 0;
    }

    .menu-toggle.active span:nth-child(3) {
        transform: rotate(-45deg) translate(7px, -7px);
    }

    .hero-title {
        font-size: 3rem;
    }

    .hero-buttons {
        flex-direction: column;
        align-items: center;
    }

    .hero-buttons .btn-large {
        width: 100%;
        max-width: 300px;
    }

    .about-features {
        grid-template-columns: 1fr;
        gap: 2rem;
    }

    .services-grid {
        grid-template-columns: 1fr;
    }

    .gallery-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 1rem;
    }

    .booking-form {
        padding: 2rem;
    }

    .map-container {
        height: 350px;
    }
}

@media (max-width: 480px) {
    .container {
        padding: 0 15px;
    }

    .section-title {
        font-size: 2rem;
    }

    .hero-title {
        font-size: 2.5rem;
    }

    .hero-subtitle {
        font-size: 1rem;
    }

    .gallery-grid {
        grid-template-columns: 1fr;
    }

    .review-card {
        padding: 2rem;
    }

    .booking-form {
        padding: 1.5rem;
    }

    .scroll-top {
        width: 45px;
        height: 45px;
        bottom: 20px;
        right: 20px;
    }
}

/* ===== АНИМАЦИИ ПРИ СКРОЛЛЕ ===== */
.fade-in {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.6s ease, transform 0.6s ease;
}

.fade-in.visible {
    opacity: 1;
    transform: translateY(0);
}
// ===== НАВИГАЦИЯ =====
const navbar = document.getElementById('navbar');
const menuToggle = document.getElementById('menuToggle');
const navMenu = document.getElementById('navMenu');
const navLinks = document.querySelectorAll('.nav-link');

// Изменение навигации при скролле
window.addEventListener('scroll', () => {
    if (window.scrollY > 100) {
        navbar.classList.add('scrolled');
    } else {
        navbar.classList.remove('scrolled');
    }
});

// Мобильное меню
menuToggle.addEventListener('click', () => {
    menuToggle.classList.toggle('active');
    navMenu.classList.toggle('active');
    document.body.style.overflow = navMenu.classList.contains('active') ? 'hidden' : '';
});

// Закрытие меню при клике на ссылку
navLinks.forEach(link => {
    link.addEventListener('click', () => {
        menuToggle.classList.remove('active');
        navMenu.classList.remove('active');
        document.body.style.overflow = '';
    });
});

// Закрытие меню при клике вне его
document.addEventListener('click', (e) => {
    if (!navMenu.contains(e.target) && !menuToggle.contains(e.target)) {
        menuToggle.classList.remove('active');
        navMenu.classList.remove('active');
        document.body.style.overflow = '';
    }
});

// ===== ПЛАВНАЯ ПРОКРУТКА =====
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            const offsetTop = target.offsetTop - 80;
            window.scrollTo({
                top: offsetTop,
                behavior: 'smooth'
            });
        }
    });
});

// ===== СЛАЙДЕР ОТЗЫВОВ =====
const reviewsContainer = document.getElementById('reviewsContainer');
const prevBtn = document.getElementById('prevBtn');
const nextBtn = document.getElementById('nextBtn');

let currentSlide = 0;
const slides = document.querySelectorAll('.review-card');
const totalSlides = slides.length;

function updateSlider() {
    const slideWidth = reviewsContainer.offsetWidth;
    reviewsContainer.scrollTo({
        left: slideWidth * currentSlide,
        behavior: 'smooth'
    });
}

prevBtn.addEventListener('click', () => {
    currentSlide = currentSlide > 0 ? currentSlide - 1 : totalSlides - 1;
    updateSlider();
});

nextBtn.addEventListener('click', () => {
    currentSlide = currentSlide < totalSlides - 1 ? currentSlide + 1 : 0;
    updateSlider();
});

// Автопрокрутка слайдера
let autoSlide = setInterval(() => {
    currentSlide = currentSlide < totalSlides - 1 ? currentSlide + 1 : 0;
    updateSlider();
}, 5000);

// Остановка автопрокрутки при взаимодействии
reviewsContainer.addEventListener('mouseenter', () => {
    clearInterval(autoSlide);
});

reviewsContainer.addEventListener('mouseleave', () => {
    autoSlide = setInterval(() => {
        currentSlide = currentSlide < totalSlides - 1 ? currentSlide + 1 : 0;
        updateSlider();
    }, 5000);
});

// Свайп для мобильных устройств
let touchStartX = 0;
let touchEndX = 0;

reviewsContainer.addEventListener('touchstart', (e) => {
    touchStartX = e.changedTouches[0].screenX;
});

reviewsContainer.addEventListener('touchend', (e) => {
    touchEndX = e.changedTouches[0].screenX;
    handleSwipe();
});

function handleSwipe() {
    if (touchEndX < touchStartX - 50) {
        // Свайп влево
        currentSlide = currentSlide < totalSlides - 1 ? currentSlide + 1 : 0;
        updateSlider();
    }
    if (touchEndX > touchStartX + 50) {
        // Свайп вправо
        currentSlide = currentSlide > 0 ? currentSlide - 1 : totalSlides - 1;
        updateSlider();
    }
}

// ===== ФОРМА ЗАПИСИ =====
const bookingForm = document.getElementById('bookingForm');

bookingForm.addEventListener('submit', (e) => {
    e.preventDefault();
    
    // Получение данных формы
    const formData = new FormData(bookingForm);
    
    // Здесь должна быть отправка данных на сервер
    // Для демонстрации просто показываем сообщение
    alert('Спасибо за заявку! Мы свяжемся с вами в ближайшее время.');
    
    // Очистка формы
    bookingForm.reset();
});

// ===== КНОПКА "НАВЕРХ" =====
const scrollTopBtn = document.getElementById('scrollTop');

window.addEventListener('scroll', () => {
    if (window.scrollY > 500) {
        scrollTopBtn.classList.add('visible');
    } else {
        scrollTopBtn.classList.remove('visible');
    }
});

scrollTopBtn.addEventListener('click', () => {
    window.scrollTo({
        top: 0,
        behavior: 'smooth'
    });
});

// ===== АНИМАЦИЯ ПРИ СКРОЛЛЕ =====
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('visible');
        }
    });
}, observerOptions);

// Добавление класса fade-in к элементам
document.querySelectorAll('.service-card, .gallery-item, .review-card, .contact-item').forEach(el => {
    el.classList.add('fade-in');
    observer.observe(el);
});

// ===== ВАЛИДАЦИЯ ТЕЛЕФОНА =====
const phoneInputs = document.querySelectorAll('input[type="tel"]');

phoneInputs.forEach(input => {
    input.addEventListener('input', (e) => {
        let value = e.target.value.replace(/\D/g, '');
        
        if (value.length > 0) {
            if (value[0] === '8') {
                value = '7' + value.slice(1);
            }
            
            let formattedValue = '+7';
            
            if (value.length > 1) {
                formattedValue += ' (' + value.substring(1, 4);
            }
            if (value.length >= 5) {
                formattedValue += ') ' + value.substring(4, 7);
            }
            if (value.length >= 8) {
                formattedValue += '-' + value.substring(7, 9);
            }
            if (value.length >= 10) {
                formattedValue += '-' + value.substring(9, 11);
            }
            
            e.target.value = formattedValue;
        }
    });
});

// ===== УСТАНОВКА МИНИМАЛЬНОЙ ДАТЫ ДЛЯ ЗАПИСИ =====
const dateInputs = document.querySelectorAll('input[type="date"]');
const today = new Date().toISOString().split('T')[0];

dateInputs.forEach(input => {
    input.setAttribute('min', today);
});

// ===== ПРЕЛОАДЕР (опционально) =====
window.addEventListener('load', () => {
    document.body.classList.add('loaded');
});

// ===== ПАРАЛЛАКС ЭФФЕКТ ДЛЯ HERO =====
const hero = document.querySelector('.hero');

window.addEventListener('scroll', () => {
    const scrolled = window.scrollY;
    if (hero && scrolled < window.innerHeight) {
        hero.style.transform = `translateY(${scrolled * 0.5}px)`;
    }
});

// ===== СЧЕТЧИК ДЛЯ СТАТИСТИКИ =====
function animateCounter(element, target, duration = 2000) {
    let start = 0;
    const increment = target / (duration / 16);
    
    const timer = setInterval(() => {
        start += increment;
        if (start >= target) {
            element.textContent = target + '+';
            clearInterval(timer);
        } else {
            element.textContent = Math.floor(start) + '+';
        }
    }, 16);
}

// Запуск счетчика при появлении в viewport
const featureNumbers = document.querySelectorAll('.feature-number');
let countersAnimated = false;

const counterObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting && !countersAnimated) {
            featureNumbers.forEach(number => {
                const target = parseInt(number.textContent);
                animateCounter(number, target);
            });
            countersAnimated = true;
        }
    });
}, { threshold: 0.5 });

const aboutSection = document.querySelector('.about');
if (aboutSection) {
    counterObserver.observe(aboutSection);
}

// ===== ЛЕНИВАЯ ЗАГРУЗКА ИЗОБРАЖЕНИЙ =====
const images = document.querySelectorAll('img[data-src]');

const imageObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            const img = entry.target;
            img.src = img.dataset.src;
            img.removeAttribute('data-src');
            imageObserver.unobserve(img);
        }
    });
});

images.forEach(img => imageObserver.observe(img));

// ===== МОДАЛЬНОЕ ОКНО ДЛЯ ГАЛЕРЕИ (опционально) =====
const galleryItems = document.querySelectorAll('.gallery-item');

galleryItems.forEach(item => {
    item.addEventListener('click', () => {
        const img = item.querySelector('img');
        if (img) {
            // Здесь можно добавить открытие модального окна с увеличенным изображением
            console.log('Открыть изображение:', img.src);
        }
    });
});

console.log('🎨 Сайт Kshatri Beauty Studio загружен успешно!');

# E-COMMERCE  JUAN DAVID MADRID CÀRCAMO



en la realización del trabajo mi función fue realizar la parte de fags ("fag.html")guiándome de los videos compartidos por el instructor

trabaje en la siguientes partes:

-  *<!--=============== HEADER ===============-->*
- *<!--=============== CART ===============-->*
- *<!--=============== LOGIN ===============-->*
- *<!--=============== MAIN ===============-->*
- *<!--=============== FOOTER ===============-->*
- *<!--=============== SCROLL UP ===============-->*
-  *<!--=============== STYLE SWITCHER ===============-->*

evidencia de la codificación:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--=============== BOXICONS ===============-->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">

    <!--=============== SWIPER CSS ===============-->
    <link rel="stylesheet" href="assets/css/swiper-bundle.min.css">

    <!--=============== CSS ===============-->
    <link rel="stylesheet" href="assets/css/style.css">
    <link rel="stylesheet" href="assets/css/colors/color-1.css">

    <title>Responsive e-commerce website - Crypticalcoder</title>
</head>
<body>
    <!--=============== HEADER ===============-->
    <header class="header" id="header">
        <nav class="nav container">
            <a href="index.html" class="nav__logo">
                <i class="bx bxs-shopping-bags nav__logo-icon"></i> e-shopper
            </a>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav-item">
                        <a href="index.html" class="nav__link">Home</a>
                    </li>

                    <li class="nav-item">
                        <a href="shop.html" class="nav__link">Shop</a>
                    </li>

                    <li class="nav-item">
                        <a href="about.html" class="nav__link">About</a>
                    </li>

                    <li class="nav-item">
                        <a href="blog.html" class="nav__link active-link">Blog</a>
                    </li>

                    <li class="nav-item">
                        <a href="faq.html" class="nav__link active-link">Faq's</a>
                    </li>

                    <li class="nav-item">
                        <a href="contact.html" class="nav__link">Contact</a>
                    </li>
                </ul>

                <div class="nav__close" id="nav-close">
                    <i class="bx bx-x"></i>
                </div>
            </div>

            <div class="nav__btns">
                <div class="login__toggle" id="login__button">
                    <i class="bx bx-user"></i>
                </div>

                <div class="nav__shop" id="cart-shop">
                    <i class="bx bxs-shopping-bags"></i>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class="bx bx-grid-alt"></i>
                </div>
            </div>
        </nav>
    </header>

    <!--=============== CART ===============-->
    <div class="cart" id="cart">
        <i class="bx bx-x cart__close" id="card-close"></i>
        <h2 class="cart__title-center"></h2>

        <div class="cart__container">
            <article class="cart__card">
                <div class="car__box">
                    <img src="assets/img/cart-1.png" alt="" class="cart__img">
                </div>
                <div class="cat__details">
                    <h3 class="cart__title">Windbreaker</h3>
                    <span class="cart__price">$12</span>
                    <div class="cart__amount">
                        <div class="cart__amount-contend">
                            <span class="cart__amount-box">
                                <i class="bx bx-minus"></i>
                            </span>


                            <span class="cart__amount-number">1</span>
                            <span class="cart__amount-box">
                                <i class="bx bx-plus"></i>
                            </span>
                        </div>
                        <i class="bx bx-trash-alt cart__amount-trash"></i>
                    </div>
                </div>
            </article>
            <article class="cart__card">
                <div class="car__box">
                    <img src="assets/img/cart-2.png" alt="" class="cart__img">
                </div>
                <div class="cat__details">
                    <h3 class="cart__title">Cardigan Hoodie</h3>
                    <span class="cart__price">$16</span>
                    <div class="cart__amount">
                        <div class="cart__amount-contend">
                            <span class="cart__amount-box">
                                <i class="bx bx-minus"></i>
                            </span>


                            <span class="cart__amount-number">1</span>
                            <span class="cart__amount-box">
                                <i class="bx bx-plus"></i>
                            </span>
                        </div>
                        <i class="bx bx-trash-alt cart__amount-trash"></i>
                    </div>
                </div>
            </article>
            <article class="cart__card">
                <div class="car__box">
                    <img src="assets/img/cart-3.png" alt="" class="cart__img">
                </div>
                <div class="cat__details">
                    <h3 class="cart__title">Cartoon</h3>
                    <span class="cart__price">$10</span>
                    <div class="cart__amount">
                        <div class="cart__amount-contend">
                            <span class="cart__amount-box">
                                <i class="bx bx-minus"></i>
                            </span>


                            <span class="cart__amount-number">1</span>
                            <span class="cart__amount-box">
                                <i class="bx bx-plus"></i>
                            </span>
                        </div>
                        <i class="bx bx-trash-alt cart__amount-trash"></i>
                    </div>
                </div>
            </article>
            <div class="cart_prices">
                <span class="cart__prices-item">3 items</span>
                <span class="cart__prices-total">$38</span>
            </div>
        </div>
    </div>

    <!--=============== LOGIN ===============-->
    <div class="login" id="login">
        <i class="bx bx-x login__close" id="login-close"></i>
        <h2 class="login__title-center">Login</h2>
        <form action="" class="login__form gird">
            <div class="login__content">
                <label for="" class="login__label">Email</label>
                <input type="email" class="login__input">
            </div>

            <div class="login__content">
                <label for="" class="login__label">Password</label>
                <input type="password" class="login__input">
            </div>
            <div>
                <a href="#" class="button">Sign in</a>
            </div>
            <div>
                <p class="signup">Not a member? <a href="registration.html">Sign up now</a></p>
            </div>
        </form>
    </div>

    <!--=============== MAIN ===============-->
    <main class="main">
        <!--=============== FAQ'S ===============-->
        <section class="questions section container">
            <h2 class="breadcrumb__title">FAQ'S Page</h2>
            <h3 class="breadcrumb__subtitle"><span>FAQ'S</span></h3>

            <div class="questions__container grid">
                <div class="questions__group">
                    <div class="questions__item">
                        <header class="questions__header">
                            <i class="bx bx-plus questions__icon"></i>
                            <h3 class="questions__item-title">Lorem ipsum dolor sit amet.</h3>
                        </header>

                        <div class="questions__content">
                            <p class="questions__description">
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis quo blanditiis esse perferendis voluptas, fugit consectetur maiores alias?
                            </p>
                        </div>
                    </div>

                    <div class="questions__item">
                        <header class="questions__header">
                            <i class="bx bx-plus questions__icon"></i>
                            <h3 class="questions__item-title">Lorem ipsum dolor sit amet.</h3>
                        </header>

                        <div class="questions__content">
                            <p class="questions__description">
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis quo blanditiis esse perferendis voluptas, fugit consectetur maiores alias?
                            </p>
                        </div>
                    </div>

                    <div class="questions__item">
                        <header class="questions__header">
                            <i class="bx bx-plus questions__icon"></i>
                            <h3 class="questions__item-title">Lorem ipsum dolor sit amet.</h3>
                        </header>

                        <div class="questions__content">
                            <p class="questions__description">
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis quo blanditiis esse perferendis voluptas, fugit consectetur maiores alias?
                            </p>
                        </div>
                    </div>
                </div>

                <div class="questions__group">
                    <div class="questions__item">
                        <header class="questions__header">
                            <i class="bx bx-plus questions__icon"></i>
                            <h3 class="questions__item-title">Lorem ipsum dolor sit amet.</h3>
                        </header>

                        <div class="questions__content">
                            <p class="questions__description">
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis quo blanditiis esse perferendis voluptas, fugit consectetur maiores alias?
                            </p>
                        </div>
                    </div>

                    <div class="questions__item">
                        <header class="questions__header">
                            <i class="bx bx-plus questions__icon"></i>
                            <h3 class="questions__item-title">Lorem ipsum dolor sit amet.</h3>
                        </header>

                        <div class="questions__content">
                            <p class="questions__description">
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis quo blanditiis esse perferendis voluptas, fugit consectetur maiores alias?
                            </p>
                        </div>
                    </div>

                    <div class="questions__item">
                        <header class="questions__header">
                            <i class="bx bx-plus questions__icon"></i>
                            <h3 class="questions__item-title">Lorem ipsum dolor sit amet.</h3>
                        </header>

                        <div class="questions__content">
                            <p class="questions__description">
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis quo blanditiis esse perferendis voluptas, fugit consectetur maiores alias?
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!--=============== FOOTER ===============-->
    <footer class="footer section">
        <div class="footer__container container grid">
            <!-- FOOTER CONTENT 1 -->
            <div class="footer__content">
                <a href="#" class="footer__Logo">
                    <i class="bx bxs-shopping-bags footer__logo-icon"></i> e-shopper
                </a>
                <p class="footer__description">Enjoy the biggest sale <br> of your life.</p>
                <div class="footer__social">
                    <a href="#" class="footer__social-link"> <i class="bx bxl-facebook"></i></a>
                    <a href="#" class="footer__social-link"> <i class="bx bxl-instagram"></i></a>
                    <a href="#" class="footer__social-link"> <i class="bx bxl-twitter"></i></a>
                </div>
            </div>
            <!-- FOOTER CONTENT 2 -->
            <div class="footer__content">
                <h3 class="footer__title">About</h3>
                <ul class="footer__links">
                    <li><a href="#" class="footer__link">About Us</a></li>
                    <li><a href="#" class="footer__link">Customer Support</a></li>
                    <li><a href="#" class="footer__link">Support Center</a></li>
                </ul>
            </div>
            <!-- FOOTER CONTENT 3 -->
            <div class="footer__content">
                <h3 class="footer__title">Our Services</h3>
                <ul class="footer__links">
                    <li><a href="#" class="footer__link">Shop</a></li>
                    <li><a href="#" class="footer__link">Discounts</a></li>
                    <li><a href="#" class="footer__link">Shipping mode</a></li>
                </ul>
            </div>
            <!-- FOOTER CONTENT 4 -->
            <div class="footer__content">
                <h3 class="footer__title">Our Company</h3>
                <ul class="footer__links">
                    <li><a href="#" class="footer__link">Register</a></li>
                    <li><a href="#" class="footer__link">Contact US</a></li>
                    <li><a href="#" class="footer__link">About Us</a></li>
                </ul>
            </div>
        </div>
        <span class="footer__copy">&#169; Crypticalcoder. All rights reserved</span>
    </footer>

    <!--=============== SCROLL UP ===============-->
    <a href="#" class="scrollup" id="scroll-up">
        <i class="bx bx-up-arrow-alt scrollup__icon"></i>
    </a>
    <!--=============== STYLE SWITCHER ===============-->
    <div class="style__switcher">
        <div class="style__switcher-toggler s__icon">
            <i class="bx bxs-cog bx-spin"></i>
        </div>
        <h4>Theme Colors</h4>

        <div class="theme__colors js-theme-colors">
            <button type="button" class="js-theme-color-item theme__button color-1"><i class="bx bx-check"></i></button>
            <button type="button" class="js-theme-color-item theme__button color-2"><i class="bx bx-check"></i></button>
            <button type="button" class="js-theme-color-item theme__button color-3"><i class="bx bx-check"></i></button>
            <button type="button" class="js-theme-color-item theme__button color-4"><i class="bx bx-check"></i></button>
            <button type="button" class="js-theme-color-item theme__button color-5"><i class="bx bx-check"></i></button>
        </div>
    </div>
    <!--=============== SWIPER JS ===============-->
    <script src="assets/js/swiper-bundle.min.js"></script>

    <!--=============== JS ===============-->
    <script src="assets/js/main.js"></script>
</body>
</html>
```

y asi finaliza mi parte en la colaboracion de este proyecto.

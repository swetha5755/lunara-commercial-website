## Program:
index.html
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUNARA | Fashion Store</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Announcement Bar -->
    <div class="announcement">
        FREE SHIPPING ON ORDERS ABOVE ₹1999 | NEW COLLECTION 2026
    </div>

    <!-- Navigation -->
    <header class="navbar">
        <div class="logo">LUNARA</div>

        <nav>
            <a href="#home">Home</a>
            <a href="#categories">Categories</a>
            <a href="#products">Shop</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>

        <div class="cart">
            <a href="#products">My Cart ♡</a>
        </div>
    </header>

    <!-- Hero -->
    <section class="hero" id="home">

        <div class="hero-content">
            <p class="tagline">NEW COLLECTION 2026</p>

            <h1>Discover Your<br>Own Style.</h1>

            <p>
                Explore timeless fashion, beautiful details
                and collections designed to make you feel confident.
            </p>

            <a href="#products" class="shop-button">
                Explore Collection
            </a>
        </div>

        <div class="hero-image">
            <img
                src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?w=900"
                alt="Fashion model wearing an elegant outfit">
        </div>

    </section>

    <!-- Categories -->
    <section class="categories" id="categories">

        <h2>Shop By Category</h2>
        <p>Find something that feels like you.</p>

        <div class="category-container">

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1483985988355-763728e1935b?w=600"
                     alt="Women's clothing">
                <h3>Clothing</h3>
            </div>

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1611652022419-a9419f74343d?w=600"
                     alt="Jewellery">
                <h3>Jewellery</h3>
            </div>

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1584917865442-de89df76afd3?w=600"
                     alt="Fashion accessories">
                <h3>Accessories</h3>
            </div>

        </div>

    </section>

    <!-- Featured Products -->
    <section class="products" id="products">

        <h2>Our Best Sellers</h2>
        <p>Handpicked styles for your everyday elegance.</p>

        <div class="product-container">

            <!-- Product 1 -->
            <article class="product-card">
                <span class="sale-badge">20% OFF</span>

                <img src="https://images.unsplash.com/photo-1539008835657-9e8e9680c956?w=600"
                     alt="Elegant women's dress">

                <div class="product-info">
                    <p class="product-category">WOMEN'S CLOTHING</p>
                    <h3>Elegant Dress</h3>
                    <p class="rating">★★★★★ <span>(4.8)</span></p>
                    <p class="price">
                        ₹1,499 <del>₹1,899</del>
                    </p>
                    <button class="add-cart">Add to Cart</button>
                </div>
            </article>

            <!-- Product 2 -->
            <article class="product-card">
                <span class="sale-badge">NEW</span>

                <img src="https://images.unsplash.com/photo-1548036328-c9fa89d128fa?w=600"
                     alt="Classic handbag">

                <div class="product-info">
                    <p class="product-category">ACCESSORIES</p>
                    <h3>Classic Handbag</h3>
                    <p class="rating">★★★★★ <span>(4.7)</span></p>
                    <p class="price">
                        ₹1,899 <del>₹2,299</del>
                    </p>
                    <button class="add-cart">Add to Cart</button>
                </div>
            </article>

            <!-- Product 3 -->
            <article class="product-card">
                <span class="sale-badge">BESTSELLER</span>

                <img src="https://images.unsplash.com/photo-1617038220319-276d3cfab638?w=600"
                     alt="Golden jewellery">

                <div class="product-info">
                    <p class="product-category">JEWELLERY</p>
                    <h3>Golden Jewellery</h3>
                    <p class="rating">★★★★★ <span>(4.9)</span></p>
                    <p class="price">
                        ₹799 <del>₹999</del>
                    </p>
                    <button class="add-cart">Add to Cart</button>
                </div>
            </article>

            <!-- Product 4 -->
            <article class="product-card">
                <span class="sale-badge">15% OFF</span>

                <img src="https://images.unsplash.com/photo-1543163521-1bf539c55dd2?w=600"
                     alt="Classic heels">

                <div class="product-info">
                    <p class="product-category">FOOTWEAR</p>
                    <h3>Classic Heels</h3>
                    <p class="rating">★★★★☆ <span>(4.5)</span></p>
                    <p class="price">
                        ₹1,299 <del>₹1,599</del>
                    </p>
                    <button class="add-cart">Add to Cart</button>
                </div>
            </article>

        </div>

    </section>

    <!-- Special Offer -->
    <section class="offer">

        <div>
            <p>LIMITED TIME OFFER</p>
            <h2>Get 20% OFF</h2>
            <p>On your first purchase with LUNARA.</p>
            <a href="#products">Shop the Offer</a>
        </div>

    </section>

    <!-- About -->
    <section class="about" id="about">

        <h2>Our Story</h2>

        <p>
            At LUNARA, we believe fashion is a form of self-expression.
            Our collections bring together timeless elegance,
            everyday comfort and modern style.
            We want everyone to feel confident in what they wear.
        </p>

    </section>

    <!-- Newsletter -->
    <section class="newsletter">

        <h2>Join the LUNARA Community</h2>

        <p>
            Subscribe to receive updates about new arrivals,
            exclusive offers and fashion inspiration.
        </p>

        <form action="#" method="get">
            <input type="email" name="email"
                   placeholder="Enter your email address"
                   required>
            <button type="submit">Subscribe</button>
        </form>

    </section>

    <!-- Footer -->
    <footer id="contact">

        <h2>LUNARA</h2>
        <p>Style Beyond Trends.</p>

        <div class="footer-links">
            <a href="#home">Home</a>
            <a href="#products">Shop</a>
            <a href="#about">About Us</a>
            <a href="mailto:hello@lunara.com">Email Us</a>
        </div>

        <p class="copyright">
            &copy; 2026 LUNARA. All Rights Reserved.
        </p>

    </footer>

</body>
</html>

```
style.css
```

/* GENERAL STYLING */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    background-color: #fffaf7;
    color: #493b40;
}

/* ANNOUNCEMENT BAR */

.announcement {
    background-color: #65465b;
    color: white;
    text-align: center;
    padding: 12px;
    font-size: 12px;
    letter-spacing: 2px;
}

/* NAVIGATION */

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 22px 7%;
    background-color: #f3e7e8;
}

.logo {
    font-family: Georgia, serif;
    font-size: 30px;
    font-weight: bold;
    letter-spacing: 4px;
    color: #79546c;
}

.navbar nav {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 28px;
}

.navbar a {
    text-decoration: none;
    color: #493b40;
    font-size: 15px;
}

.navbar a:hover {
    color: #a46b87;
}

.cart a {
    font-weight: bold;
}

/* HERO */

.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 65px 7%;
    gap: 40px;
    background-color: #f9eeee;
}

.hero-content {
    flex: 1;
}

.tagline {
    color: #a46b87;
    letter-spacing: 4px;
    font-weight: bold;
    margin-bottom: 20px;
}

.hero-content h1 {
    font-family: Georgia, serif;
    font-size: 58px;
    line-height: 1.15;
    color: #65465b;
    margin-bottom: 20px;
}

.hero-content p {
    font-size: 17px;
    line-height: 1.8;
    max-width: 480px;
}

.shop-button {
    display: inline-block;
    margin-top: 25px;
    padding: 15px 28px;
    background-color: #956b82;
    color: white;
    text-decoration: none;
}

.shop-button:hover {
    background-color: #70475e;
}

.hero-image {
    flex: 1;
}

.hero-image img {
    width: 100%;
    height: 430px;
    object-fit: cover;
}

/* CATEGORIES */

.categories,
.products {
    padding: 65px 7%;
    text-align: center;
}

.categories h2,
.products h2,
.about h2 {
    font-family: Georgia, serif;
    font-size: 36px;
    color: #79546c;
    margin-bottom: 12px;
}

.categories > p,
.products > p {
    margin-bottom: 35px;
    color: #806f76;
}

.category-container {
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 25px;
    flex-wrap: wrap;
}

.category-card {
    flex: 1 1 220px;
    max-width: 330px;
    background-color: #f5e8eb;
    padding-bottom: 18px;
}

.category-card img {
    width: 100%;
    height: 280px;
    object-fit: cover;
}

.category-card h3 {
    margin-top: 15px;
    color: #79546c;
}

/* PRODUCTS */

.products {
    background-color: #f8eff0;
}

.product-container {
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 25px;
    flex-wrap: wrap;
}

.product-card {
    position: relative;
    flex: 1 1 210px;
    max-width: 270px;
    background-color: white;
    text-align: left;
    overflow: hidden;
}

.product-card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.product-info {
    padding: 16px;
}

.sale-badge {
    position: absolute;
    top: 12px;
    left: 12px;
    background-color: #a46b87;
    color: white;
    padding: 7px 10px;
    font-size: 11px;
    font-weight: bold;
}

.product-category {
    font-size: 10px;
    letter-spacing: 1px;
    color: #a46b87;
    margin-bottom: 8px;
}

.product-card h3 {
    color: #65465b;
    margin-bottom: 8px;
}

.rating {
    color: #c48a49;
    font-size: 14px;
    margin-bottom: 10px;
}

.rating span {
    color: #806f76;
}

.price {
    font-size: 17px;
    font-weight: bold;
    margin-bottom: 15px;
    color: #65465b;
}

.price del {
    font-size: 13px;
    font-weight: normal;
    color: #999;
    margin-left: 5px;
}

.add-cart {
    width: 100%;
    padding: 11px;
    border: none;
    background-color: #956b82;
    color: white;
    cursor: pointer;
}

.add-cart:hover {
    background-color: #70475e;
}

/* SPECIAL OFFER */

.offer {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    min-height: 270px;
    padding: 40px;
    background-color: #e9d6dc;
}

.offer h2 {
    font-family: Georgia, serif;
    font-size: 42px;
    color: #70475e;
    margin: 12px 0;
}

.offer a {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background-color: #79546c;
    color: white;
    text-decoration: none;
}

/* ABOUT */

.about {
    padding: 70px 15%;
    text-align: center;
}

.about p {
    font-size: 17px;
    line-height: 1.9;
    color: #6c5a62;
}

/* NEWSLETTER */

.newsletter {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    gap: 18px;
    padding: 55px 20px;
    background-color: #f3e7e8;
}

.newsletter h2 {
    font-family: Georgia, serif;
    color: #79546c;
    font-size: 32px;
}

.newsletter p {
    max-width: 550px;
    line-height: 1.7;
}

.newsletter form {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
}

.newsletter input {
    padding: 13px;
    width: 280px;
    border: 1px solid #c9aab9;
    background-color: white;
}

.newsletter button {
    padding: 13px 22px;
    border: none;
    background-color: #79546c;
    color: white;
    cursor: pointer;
}

/* FOOTER */

footer {
    padding: 40px 20px;
    background-color: #65465b;
    color: white;
    text-align: center;
}

footer h2 {
    font-family: Georgia, serif;
    font-size: 30px;
    letter-spacing: 4px;
}

.footer-links {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 25px;
    margin: 25px 0;
}

.footer-links a {
    color: white;
    text-decoration: none;
}

.copyright {
    margin-top: 25px;
    font-size: 13px;
}

/* TABLET RESPONSIVENESS */

@media (max-width: 768px) {

    .navbar {
        flex-direction: column;
        gap: 18px;
        text-align: center;
    }

    .navbar nav {
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
    }

    .hero {
        flex-direction: column;
        text-align: center;
    }

    .hero-content p {
        margin-left: auto;
        margin-right: auto;
    }

    .hero-content h1 {
        font-size: 42px;
    }

    .hero-image {
        width: 100%;
    }

    .hero-image img {
        height: 350px;
    }

    .category-container,
    .product-container {
        justify-content: center;
    }

    .category-card,
    .product-card {
        flex: 1 1 220px;
    }

    .about {
        padding: 45px 8%;
    }
}

/* MOBILE RESPONSIVENESS */

@media (max-width: 480px) {

    .hero-content h1 {
        font-size: 35px;
    }

    .hero-image img {
        height: 280px;
    }

    .categories h2,
    .products h2,
    .about h2 {
        font-size: 28px;
    }

    .category-card,
    .product-card {
        flex-basis: 100%;
    }

    .offer h2 {
        font-size: 32px;
    }

    .navbar nav {
        gap: 12px;
    }

    .newsletter h2 {
        font-size: 26px;
    }

    .newsletter form {
        width: 100%;
    }

    .newsletter input {
        width: 100%;
    }
}

```
## Output:
<img width="1882" height="842" alt="image" src="https://github.com/user-attachments/assets/87bcbeb6-0853-4079-9f8e-757f9a206517" />
<img width="1872" height="713" alt="image" src="https://github.com/user-attachments/assets/153d0b49-b0af-4572-9eb3-cd406c589304" />
<img width="1876" height="832" alt="image" src="https://github.com/user-attachments/assets/31613e40-73d8-4d71-a49c-bdb8d018f238" />
<img width="1873" height="652" alt="image" src="https://github.com/user-attachments/assets/497e0f72-5b85-43fc-af1e-57f7cca60d28" />
<img width="1867" height="606" alt="image" src="https://github.com/user-attachments/assets/1a930047-8df6-4286-9c5c-b1ff0c8d088c" />




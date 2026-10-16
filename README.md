<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://images.unsplash.com">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

   
    <header class="header">
        <a href="#" class="logo"><span>▶️</span> StreamVibe</a>

        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#categories">Movies & Shows</a>
            <a href="#faq">Support</a>
            <a href="#plans">Subscriptions</a>
        </nav>

        <div class="header-icons">
            <a href="#categories" aria-label="Search">⌕</a>
            <a href="#faq" aria-label="Notifications">♧</a>
        </div>
    </header>

    
    <main>
        <section class="hero" id="home">
            <div class="poster-wall">
                <img src="Sub Container (1).png" alt="">
                
            </div>

            <div class="hero-content">
                <div class="play-mark">▶️</div>
                <h1>The Best Streaming Experience</h1>
                <p>
                    StreamVibe is the best streaming experience for watching your
                    favorite movies and shows on demand, anytime, anywhere.
                    Enjoy a wide variety of content, including the latest blockbusters,
                    classic movies, popular TV shows, and more.
                </p>
                <a href="#categories" class="btn">▶️ Start Watching Now</a>
            </div>
        </section>

        
        <section class="section" id="categories">
            <div class="section-heading">
                <div>
                    <h2>Explore our wide variety of categories</h2>
                    <p>Discover movies and shows for every mood and moment.</p>
                </div>
                <div class="arrows">
                    <button type="button" aria-label="Previous">←</button>
                    <button type="button" aria-label="Next">→</button>
                </div>
            </div>

            <div class="category-grid">
                <a href="#plans" class="category-card">
                    <img src="https://images.unsplash.com/photo-1519608487953-e999c86e7455?auto=format&fit=crop&w=500&q=80" alt="Action movies">
                    <span>Action <b>→</b></span>
                </a>
                <a href="#plans" class="category-card">
                    <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=500&q=80" alt="Adventure movies">
                    <span>Adventure <b>→</b></span>
                </a>
                <a href="#plans" class="category-card">
                    <img src="https://images.unsplash.com/photo-1470225620780-dba8ba36b745?auto=format&fit=crop&w=500&q=80" alt="Comedy shows">
                    <span>Comedy <b>→</b></span>
                </a>
                <a href="#plans" class="category-card">
                    <img src="https://images.unsplash.com/photo-1478720568477-152d9b164e26?auto=format&fit=crop&w=500&q=80" alt="Drama movies">
                    <span>Drama <b>→</b></span>
                </a>
                <a href="#plans" class="category-card">
                    <img src="https://images.unsplash.com/photo-1534447677768-be436bb09401?auto=format&fit=crop&w=500&q=80" alt="Thriller and horror">
                    <span>Horror <b>→</b></span>
                </a>
            </div>
        </section>

        
        <section class="section" id="devices">
            <div class="section-heading">
                <div>
                    <h2>We Provide you streaming experience across various devices.</h2>
                    <p>Enjoy your favorite movies and TV shows on your preferred device.</p>
                </div>
            </div>

            <div class="device-grid">
                <article class="device-card">
                    <div class="device-icon">▯</div>
                    <h3>Smartphones</h3>
                    <p>Watch your favorite entertainment on your phone, wherever you go.</p>
                </article>
                <article class="device-card">
                    <div class="device-icon">▣</div>
                    <h3>Tablet</h3>
                    <p>Enjoy movies and shows on a bigger screen with a comfortable view.</p>
                </article>
                <article class="device-card">
                    <div class="device-icon">▰</div>
                    <h3>Smart TV</h3>
                    <p>Bring the cinema experience home with your favorite smart TV.</p>
                </article>
                <article class="device-card">
                    <div class="device-icon">▱</div>
                    <h3>Laptops</h3>
                    <p>Stream your favorite content on your laptop at home or on the go.</p>
                </article>
                <article class="device-card">
                    <div class="device-icon">♧</div>
                    <h3>Gaming Consoles</h3>
                    <p>Enjoy your entertainment from the comfort of your gaming setup.</p>
                </article>
                <article class="device-card">
                    <div class="device-icon">◉</div>
                    <h3>VR Headsets</h3>
                    <p>Explore a more immersive way to enjoy your entertainment.</p>
                </article>
            </div>
        </section>

        
        <section class="section" id="faq">
            <div class="section-heading">
                <div>
                    <h2>Frequently Asked Questions</h2>
                    <p>Got questions? Find answers to the most common questions below.</p>
                </div>
                <a href="mailto:support@streamvibe.example" class="btn">Ask a Question</a>
            </div>

            <div class="faq-grid">
                <div class="faq-list">
                    <details open>
                        <summary><span>01</span> What is StreamVibe?</summary>
                        <p>StreamVibe is a streaming website concept for discovering movies and shows.</p>
                    </details>
                    <details>
                        <summary><span>02</span> How much does StreamVibe cost?</summary>
                        <p>Choose a subscription plan that fits your entertainment needs.</p>
                    </details>
                    <details>
                        <summary><span>03</span> What content is available?</summary>
                        <p>Explore action, adventure, comedy, drama and horror categories.</p>
                    </details>
                    <details>
                        <summary><span>04</span> How can I watch StreamVibe?</summary>
                        <p>You can browse this website on your laptop, tablet or smartphone.</p>
                    </details>
                </div>

                <div class="faq-list">
                    <details>
                        <summary><span>05</span> How do I sign up for StreamVibe?</summary>
                        <p>Sign-up functionality can be added with a backend and user accounts.</p>
                    </details>
                    <details>
                        <summary><span>06</span> Is there a free trial?</summary>
                        <p>Free trial availability depends on the service's actual subscription setup.</p>
                    </details>
                    <details>
                        <summary><span>07</span> How do I contact customer support?</summary>
                        <p>Use the support contact provided by the website owner.</p>
                    </details>
                    <details>
                        <summary><span>08</span> What payment methods are accepted?</summary>
                        <p>Payment methods would be configured when a payment system is connected.</p>
                    </details>
                </div>
            </div>
        </section>

        
        <section class="section" id="plans">
            <div class="section-heading">
                <div>
                    <h2>Choose the plan that’s right for you</h2>
                    <p>Find a plan that matches your viewing preferences.</p>
                </div>
                <div class="billing">
                    <button class="selected" type="button">Monthly</button>
                    <button type="button">Yearly</button>
                </div>
            </div>

            <div class="pricing-grid">
                <article class="price-card">
                    <h3>Basic Plan</h3>
                    <p>Enjoy a wide library of movies and shows for everyday entertainment.</p>
                    <div class="price">$9.99 <small>/month</small></div>
                    <div class="price-actions">
                        <a href="mailto:support@streamvibe.example" class="btn-secondary">Start Free Trial</a>
                        <a href="mailto:support@streamvibe.example" class="btn">Choose Plan</a>
                    </div>
                </article>

                <article class="price-card">
                    <h3>Standard Plan</h3>
                    <p>Access a wider selection of movies and shows in your free time.</p>
                    <div class="price">$12.99 <small>/month</small></div>
                    <div class="price-actions">
                        <a href="mailto:support@streamvibe.example" class="btn-secondary">Start Free Trial</a>
                        <a href="mailto:support@streamvibe.example" class="btn">Choose Plan</a>
                    </div>
                </article>

                <article class="price-card">
                    <h3>Premium Plan</h3>
                    <p>Enjoy a premium entertainment experience across your devices.</p>
                    <div class="price">$14.99 <small>/month</small></div>
                    <div class="price-actions">
                        <a href="mailto:support@streamvibe.example" class="btn-secondary">Start Free Trial</a>
                        <a href="mailto:support@streamvibe.example" class="btn">Choose Plan</a>
                    </div>
                </article>
            </div>
        </section>

        
        <section class="trial-banner">
            <div>
                <h2>Start your free trial today!</h2>
                <p>Discover your next favorite movie or show with StreamVibe.</p>
            </div>
            <a href="mailto:support@streamvibe.example" class="btn">Start a Free Trial</a>
        </section>
    </main>

   
    <footer class="footer">
        <div class="footer-grid">
            <div>
                <h4>Home</h4>
                <a href="#categories">Categories</a>
                <a href="#devices">Devices</a>
                <a href="#plans">Pricing</a>
                <a href="#faq">FAQ</a>
            </div>
            <div>
                <h4>Movies</h4>
                <a href="#categories">Genres</a>
                <a href="#categories">Trending</a>
                <a href="#categories">New Releases</a>
                <a href="#categories">Popular</a>
            </div>
            <div>
                <h4>Shows</h4>
                <a href="#categories">Genres</a>
                <a href="#categories">Trending</a>
                <a href="#categories">New Releases</a>
                <a href="#categories">Popular</a>
            </div>
            <div>
                <h4>Support</h4>
                <a href="mailto:support@streamvibe.example">Contact Us</a>
            </div>
            <div>
                <h4>Subscription</h4>
                <a href="#plans">Plans</a>
                <a href="#plans">Features</a>
            </div>
            <div>
                <h4>Connect With Us</h4>
                <div class="socials">
                    <a href="#home" aria-label="Facebook">f</a>
                    <a href="#home" aria-label="Twitter">𝕏</a>
                    <a href="#home" aria-label="LinkedIn">in</a>
                </div>
            </div>
        </div>

        <div class="footer-bottom">
            <p>© 2026 StreamVibe. All Rights Reserved.</p>
            <div>
                <a href="#home">Terms of Use</a>
                <a href="#home">Privacy Policy</a>
                <a href="#home">Cookie Policy</a>
            </div>
        </div>
    </footer>

</body>
</html>








 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    background: #141414;
    color: #ffffff;
    font-family: 'Inter', Arial, sans-serif;
    line-height: 1.6;
    overflow-x: hidden;
}

a {
    color: inherit;
    text-decoration: none;
}

button {
    font: inherit;
    cursor: pointer;
}

p {
    color: #999999;
    font-size: 13px;
}

section {
    scroll-margin-top: 90px;
}


.header {
    width: min(1200px, 90%);
    margin: 0 auto;
    min-height: 76px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 24px;
    position: relative;
    z-index: 5;
}

.logo {
    font-size: 21px;
    font-weight: 700;
    white-space: nowrap;
}

.logo span {
    color: #e50000;
    font-size: 23px;
    margin-right: 5px;
}

.navbar {
    display: flex;
    align-items: center;
    gap: 5px;
    background: #0c0c0c;
    border: 1px solid #262626;
    border-radius: 10px;
    padding: 5px;
}

.navbar a {
    color: #b5b5b5;
    font-size: 12px;
    padding: 10px 15px;
    border-radius: 7px;
    transition: 0.25s ease;
}

.navbar a:hover,
.navbar a.active {
    color: #ffffff;
    background: #252525;
}

.header-icons {
    display: flex;
    gap: 18px;
    font-size: 24px;
}

.header-icons a:hover {
    color: #e50000;
}



.hero {
    min-height: 900px;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    padding: 0 5% 55px;
    isolation: isolate;
}

.poster-wall {
    position: absolute;
    z-index: -2;
    top: -76px;
    left: 0;
    width: 100%;
    height: 400px;
    display: grid;
    grid-template-columns: repeat(7, minmax(0, 1fr));
    grid-auto-rows: 135px;
    gap: 8px;
    overflow: hidden;
    opacity: 0.65;
    -webkit-mask-image: linear-gradient(
        to bottom, #000 0%, #000 48%, transparent 100%
    );
    mask-image: linear-gradient(
        to bottom, #000 0%, #000 48%, transparent 100%
    );
}

.poster-wall img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 5px;
    filter: brightness(0.62);
}

.hero::before {
    content: "";
    position: absolute;
    inset: -76px 0 0;
    z-index: -1;
    background: linear-gradient(
        to bottom,
        rgba(20, 20, 20, 0.12),
        rgba(20, 20, 20, 0.6) 45%,
        #141414 85%
    );
}

.hero-content {
    max-width: 780px;
    text-align: center;
    position: relative;
}

.play-mark {
    width: 125px;
    height: 125px;
    border: 14px solid rgba(255, 255, 255, 0.2);
    border-radius: 50%;
    display: grid;
    place-items: center;
    margin: 0 auto 24px;
    font-size: 39px;
    color: rgba(255, 255, 255, 0.6);
    background: rgba(255, 255, 255, 0.06);
}

.hero h1 {
    font-size: clamp(27px, 4vw, 42px);
    line-height: 1.25;
    margin-bottom: 12px;
    letter-spacing: -1px;
}

.hero p {
    max-width: 690px;
    margin: 0 auto 25px;
    line-height: 1.8;
}

.btn {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    gap: 7px;
    background: #e50000;
    color: #ffffff;
    padding: 12px 19px;
    border: 1px solid #e50000;
    border-radius: 5px;
    font-size: 12px;
    font-weight: 600;
    transition: background 0.2s, transform 0.2s;
}

.btn:hover {
    background: #bd0000;
    transform: translateY(-2px);
}



.section {
    width: min(1200px, 90%);
    margin: 0 auto;
    padding: 48px 0;
}

.section-heading {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 22px;
    margin-bottom: 28px;
}

.section-heading h2 {
    font-size: clamp(21px, 2.5vw, 28px);
    line-height: 1.4;
    margin-bottom: 7px;
}

.section-heading p {
    line-height: 1.7;
}

.arrows {
    display: flex;
    gap: 10px;
    padding: 8px;
    background: #0c0c0c;
    border: 1px solid #252525;
    border-radius: 8px;
    flex-shrink: 0;
}

.arrows button {
    width: 38px;
    height: 38px;
    color: white;
    background: #222222;
    border: 0;
    border-radius: 5px;
}

.arrows button:hover {
    background: #e50000;
}



.category-grid {
    display: grid;
    grid-template-columns: repeat(5, minmax(0, 1fr));
    gap: 18px;
}

.category-card {
    min-width: 0;
    background: #1c1c1c;
    border: 1px solid #252525;
    border-radius: 9px;
    padding: 14px;
    transition: border-color 0.25s, transform 0.25s;
}

.category-card:hover {
    border-color: #e50000;
    transform: translateY(-4px);
}

.category-card img {
    display: block;
    width: 100%;
    height: 155px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 12px;
}

.category-card span {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 13px;
    font-weight: 500;
}

.category-card b {
    font-size: 19px;
    font-weight: 400;
}



.device-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 18px;
}

.device-card {
    padding: 24px;
    min-height: 150px;
    background: linear-gradient(135deg, #1d1111, #111111 80%);
    border: 1px solid #252525;
    border-radius: 9px;
    transition: border-color 0.25s;
}

.device-card:hover {
    border-color: #555555;
}

.device-icon {
    width: 42px;
    height: 42px;
    display: grid;
    place-items: center;
    background: #242020;
    color: #e50000;
    border-radius: 8px;
    font-size: 24px;
    margin-bottom: 15px;
}

.device-card h3 {
    font-size: 16px;
    font-weight: 500;
    margin-bottom: 10px;
}

.device-card p {
    line-height: 1.7;
}



.faq-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 35px;
}

.faq-list details {
    border-bottom: 1px solid #292929;
    padding: 20px 0;
}

.faq-list summary {
    display: flex;
    align-items: center;
    gap: 13px;
    cursor: pointer;
    list-style: none;
    font-size: 13px;
    font-weight: 500;
}

.faq-list summary::-webkit-details-marker {
    display: none;
}

.faq-list summary::after {
    content: "+";
    margin-left: auto;
    font-size: 23px;
    font-weight: 300;
}

.faq-list details[open] summary::after {
    content: "−";
}

.faq-list summary span {
    display: grid;
    place-items: center;
    flex-shrink: 0;
    width: 38px;
    height: 38px;
    border-radius: 5px;
    background: #222222;
    font-size: 12px;
}

.faq-list details p {
    padding: 12px 0 0 51px;
    line-height: 1.8;
}


.billing {
    display: flex;
    gap: 5px;
    padding: 5px;
    background: #0c0c0c;
    border: 1px solid #252525;
    border-radius: 8px;
    flex-shrink: 0;
}

.billing button {
    padding: 10px 15px;
    border: 0;
    color: #aaaaaa;
    background: transparent;
    border-radius: 5px;
    font-size: 12px;
}

.billing button.selected,
.billing button:hover {
    color: #ffffff;
    background: #252525;
}

.pricing-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 18px;
}

.price-card {
    padding: 27px;
    background: #1a1a1a;
    border: 1px solid #252525;
    border-radius: 9px;
}

.price-card h3 {
    font-size: 16px;
    margin-bottom: 12px;
}

.price-card > p {
    min-height: 60px;
    line-height: 1.7;
}

.price {
    font-size: 32px;
    font-weight: 600;
    margin: 18px 0;
}

.price small {
    color: #888888;
    font-size: 12px;
    font-weight: 400;
}

.price-actions {
    display: flex;
    gap: 10px;
}

.price-actions .btn,
.price-actions .btn-secondary {
    flex: 1;
    text-align: center;
    padding: 11px 8px;
    font-size: 11px;
}

.btn-secondary {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #292929;
    background: #111111;
    color: #ffffff;
    border-radius: 5px;
    transition: background 0.2s;
}

.btn-secondary:hover {
    background: #292929;
}


.trial-banner {
    width: min(1200px, 90%);
    min-height: 210px;
    margin: 45px auto 90px;
    padding: 35px 45px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 25px;
    border: 1px solid #292929;
    border-radius: 10px;
    background:
        linear-gradient(90deg, #101010 15%, rgba(16, 16, 16, 0.75)),
        url("https://images.unsplash.com/photo-1489599849927-2ee91cede3ba?auto=format&fit=crop&w=1400&q=80")
        center / cover;
}

.trial-banner h2 {
    font-size: clamp(23px, 3vw, 34px);
    margin-bottom: 10px;
}

.trial-banner p {
    line-height: 1.8;
}



.footer {
    background: #0d0d0d;
    padding: 55px max(5%, calc((100% - 1200px) / 2)) 25px;
}

.footer-grid {
    display: grid;
    grid-template-columns: repeat(6, minmax(0, 1fr));
    gap: 28px;
    padding-bottom: 40px;
}

.footer-grid h4 {
    font-size: 13px;
    margin-bottom: 18px;
}

.footer-grid > div > a {
    display: block;
    width: fit-content;
    color: #999999;
    font-size: 12px;
    margin-bottom: 10px;
    transition: color 0.2s;
}

.footer-grid > div > a:hover,
.footer-bottom a:hover {
    color: #ffffff;
}

.socials {
    display: flex;
    gap: 8px;
}

.socials a {
    display: grid;
    place-items: center;
    width: 36px;
    height: 36px;
    background: #202020;
    border-radius: 6px;
    font-size: 13px;
    font-weight: 600;
}

.socials a:hover {
    background: #e50000;
}

.footer-bottom {
    padding-top: 23px;
    border-top: 1px solid #292929;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 18px;
}

.footer-bottom p,
.footer-bottom a {
    font-size: 11px;
}

.footer-bottom div {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.footer-bottom a {
    color: #999999;
}


@media (max-width: 900px) {
    .header {
        gap: 12px;
    }

    .logo {
        font-size: 17px;
    }

    .navbar a {
        padding: 9px;
        font-size: 11px;
    }

    .poster-wall {
        grid-template-columns: repeat(5, minmax(0, 1fr));
    }

    .category-grid {
        grid-template-columns: repeat(3, minmax(0, 1fr));
    }

    .category-card img {
        height: 170px;
    }

    .device-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }

    .footer-grid {
        grid-template-columns: repeat(3, minmax(0, 1fr));
    }

    .price-card {
        padding: 18px;
    }

    .price-actions {
        flex-direction: column;
    }
}



@media (max-width: 600px) {
    .header {
        width: 92%;
        min-height: auto;
        padding: 18px 0;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    .logo {
        font-size: 19px;
    }

    .header-icons {
        gap: 12px;
    }

    .navbar {
        width: 100%;
        order: 3;
        justify-content: center;
        flex-wrap: wrap;
    }

    .navbar a {
        padding: 9px 10px;
        font-size: 11px;
    }

    .hero {
        min-height: 470px;
        padding: 0 5% 42px;
    }

    .poster-wall {
        top: -130px;
        height: 380px;
        grid-template-columns: repeat(3, minmax(0, 1fr));
        grid-auto-rows: 115px;
        gap: 5px;
    }

    .hero::before {
        inset: -130px 0 0;
    }

    .play-mark {
        width: 85px;
        height: 85px;
        border-width: 9px;
        font-size: 28px;
        margin-bottom: 20px;
    }

    .hero h1 {
        font-size: 27px;
        letter-spacing: -0.5px;
    }

    .hero p {
        font-size: 12px;
        line-height: 1.8;
    }

    .section {
        width: 90%;
        padding: 34px 0;
    }

    .section-heading {
        align-items: flex-start;
        flex-direction: column;
        gap: 15px;
    }

    .section-heading h2 {
        font-size: 22px;
    }

    .section-heading p {
        font-size: 12px;
    }

    .category-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 12px;
    }

    .category-card {
        padding: 9px;
    }

    .category-card img {
        height: 135px;
    }

    .category-card span {
        font-size: 12px;
    }

    .device-grid {
        grid-template-columns: 1fr;
        gap: 12px;
    }

    .device-card {
        min-height: auto;
        padding: 20px;
    }

    .faq-grid {
        grid-template-columns: 1fr;
        gap: 0;
    }

    .faq-list summary {
        font-size: 12px;
    }

    .faq-list summary span {
        width: 34px;
        height: 34px;
    }

    .faq-list details p {
        padding-left: 47px;
    }

    .billing {
        align-self: flex-start;
    }

    .pricing-grid {
        grid-template-columns: 1fr;
        gap: 14px;
    }

    .price-card {
        padding: 24px;
    }

    .price-card > p {
        min-height: 0;
    }

    .price-actions {
        flex-direction: row;
    }

    .trial-banner {
        width: 90%;
        margin: 25px auto 55px;
        padding: 28px 22px;
        flex-direction: column;
        align-items: flex-start;
        background-position: center;
    }

    .trial-banner h2 {
        font-size: 25px;
    }

    .footer {
        padding: 38px 5% 20px;
    }

    .footer-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 28px 18px;
    }

    .footer-bottom {
        align-items: flex-start;
        flex-direction: column;
    }

    .footer-bottom div {
        gap: 13px;
    }
}



@media (max-width: 360px) {
    .navbar a {
        padding: 8px 6px;
        font-size: 10px;
    }

    .category-grid {
        grid-template-columns: 1fr;
    }

    .category-card img {
        height: 180px;
    }

    .price-actions {
        flex-direction: column;
    }

    .footer-grid {
        gap: 25px 12px;
    }
}


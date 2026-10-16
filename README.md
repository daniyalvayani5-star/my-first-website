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

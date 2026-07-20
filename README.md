<!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tuddav – Cafenea Bucureștii Noi</title>

<style>
    :root {
        --bg: #3b2a23;
        --bg-light: #4a3329;
        --accent: #c69c6d;
        --text: #f5e9dd;
        --white: #ffffff;
    }

    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
        font-family: "Segoe UI", Arial, sans-serif;
        background: radial-gradient(circle at top, #5a3b2b 0%, #2a1c16 45%, #1a120d 100%);
        color: var(--text);
    }

    header {
        padding: 20px;
        text-align: center;
        background: rgba(0,0,0,0.35);
        backdrop-filter: blur(6px);
        position: sticky;
        top: 0;
        z-index: 10;
    }

    header h1 {
        font-size: 28px;
        letter-spacing: 2px;
        text-transform: uppercase;
    }

    header p {
        font-size: 14px;
        color: #e0cbb0;
    }

    nav {
        margin-top: 10px;
    }

    nav a {
        color: var(--accent);
        text-decoration: none;
        margin: 0 10px;
        font-size: 14px;
    }

    nav a:hover {
        text-decoration: underline;
    }

    .hero {
        display: flex;
        flex-wrap: wrap;
        padding: 40px 10%;
        align-items: center;
        gap: 30px;
    }

    .hero-text {
        flex: 1 1 280px;
    }

    .hero-text h2 {
        font-size: 32px;
        margin-bottom: 15px;
    }

    .hero-text p {
        font-size: 16px;
        line-height: 1.6;
        color: #f0dfc7;
    }

    .hero-badge {
        margin-top: 15px;
        display: inline-block;
        padding: 8px 14px;
        border-radius: 999px;
        background: rgba(0,0,0,0.4);
        border: 1px solid var(--accent);
        font-size: 13px;
    }

    .hero-img {
        flex: 1 1 280px;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 10px;
    }

    .hero-img img {
        width: 100%;
        border-radius: 12px;
        object-fit: cover;
        height: 160px;
        border: 1px solid rgba(255,255,255,0.08);
    }

    section {
        padding: 30px 10%;
    }

    section h3 {
        font-size: 22px;
        margin-bottom: 15px;
        color: var(--accent);
    }

    .card {
        background: rgba(0,0,0,0.35);
        border-radius: 12px;
        padding: 20px;
        border: 1px solid rgba(255,255,255,0.06);
    }

    .about p {
        font-size: 15px;
        line-height: 1.7;
        color: #f3e3cf;
    }

    .grid-2 {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
        gap: 20px;
    }

    .menu-item {
        margin-bottom: 10px;
    }

    .menu-item span {
        display: flex;
        justify-content: space-between;
        font-size: 15px;
    }

    .menu-item small {
        font-size: 12px;
        color: #d7c3a7;
    }

    .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 15px;
    }

    .gallery img {
        width: 100%;
        border-radius: 10px;
        object-fit: cover;
        height: 180px;
        border: 1px solid rgba(255,255,255,0.08);
    }

    .contact-list {
        list-style: none;
        font-size: 15px;
    }

    .contact-list li {
        margin-bottom: 8px;
    }

    .contact-list b {
        color: var(--accent);
    }

    .map {
        margin-top: 15px;
        border-radius: 12px;
        overflow: hidden;
        border: 1px solid rgba(255,255,255,0.1);
    }

    .footer {
        text-align: center;
        padding: 20px;
        font-size: 12px;
        color: #cbb49a;
    }

    a.link {
        color: var(--accent);
        text-decoration: none;
    }

    a.link:hover {
        text-decoration: underline;
    }

    @media (max-width: 768px) {
        .hero {
            padding: 25px 6%;
        }
        section {
            padding: 25px 6%;
        }
    }
</style>
</head>
<body>

<header>
    <h1>Tuddav Coffee</h1>
    <p>Bulevardul Bucureștii Noi 25, 012352 – București</p>
    <nav>
        <a href="#reviewuri">Review-uri</a>
        <a href="#despre">Despre</a>
        <a href="#meniu">Meniu</a>
        <a href="#galerie">Galerie</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero">
    <div class="hero-text">
        <h2>Cafenea de cartier, cu suflet și espresso serios</h2>
        <p>
            Tuddav este locul unde îți bei cafeaua în liniște, cunoști oameni din zonă
            și îți iei energia pentru zi. Boabe atent alese, prăjire corectă, lapte bun
            și un vibe cald, maroniu, ca o dimineață de toamnă.
        </p>
        <div class="hero-badge">
            ⭐ Rating 4.9 · Cafenea de specialitate · Bucureștii Noi
        </div>
    </div>

    <div class="hero-img">
        <!-- Imagini de cafea (royalty-free) – le poți schimba oricând -->
        <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=600&q=80" alt="Cafea espresso">
        <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=600&q=80" alt="Latte art">
        <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=600&q=80" alt="Boabe de cafea">
        <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=600&q=80" alt="Cafea la bar">
    </div>
</div>

<section id="despre">
    <h3>Despre Tuddav</h3>
    <div class="card about">
        <p>
            Tuddav nu este doar o cafenea, este locul unde cartierul respiră. Aici se adună oameni care 
            fug de agitația orașului, oameni care vor doar o pauză, un moment pentru ei. Nu avem pretenții 
            de hipsteri sau de local fancy, suntem exact ce vezi: o cafenea mică, caldă, cu miros de boabe 
            proaspăt râșnite și cu povești care se nasc la fiecare masă. 
        </p>
        <p style="margin-top:10px;">
            Ne place să credem că fiecare client pleacă de aici un pic mai bine decât a venit. Poate din 
            cauza cafelei, poate din cauza atmosferei, poate din cauza unei discuții scurte cu barista. 
            Nu promitem experiențe revoluționare, promitem doar sinceritate, bun simț și o cafea făcută 
            cu grijă. Și uneori, asta e tot ce ai nevoie ca să-ți începi ziua cum trebuie.
        </p>
    </div>
</section>

<section id="meniu">
    <h3>Meniu complet</h3>
    <div class="card grid-2">

        <!-- CAFEA CLASICĂ -->
        <div>
            <div class="menu-item"><span><strong>Espresso</strong> <strong>10 lei</strong></span></div>
            <div class="menu-item"><span><strong>Doppio</strong> <strong>14 lei</strong></span></div>
            <div class="menu-item"><span><strong>Americano</strong> <strong>12 lei</strong></span></div>
            <div class="menu-item"><span><strong>Long Black</strong> <strong>12 lei</strong></span></div>
            <div class="menu-item"><span><strong>Macchiato</strong> <strong>12 lei</strong></span></div>
            <div class="menu-item"><span><strong>Cortado</strong> <strong>14 lei</strong></span></div>
        </div>

        <!-- CAFEA CU LAPTE -->
        <div>
            <div class="menu-item"><span><strong>Cappuccino</strong> <strong>15 lei</strong></span></div>
            <div class="menu-item"><span><strong>Flat White</strong> <strong>16 lei</strong></span></div>
            <div class="menu-item"><span><strong>Latte</strong> <strong>16 lei</strong></span></div>
            <div class="menu-item"><span><strong>Mocha</strong> <strong>18 lei</strong></span></div>
            <div class="menu-item"><span><strong>Latte Caramel</strong> <strong>18 lei</strong></span></div>
            <div class="menu-item"><span><strong>Latte Vanilie</strong> <strong>18 lei</strong></span></div>
        </div>

        <!-- SPECIALITĂȚI -->
        <div>
            <div class="menu-item"><span><strong>Cold Brew</strong> <strong>18 lei</strong></span></div>
            <div class="menu-item"><span><strong>Ice Latte</strong> <strong>18 lei</strong></span></div>
            <div class="menu-item"><span><strong>Affogato</strong> <strong>20 lei</strong></span></div>
            <div class="menu-item"><span><strong>Frappé</strong> <strong>18 lei</strong></span></div>
            <div class="menu-item"><span><strong>Matcha Latte</strong> <strong>20 lei</strong></span></div>
            <div class="menu-item"><span><strong>Chai Latte</strong> <strong>20 lei</strong></span></div>
        </div>

        <!-- BAUTURI FARA CAFEA -->
        <div>
            <div class="menu-item"><span><strong>Ciocolată caldă</strong> <strong>16 lei</strong></span></div>
            <div class="menu-item"><span><strong>Ceaiuri naturale</strong> <strong>12 lei</strong></span></div>
            <div class="menu-item"><span><strong>Limonadă</strong> <strong>14 lei</strong></span></div>
            <div class="menu-item"><span><strong>Fresh portocale</strong> <strong>16 lei</strong></span></div>
            <div class="menu-item"><span><strong>Apă plată / minerală</strong> <strong>8 lei</strong></span></div>
        </div>

        <!-- DESERTURI -->
        <div>
            <div class="menu-item"><span><strong>Cheesecake</strong> <strong>20 lei</strong></span></div>
            <div class="menu-item"><span><strong>Brownie</strong> <strong>18 lei</strong></span></div>
            <div class="menu-item"><span><strong>Tiramisu</strong> <strong>22 lei</strong></span></div>
            <div class="menu-item"><span><strong>Banana Bread</strong> <strong>16 lei</strong></span></div>
            <div class="menu-item"><span><strong>Cookie mare</strong> <strong>10 lei</strong></span></div>
        </div>

        <!-- LAPTE & EXTRA -->
        <div>
            <div class="menu-item"><span><strong>Laptele vegetal</strong> <strong>+3 lei</strong></span></div>
            <div class="menu-item"><span><strong>Shot espresso extra</strong> <strong>+4 lei</strong></span></div>
            <div class="menu-item"><span><strong>Arome (caramel, vanilie, ciocolată)</strong> <strong>+3 lei</strong></span></div>
        </div>

    </div>
</section>

<section id="galerie">
    <h3>Galerie foto</h3>
    <div class="card gallery">
        <!-- Poți înlocui imaginile cu poze făcute de tine -->
        <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=800&q=80" alt="Bar de cafea">
        <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=800&q=80" alt="Cafea și boabe">
        <img src="https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?auto=format&fit=crop&w=800&q=80" alt="Interior cozy">
        <img src="https://images.unsplash.com/photo-1517705008128-361805f42e86?auto=format&fit=crop&w=800&q=80" alt="Cafea to go">
    </div>
</section>

<section id="contact">
    <h3>Contact & program</h3>
    <div class="card">
        <ul class="contact-list">
            <li><b>Adresă:</b> Bulevardul Bucureștii Noi 25, 012352, bl. E, București</li>
            <li><b>Telefon:</b> <a class="link" href="tel:+40722582018">0722 582 018</a></li>
    
            <li><b>Instagram:</b> 
    <a class="link" href="https://www.instagram.com/tuddav.coffee.shop/?utm_source=ig_web_button_share_sheet" target="_blank">
        @tuddav.coffee.shop
    </a>
</li>

            <li><b>Program:</b> Luni–Duminică · 09:00 – 19:00</li>
        </ul>

        
    </div>
<section id="reviewuri">
    <h3>Review-uri</h3>
    <div class="card">

        <!-- Review-uri existente -->
        <div id="reviews-list">

            <div class="review">
                <p style="font-size:15px; line-height:1.6;">
                    ⭐⭐⭐⭐⭐  
                    „Cafeaua de la Tuddav e fix ce trebuie dimineața. Aromată, tare, dar fină. Atmosfera e liniștită și oamenii sunt super ok.”  
                    <br><b>– Andreea M.</b>
                </p>
            </div>

            <hr style="border:0; border-top:1px solid rgba(255,255,255,0.1); margin:15px 0;">

            <div class="review">
                <p style="font-size:15px; line-height:1.6;">
                    ⭐⭐⭐⭐⭐  
                    „Un loc mic, dar cu vibe de cartier premium. Barista e mereu atent, iar deserturile sunt surprinzător de bune.”  
                    <br><b>– Vlad C.</b>
                </p>
            </div>

            <hr style="border:0; border-top:1px solid rgba(255,255,255,0.1); margin:15px 0;">

            <div class="review">
                <p style="font-size:15px; line-height:1.6;">
                    ⭐⭐⭐⭐⭐  
                    „Tuddav e genul de loc unde vii o dată și apoi revii fără să-ți dai seama. Muzică bună, cafea excelentă, oameni calzi.”  
                    <br><b>– Ioana P.</b>
                </p>
            </div>

        </div>

        <!-- FORMULAR REVIEW -->
        <hr style="border:0; border-top:1px solid rgba(255,255,255,0.2); margin:20px 0;">

        <h4 style="color:#c69c6d; margin-bottom:10px;">Scrie un review</h4>

        <input id="review-name" type="text" placeholder="Numele tău" 
               style="width:100%; padding:10px; border-radius:8px; border:1px solid #c69c6d; margin-bottom:10px;">

        <textarea id="review-text" placeholder="Opinia ta..." 
                  style="width:100%; padding:10px; border-radius:8px; border:1px solid #c69c6d; height:100px;"></textarea>

        <button onclick="addReview()" 
                style="margin-top:10px; background:#c69c6d; color:#1a120d; padding:10px 15px; border:none; border-radius:8px; cursor:pointer;">
            Trimite review
        </button>

    </div>
</section>

<script>
function addReview() {
    let name = document.getElementById("review-name").value.trim();
    let text = document.getElementById("review-text").value.trim();

    if (!name || !text) {
        alert("Te rog completează numele și review-ul.");
        return;
    }

    let container = document.getElementById("reviews-list");

    let newReview = document.createElement("div");
    newReview.className = "review";
    newReview.innerHTML = `
        <p style="font-size:15px; line-height:1.6;">
            ⭐⭐⭐⭐⭐  
            „${text}”  
            <br><b>– ${name}</b>
        </p>
    `;

    // Adaugă review-ul nou la începutul listei
    container.insertBefore(newReview, container.firstChild);

    // Linie de separare
    let hr = document.createElement("hr");
    hr.style = "border:0; border-top:1px solid rgba(255,255,255,0.1); margin:15px 0;";
    container.insertBefore(hr, newReview.nextSibling);

    // Curăță formularul
    document.getElementById("review-name").value = "";
    document.getElementById("review-text").value = "";

    alert("Review adăugat cu succes!");
}
</script>

</body>
</html>

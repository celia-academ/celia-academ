<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>أكاديمية سيليا لتعليم اللغة الإنجليزية</title>

<style>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    color: #222;
    background: url('background.jpg') no-repeat center center fixed;
    background-size: cover;
}

body::before {
    content: "";
    position: fixed;
    inset: 0;
    background: rgba(255,255,255,0.6);
    z-index: -1;
}

header {
    position: relative;
    background: url('header-bg.jpg') no-repeat center center;
    background-size: cover;
    color: #fff;
    padding: 35px 20px;
    text-align: center;
}

header::before {
    content: "";
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.35);
    z-index: -1;
}

.header-top-image {
    position: absolute;
    top: 10px;
    left: 10px;
    width: 150px;
}

header img.logo {
    width: 200px;
    display: block;
    margin: 0 auto 10px;
}

/* ===== النص المميز ===== */
.director-title {
    margin-top: 12px;
    font-size: 1.05em;
    letter-spacing: 1px;
    color: #eaeaea;
    text-transform: uppercase;
}

.director-title span {
    display: inline-block;
    margin-top: 6px;
    font-size: 1.35em;
    font-weight: bold;
    color: #FFD700;
    padding-bottom: 4px;
    border-bottom: 2px solid #FFD700;
}
/* ====================== */

header h1 {
    margin-top: 15px;
    font-size: 2em;
}

header p.desc {
    margin-top: 10px;
    font-size: 1.1em;
    color: #e0f7ff;
}

.main-container {
    display: flex;
    flex-wrap: wrap;
    max-width: 1400px;
    margin: auto;
    padding: 20px;
}

.content {
    flex: 2;
    padding: 20px;
}

.sidebar {
    flex: 1;
    padding: 20px;
    background: rgba(255,255,255,0.3);
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    height: fit-content;
    position: sticky;
    top: 20px;
}

.sidebar-left { text-align: left; margin-right: 20px; }
.sidebar-right { text-align: right; margin-left: 20px; }

.sidebar ul {
    list-style: none;
    padding: 0;
}

.sidebar li {
    margin: 10px 0;
    font-weight: bold;
}

section {
    margin-bottom: 40px;
}

h2 {
    text-align: center;
    margin-bottom: 20px;
}

.card {
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    padding: 20px;
    text-align: center;
    max-width: 500px;
    margin: auto;
    border: 3px solid black;
}

.card img {
    width: 100%;
    border-radius: 10px;
}

#contact p {
    color: green;
    font-weight: bold;
}

.whatsapp-btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background: #25D366;
    color: #fff;
    text-decoration: none;
    border-radius: 8px;
}

footer {
    background: #4facfe;
    color: #fff;
    text-align: center;
    padding: 20px;
}

@media(max-width:1024px){
    .main-container { flex-direction: column; }
    .sidebar { position: relative; top: 0; margin-bottom: 20px; }
}

@media(max-width:768px){
    header img.logo { width: 150px; }
    .director-title span { font-size: 1.2em; }
}
</style>
</head>

<body>

<header>
    <img src="top-image.png" class="header-top-image">
    <img src="logo.png" class="logo">

    <p class="director-title">
        Director of Celia Academy<br>
        <span>Mr. Mohamed Tarek Mohammed</span>
    </p>

    <h1>أكاديمية سيليا لتعليم اللغة الإنجليزية</h1>
    <p class="desc">
        نساعد الطلاب على إتقان المحادثة، النطق، والقواعد باستخدام أفضل المناهج الدولية
    </p>
</header>

<div class="main-container">

    <aside class="sidebar sidebar-left">
        <h3>About Celia Academy</h3>
        <p>
            Celia Academy empowers students to master English conversation,
            pronunciation, and grammar confidently.
        </p>
    </aside>

    <div class="content">

        <section>
            <h2>الكورس الشامل</h2>
            <div class="card">
                <img src="course.jpg">
                <h3>محادثة - فونكس - جرامر</h3>
                <p>كورس متكامل لكل المستويات</p>
            </div>
        </section>

        <section>
            <h2>تواصل معنا</h2>
            <div class="card" id="contact">
                <p>+2012 02328529</p>
                <p>+2012 02325029</p>
                <a class="whatsapp-btn" href="https://wa.me/201202328529">احجز عبر واتساب</a>
            </div>
        </section>

    </div>

    <aside class="sidebar sidebar-right">
        <h3>عن أكاديمية سيليا</h3>
        <p>
            أكاديمية سيليا هي وجهتك لإتقان اللغة الإنجليزية بثقة.
        </p>
    </aside>

</div>

<footer>
    جميع الحقوق محفوظة © 2025 أكاديمية سيليا
</footer>

</body>
</html>


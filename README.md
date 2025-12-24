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
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(255, 255, 255, 0.6);
        z-index: -1;
    }

    header {
        position: relative;
        background: url('header-bg.jpg') no-repeat center center;
        background-size: cover;
        color: #fff;
        padding: 30px 20px;
        text-align: center;
    }

    header::before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0,0,0,0.3);
        z-index: -1;
    }

    .header-top-image {
        position: absolute;
        top: 10px;
        left: 10px;
        width: 150px;
        z-index: 2;
    }

    header img.logo {
        width: 200px;
        display: block;
        margin: 0 auto 10px;
    }

    header h1 {
        margin: 0;
        font-size: 2em;
    }

    /* اسم المدير */
    .owner-name {
        margin-top: 8px;
        font-size: 1em;
        color: #ffd700;
        font-weight: bold;
    }

    header p {
        margin-top: 10px;
        font-size: 1.1em;
        color: #e0f7ff;
    }

    .main-container {
        display: flex;
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
        position: sticky;
        top: 20px;
        height: fit-content;
    }

    .sidebar-right {
        text-align: right;
        margin-left: 20px;
    }

    .sidebar-left {
        text-align: left;
        margin-right: 20px;
    }

    section {
        margin-bottom: 40px;
    }

    .card {
        background: #fff;
        border-radius: 12px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        padding: 20px;
        max-width: 500px;
        margin: 20px auto;
        text-align: center;
        border: 3px solid black;
    }

    .card img {
        width: 100%;
        border-radius: 10px;
    }

    footer {
        background: #4facfe;
        color: #fff;
        text-align: center;
        padding: 20px;
    }

    @media (max-width: 1024px) {
        .main-container {
            flex-direction: column;
        }
        .sidebar {
            position: relative;
            top: 0;
            margin-bottom: 20px;
        }
    }
</style>
</head>

<body>

<header>
    <img src="top-image.png" class="header-top-image" alt="">
    <img src="logo.png" class="logo" alt="Celia Academy Logo">

    <h1>أكاديمية سيليا لتعليم اللغة الإنجليزية</h1>

    <!-- اسم المدير -->
    <p class="owner-name">Academy Director: Mr. Mohammad Tarek</p>

    <p>
        أكاديمية سيليا لتعليم اللغة الإنجليزية - نساعد الطلاب على إتقان المحادثة،
        النطق، والقواعد باستخدام أفضل المناهج الدولية.
    </p>
</header>

<div class="main-container">

    <aside class="sidebar sidebar-left">
        <h3>About Celia Academy</h3>
        <p>
            Celia Academy for English empowers students to master conversation,
            pronunciation, and grammar with confidence.
        </p>
    </aside>

    <div class="content">
        <section>
            <div class="card">
                <h3>Comprehensive English Courses</h3>
                <p>Conversation – Phonics – Grammar</p>
            </div>
        </section>
    </div>

    <aside class="sidebar sidebar-right">
        <h3>عن أكاديمية سيليا</h3>
        <p>
            أكاديمية متخصصة في تعليم اللغة الإنجليزية بأسلوب حديث ومناهج معتمدة.
        </p>
    </aside>

</div>

<footer>
    جميع الحقوق محفوظة © 2025 أكاديمية سيليا
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>أكاديمية سيليا لتعليم اللغة الإنجليزية</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
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
    background: url('header-bg.jpg') no-repeat center center;
    background-size: cover;
    text-align: center;
    padding: 40px 20px;
    color: white;
    position: relative;
}

header::before {
    content: "";
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.35);
    z-index: -1;
}

header img.logo {
    width: 200px;
}

/* ===== مدير الأكاديمية ===== */
.director-title {
    margin-top: 12px;
    font-size: 1.05em;
    color: #eee;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.director-title span {
    display: inline-block;
    margin-top: 6px;
    font-size: 1.35em;
    font-weight: bold;
    color: gold;
    border-bottom: 2px solid gold;
}
/* ========================== */

header h1 {
    margin-top: 18px;
}

header p.desc {
    color: #e0f7ff;
}

.main-container {
    display: flex;
    max-width: 1400px;
    margin: auto;
    padding: 20px;
    flex-wrap: wrap;
}

.sidebar {
    flex: 1;
    padding: 20px;
    background: rgba(255,255,255,0.3);
    border-radius: 12px;
}

.sidebar-left { text-align: left; margin-right: 20px; }
.sidebar-right { text-align: right; margin-left: 20px; }

.content {
    flex: 2;
    padding: 20px;
}

section {
    margin-bottom: 40px;
}

h2 {
    text-align: center;
}

.card {
    background: white;
    border-radius: 12px;
    padding: 20px;
    max-width: 500px;
    margin: auto;
    text-align: center;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    border: 3px solid black;
}

.card img {
    width: 100%;
    border-radius: 10px;
}

/* ===== نموذج الحجز ===== */
form label {
    display: block;
    margin-top: 10px;
    font-weight: bold;
    text-align: right;
}

input, select, textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border-radius: 8px;
    border: 1px solid #ccc;
}

button.submit-btn {
    margin-top: 15px;
    background: #25D366;
    color: white;
    border: none;
    padding: 12px 20px;
    font-size: 1em;
    font-weight: bold;
    border-radius: 8px;
    cursor: pointer;
}

button.submit-btn:hover {
    background: #128C7E;
}
/* ======================== */

.whatsapp-btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background: #25D366;
    color: white;
    text-decoration: none;
    border-radius: 8px;
}

footer {
    background: #4facfe;
    color: white;
    text-align: center;
    padding: 20px;
}

@media(max-width:1024px) {
    .main-container {
        flex-direction: column;
    }
    .sidebar {
        margin-bottom: 20px;
    }
}
</style>
</head>

<body>

<header>
    <img src="logo.png" class="logo" alt="Celia Academy Logo">

    <p class="director-title">
        Director of Celia Academy<br>
        <span>Mr. Mohamed Tarek</span>
    </p>

    <h1>أكاديمية سيليا لتعليم اللغة الإنجليزية</h1>
    <p class="desc">نساعد الطلاب على إتقان المحادثة والنطق والقواعد بأفضل المناهج</p>
</header>

<div class="main-container">

    <!-- يسار -->
    <aside class="sidebar sidebar-left">
        <h3>About Celia Academy</h3>
        <p>Professional English courses for all levels with certified teachers.</p>
    </aside>

    <!-- المحتوى -->
    <div class="content">

        <section>
            <h2>الكورس الشامل</h2>
            <div class="card">
                <img src="course.jpg">
                <h3>محادثة – فونكس – جرامر</h3>
                <p>برنامج متكامل لجميع المستويات</p>
            </div>
        </section>

        <!-- نموذج الحجز -->
        <section id="booking">
            <h2>نموذج حجز الطالب</h2>
            <div class="card">
                <form id="bookingForm">
                    <label>اسم الطالب</label>
                    <input type="text" id="name" required>

                    <label>رقم الهاتف</label>
                    <input type="tel" id="phone" required>

                    <label>المستوى</label>
                    <select id="level" required>
                        <option value="">اختر</option>
                        <option>مبتدئ</option>
                        <option>متوسط</option>
                        <option>متقدم</option>
                    </select>

                    <label>المنهج</label>
                    <select id="curriculum" required>
                        <option value="">اختر</option>
                        <option>المنهج المصري</option>
                        <option>المنهج السعودي</option>
                        <option>المنهج القطري</option>
                        <option>المنهج الإماراتي</option>
                    </select>

                    <label>ملاحظات</label>
                    <textarea id="notes" rows="4"></textarea>

                    <button type="submit" class="submit-btn">
                        إرسال الحجز عبر واتساب
                    </button>
                </form>
            </div>
        </section>

        <section>
            <h2>تواصل معنا</h2>
            <div class="card">
                <p style="color:green;font-weight:bold;">+2012 02328529</p>
                <a class="whatsapp-btn" href="https://wa.me/201202328529" target="_blank">
                    احجز عبر واتساب
                </a>
            </div>
        </section>

    </div>

    <!-- يمين -->
    <aside class="sidebar sidebar-right">
        <h3>عن الأكاديمية</h3>
        <p>نوفر بيئة تعليمية احترافية لبناء الثقة والطلاقة في اللغة الإنجليزية.</p>
    </aside>

</div>

<footer>
    جميع الحقوق محفوظة © 2025 أكاديمية سيليا
</footer>

<script>
document.getElementById("bookingForm").addEventListener("submit", function(e){
    e.preventDefault();

    const name = document.getElementById("name").value;
    const phone = document.getElementById("phone").value;
    const level = document.getElementById("level").value;
    const curriculum = document.getElementById("curriculum").value;
    const notes = document.getElementById("notes").value;

    const text =
`حجز طالب جديد:
الاسم: ${name}
الهاتف: ${phone}
المستوى: ${level}
المنهج: ${curriculum}
ملاحظات: ${notes}`;

    const url = "https://wa.me/201202328529?text=" + encodeURIComponent(text);
    window.open(url, "_blank");
});
</script>

</body>
</html>

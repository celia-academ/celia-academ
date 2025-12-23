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
    padding: 30px 20px;
    text-align: center;
}

header::before {
    content: "";
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.3);
    z-index: -1;
}

header img.logo {
    width: 200px;
    margin: 0 auto 10px;
    display: block;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

header p {
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

.content { flex: 2; padding: 20px; }

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

.sidebar-right { text-align: right; margin-left: 20px; }
.sidebar-left { text-align: left; margin-right: 20px; }

.sidebar ul {
    list-style: none;
    padding: 0;
}

.sidebar li {
    margin: 10px 0;
    font-weight: bold;
}

section { margin-bottom: 40px; }

h2 {
    text-align: center;
    margin-bottom: 20px;
    color: black;
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
    margin-bottom: 15px;
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
    font-weight: bold;
    text-decoration: none;
    border-radius: 8px;
}

input, select, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border-radius: 8px;
    border: 1px solid #ccc;
}

button.submit-btn {
    background: #25D366;
    color: #fff;
    padding: 12px 25px;
    border: none;
    border-radius: 8px;
    font-weight: bold;
    cursor: pointer;
}

button.submit-btn:hover {
    background: #128C7E;
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
</style>
</head>

<body>

<header>
    <img src="logo.png" alt="لوجو أكاديمية سيليا" class="logo">
    <h1>أكاديمية سيليا لتعليم اللغة الإنجليزية</h1>
    <p>نساعد الطلاب على إتقان المحادثة، النطق، والقواعد باستخدام أفضل المناهج الدولية</p>
</header>

<div class="main-container">

<aside class="sidebar sidebar-left">
    <h3>About Celia Academy</h3>
    <p>Celia Academy helps students master English confidently for study and work.</p>
</aside>

<div class="content">

<section id="course">
    <h2>الكورس الشامل</h2>
    <div class="card">
        <img src="course.jpg">
        <h3>محادثة – فونكس – جرامر</h3>
        <p>كورس متكامل لجميع المستويات</p>
    </div>
</section>

<section id="booking">
    <h2>نموذج حجز للطالب</h2>
    <div class="card">
        <form id="booking-form">
            <label>الاسم الكامل</label>
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

            <label>هل يحتاج تأسيس؟</label>
            <select id="foundation" required>
                <option value="">اختر</option>
                <option>نعم</option>
                <option>لا</option>
            </select>

            <label>ملاحظات</label>
            <textarea id="message" rows="4"></textarea>

            <button type="submit" class="submit-btn">
                إرسال الحجز عبر واتساب
            </button>
        </form>
    </div>
</section>

<section id="contact">
    <h2>تواصل معنا</h2>
    <div class="card">
        <p>+2012 02328529</p>
        <a class="whatsapp-btn" href="https://wa.me/201202328529" target="_blank">
            احجز عبر واتساب
        </a>
    </div>
</section>

</div>

<aside class="sidebar sidebar-right">
    <h3>عن أكاديمية سيليا</h3>
    <p>نوفر بيئة تعليمية احترافية لبناء الثقة والطلاقة في اللغة الإنجليزية.</p>
</aside>

</div>

<footer>
    جميع الحقوق محفوظة © 2025 أكاديمية سيليا
</footer>

<script>
document.getElementById("booking-form").addEventListener("submit", function(e){
    e.preventDefault();

    const text =
`حجز طالب جديد
الاسم: ${name.value}
الهاتف: ${phone.value}
المستوى: ${level.value}
المنهج: ${curriculum.value}
تأسيس: ${foundation.value}
ملاحظات: ${message.value}`;

    const url = "https://wa.me/201202328529?text=" + encodeURIComponent(text);
    window.open(url, "_blank");
});
</script>

</body>
</html>

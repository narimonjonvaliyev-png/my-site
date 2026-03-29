<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abduraxmonning sayti</title>

<style>
body {
    margin:0;
    font-family:Arial;
    background:#111;
    color:white;
    text-align:center;
}

/* ANIMATSIYA */
.fade {
    opacity:0;
    transform:translateY(20px);
    animation:fadeIn 1s forwards;
}
@keyframes fadeIn {
    to {
        opacity:1;
        transform:translateY(0);
    }
}

/* CARD */
.card {
    background:#1e1e1e;
    padding:20px;
    margin:20px;
    border-radius:20px;
    box-shadow:0 5px 20px rgba(0,0,0,0.5);
}

/* BUTTON */
.btn {
    padding:12px 25px;
    border:none;
    border-radius:10px;
    background:green;
    color:white;
    font-size:16px;
    transition:0.2s;
}
.btn:active {
    background:darkgreen;
    transform:scale(0.9);
}
</style>

</head>

<body>

<!-- HEADER -->
<div style="background:#222; padding:20px;">
    <h1>Abduraxmonning sayti 😎</h1>
</div>

<!-- CONTENT -->
<div class="card fade">

    <h2>Men web saytlar yarataman 💻</h2>
    <p>Tez, arzon va sifatli saytlar tayyorlayman 🔥</p>

    <a href="https://t.me/USERNAME?text=Salom%20men%20sayt%20buyurtma%20qilmoqchiman">
        <button class="btn">Buyurtma berish 💬</button>
    </a>

</div>

<!-- FOOTER -->
<div style="background:#222; padding:10px;">
    <p>© 2026 Abduraxmon</p>
</div>

</body>
</html>

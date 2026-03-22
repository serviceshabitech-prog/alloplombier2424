<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>AlloPlombier 2424</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

/* HEADER */
.header {
    background: linear-gradient(90deg, #0a2a4a, #0077cc);
    color: white;
    padding: 15px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

/* LOGO */
.logo {
    display: flex;
    align-items: center;
    gap: 10px;
}

.logo svg {
    width: 50px;
}

/* TEXTE LOGO */
.logo-text {
    font-weight: bold;
    font-size: 20px;
}

/* TELEPHONE */
.phone {
    font-size: 20px;
    font-weight: bold;
}

/* BOUTON */
.call-btn {
    background: #ff6600;
    color: white;
    padding: 10px 15px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.call-btn:hover {
    background: #e65c00;
}

/* RESPONSIVE */
@media (max-width: 600px) {
    .header {
        flex-direction: column;
        gap: 10px;
    }
}
</style>

</head>

<body>

<header class="header">

    <!-- LOGO -->
    <div class="logo">
        <svg viewBox="0 0 100 100">
            <path d="M50 10 C35 35, 25 50, 50 80 C75 50, 65 35, 50 10 Z" fill="#00aaff"/>
        </svg>
        <div class="logo-text">ALLOPLOMBIER 2424</div>
    </div>

    <!-- TELEPHONE -->
    <div class="phone">
        📞 07 00 00 00 00
    </div>

    <!-- BOUTON -->
    <a href="tel:0700000000" class="call-btn">
        Appeler maintenant
    </a>

</header>

</body>
</html>

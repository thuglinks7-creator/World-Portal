# World-Portal
Your gateway to everything <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>World Portal</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: radial-gradient(circle at top, #0b0f2a, #000);
    color: white;
}

/* HEADER */
header {
    text-align: center;
    padding: 40px 20px;
}

header h1 {
    font-size: 40px;
    color: #00f7ff;
    text-shadow: 0 0 20px #00f7ff;
}

header p {
    color: #aaa;
}

/* SEARCH BAR */
.search-box {
    text-align: center;
    margin: 20px;
}

.search-box input {
    width: 70%;
    padding: 15px;
    border-radius: 25px;
    border: none;
    outline: none;
    font-size: 16px;
}

/* GRID */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 20px;
    padding: 30px;
}

.card {
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(0,247,255,0.2);
    padding: 25px;
    border-radius: 15px;
    text-align: center;
    cursor: pointer;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px #00f7ff;
}

.card h3 {
    color: #00f7ff;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    color: #555;
    font-size: 12px;
}
</style>

</head>

<body>

<header>
    <h1>WORLD PORTAL</h1>
    <p>Your Gateway to Everything</p>
</header>

<div class="search-box">
    <input type="text" placeholder="Search the portal...">
</div>

<div class="grid">

    <div class="card" onclick="alert('Opening Store...')">
        <h3>🛒 Store</h3>
        <p>Buy digital products</p>
    </div>

    <div class="card" onclick="alert('Opening Links...')">
        <h3>🔗 Links</h3>
        <p>All your websites</p>
    </div>

    <div class="card" onclick="alert('Opening Music...')">
        <h3>🎧 Music</h3>
        <p>Listen & upload</p>
    </div>

    <div class="card" onclick="alert('Opening Creator Hub...')">
        <h3>⚡ Creator Hub</h3>
        <p>Earn & upload content</p>
    </div>

    <div class="card" onclick="alert('Opening Digital Vault...')">
        <h3>🔐 Vault</h3>
        <p>Save your files</p>
    </div>

    <div class="card" onclick="alert('Opening Marketplace...')">
        <h3>🌍 Marketplace</h3>
        <p>Global buying & selling</p>
    </div>

</div>

<footer>
    World Portal © 2026 — Built by Derron moodie
</footer>

</body>
</html>

/* Estilos generales */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #1a1a1a;
    color: #ffffff;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
}

.hero {
    background-image: url('lux-bg.jpg');
    background-size: cover;
    background-position: center;
    height: 60vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #ffffff;
}

.hero-text {
    background-color: rgba(0, 0, 0, 0.5);
    padding: 20px;
    border-radius: 5px;
}

.btn {
    background-color: #ffcc00;
    color: #000000;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 40px;
}

.services {
    background-color: #ffffff;
    display: flex;
    justify-content: space-around;
}

.service-box {
    width: 30%;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.about, .contact {
    background-color: #f9f9f9;
    text-align: center;
}

footer {
    background-color: #1a1a1a;
    color: #ffffff;
    text-align: center;
    padding: 10px 0;
}

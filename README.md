html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>¡Feliz Cumpleaños, Soldado!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: url('https://wallpaperaccess.com/full/2005554.jpg') no-repeat center center fixed;
      background-size: cover;
      font-family: 'Arial Black', sans-serif;
      color: #FFD700;
      text-align: center;
      overflow: hidden;
      position: relative;
    }

    h1 {
      font-size: 60px;
      margin-top: 15%;
      text-shadow: 2px 2px 10px #000;
      display: inline-block;
    }

    .wave span {
      display: inline-block;
      animation: wave 1.5s infinite;
    }

    .wave span:nth-child(odd) {
      animation-delay: 0.1s;
    }

    .wave span:nth-child(even) {
      animation-delay: 0.2s;
    }

    @keyframes wave {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }

    p {
      font-size: 24px;
      text-shadow: 1px 1px 5px #000;
      margin-top: 20px;
      animation: fadeIn 2s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    /* Luces */
    .light {

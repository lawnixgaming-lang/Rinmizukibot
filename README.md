<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RinMizuki Bot - Multi-Purpose Discord Bot</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
  /* Reset */
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Roboto', sans-serif;
    background: #0d0d1a;
    color: #fff;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    min-height: 100vh;
    text-align: center;
  }

  header {
    width: 100%;
    text-align: center;
    padding: 5vw 5%;
    background: linear-gradient(135deg, #6e0dd0, #ff6b81);
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
  }
  header h1 {
    font-size: clamp(1.8rem, 5vw, 3rem);
    text-shadow: 0 0 10px #fff;
    word-break: break-word;
  }
  header p {
    font-size: clamp(1rem, 3vw, 1.3rem);
    color: #f0e6ff;
    text-shadow: 0 0 10px #ff6b81;
    margin-top: 0.5em;
  }

  .container {
    width: 100%;
    max-width: 1000px;
    padding: 5vw 5%;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 5vw;
    text-align: center;
  }

  .profile img {
    width: 100%;
    max-width: 250px;
    border-radius: 20px;
    box-shadow: 0 0 20px #ff6b81, 0 0 40px #6e0dd0;
    transition: transform 0.3s;
  }
  .profile img:hover {
    transform: scale(1.05);
  }

  .section {
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
  }
  .section h2 {
    font-size: clamp(1.5rem, 4vw, 2.2rem);
    color: #ff6b81;
    margin-bottom: 15px;
    text-shadow: 0 0 10px #ff6b81;
  }
  .section p, .section ul {
    font-size: clamp(0.95rem, 3vw, 1.1rem);
    line-height: 1.6;
    color: #ddd;
    margin: 0 auto 1em auto;
  }
  ul {
    padding-left: 20px;
    text-align: left;
  }
  ul li {
    margin-bottom: 8px;
  }

  .neon-btn {
    display: inline-block;
    padding: clamp(12px, 3vw, 18px) clamp(25px, 5vw, 35px);
    font-size: clamp(1rem, 3vw, 1.2em);
    font-weight: bold;
    color: #fff;
    text-decoration: none;
    border-radius: 12px;
    background: linear-gradient(45deg, #6e0dd0, #ff6b81, #ff6b81, #6e0dd0);
    background-size: 400% 400%;
    box-shadow: 0 0 10px #ff6b81, 0 0 20px #6e0dd0, 0 0 30px #ff6b81, 0 0 40px #6e0dd0;
    animation: neon 6s ease infinite;
    transition: 0.3s;
    margin-top: 20px;
    word-break: break-word;
    max-width: 300px;
    width: 100%;
  }
  .neon-btn:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px #ff6b81, 0 0 40px #6e0dd0, 0 0 60px #ff6b81, 0 0 80px #6e0dd0;
  }
  @keyframes neon {
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
  }

  footer {
    width: 100%;
    background-color: #1a1a2f;
    text-align: center;
    padding: 20px 5%;
    color: #999;
    font-size: clamp(0.8rem, 2vw, 1rem);
    word-break: break-word;
    margin-top: auto;
  }

  @media (max-width: 768px) {
    .container { padding: 5vw 3%; }
    .section h2 { font-size: clamp(1.4rem, 5vw, 2rem); }
    .section p, .section ul { font-size: 1rem; }
  }

  @media (max-width: 480px) {
    header { padding: 8vw 5%; }
    .section h2 { font-size: 1.5rem; }
    .neon-btn { width: 100%; text-align: center; max-width: 100%; }
  }
</style>
</head>
<body>

<header>
  <h1>RinMizuki Bot</h1>
  <p>Multi-Purpose Discord Bot for Your Server</p>
</header>

<div class="container">

  <div class="profile">
    <img src="https://raw.githubusercontent.com/laynH/Anime-Girls-Holding-Programming-Books/master/C%2B%2B/Sakura_Nene_CPP.jpg" alt="RinMizuki Bot Profile">
  </div>

  <div class="section">
    <h2>About RinMizuki Bot</h2>
    <p>RinMizuki is a versatile, multi-purpose Discord bot designed to enhance your server experience. From moderation to fun commands, music, and utility features, RinMizuki keeps your server lively and secure.</p>
  </div>

  <div class="section">
    <h2>Features</h2>
    <ul>
      <li>Moderation commands to keep your server organized.</li>
      <li>Fun games and interactive commands for members.</li>
      <li>Music commands to play your favorite songs.</li>
      <li>Utilities like reminders, polls, and server stats.</li>
      <li>Customizable settings for server admins.</li>
    </ul>
  </div>

  <div class="section">
    <h2>Invite RinMizuki Bot</h2>
    <p>Click the button below to add RinMizuki Bot to your server. Make sure you are logged into Discord and have “Manage Server” permissions.</p>
    <a href="https://discord.com/oauth2/authorize?client_id=726023020203737110&permissions=8&integration_type=0&scope=bot+applications.commands" class="neon-btn" target="_blank">Add RinMizuki Bot</a>
  </div>

</div>

<footer>
  &copy; 2025 RinMizuki Bot. All rights reserved.
</footer>

</body>
</html>

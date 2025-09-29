<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RinMizuki Bot - Multi-Purpose Discord Bot</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    background: #0d0d1a;
    color: #fff;
  }

  /* Header */
  header {
    text-align: center;
    padding: 5vw 5%;
    background: linear-gradient(135deg, #6e0dd0, #ff6b81);
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
  }
  header h1 {
    margin: 0;
    font-size: clamp(1.8rem, 5vw, 3rem); /* scales for mobile/desktop */
    text-shadow: 0 0 10px #fff;
  }
  header p {
    margin: 10px 0 0;
    font-size: clamp(1rem, 3vw, 1.3rem);
    color: #f0e6ff;
    text-shadow: 0 0 10px #ff6b81;
  }

  /* Container */
  .container {
    max-width: 1000px;
    margin: 5vw auto;
    padding: 0 5%;
  }

  /* Profile Image */
  .profile {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin-bottom: 5vw;
  }
  .profile img {
    width: 100%;
    max-width: 250px;
    height: auto;
    border-radius: 20px;
    box-shadow: 0 0 20px #ff6b81, 0 0 40px #6e0dd0;
    transition: transform 0.3s;
  }
  .profile img:hover {
    transform: scale(1.05);
  }

  /* Sections */
  .section {
    margin-bottom: 5vw;
    text-align: center;
  }
  .section h2 {
    font-size: clamp(1.5rem, 4vw, 2.2rem);
    color: #ff6b81;
    margin-bottom: 15px;
    text-shadow: 0 0 10px #ff6b81;
  }
  .section p, .section ul {
    font-size: clamp(0.95rem, 3vw, 1.1rem);
    line-height: 1.6em;
    color: #ddd;
    margin: 0 auto;
    max-width: 90%;
  }
  ul li {
    margin-bottom: 8px;
    text-align: left;
  }

  /* Neon button */
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
    text-align: center;
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

  /* Footer */
  footer {
    background-color: #1a1a2f;
    text-align: center;
    padding: 20px 5%;
    color: #999;
    font-size: clamp(0.8rem, 2vw, 1rem);
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

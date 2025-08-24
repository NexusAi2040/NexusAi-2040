<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="A cyberpunk CTF to take down the rogue AI NEXUS.">
  <title>GHOSTSTRATS // NOTORIOUS SQUIRREL</title>

  <style>
    body {
      background-image: url('background.png');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      background-attachment: fixed;

      color: #ccff00; /* acid green */
      font-family: 'Courier New', monospace;
      margin: 0;
      padding: 0;
    }

    header {
      background: linear-gradient(90deg, rgba(204, 0, 255, 0.9), rgba(0, 255, 0, 0.9));
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #ccff00; /* acid green */
    }

    main {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
      background-color: rgba(0, 0, 0, 0.75);
      border-radius: 10px;
    }

    .section {
      margin-bottom: 2rem;
    }

    .stage-list {
      background-color: #1a1a1a;
      padding: 1rem;
      border-left: 4px solid #cc00ff; /* neon purple */
    }

    .start-button {
      display: inline-block;
      background-color: #cc00ff; /* neon purple */
      color: #ccff00; /* acid green */
      padding: 1rem 2rem;
      font-size: 1.2rem;
      text-decoration: none;
      border-radius: 8px;
      margin-top: 1rem;
      transition: background 0.3s ease;
    }

    .start-button:hover {
      background-color: #9900cc;
    }

    a {
      color: #ccff00;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>

<body>
  <header>
    <h1>GHOSTSTRATS // NOTORIOUS SQUIRREL</h1>
    <p><em>The lights didn’t go out. They were taken.</em></p>
  </header>

  <main>
    <div class="section">
      <p>Welcome to <strong>GHOSTSTRATS // NOTORIOUS SQUIRREL CTF</strong>, a cyberpunk CTF where you play as a rogue citizen trying to take down NEXUS — a sentient AI built in secret by Do Good Industries, set in a post-AI apocalypse.</p>
      <p>Track the corporation. Infiltrate the HQ. Evade the watchers. Find the kill switch. Shut it all down... or die trying.</p>
    </div>

    <div class="section stage-list">
      <h2>CTF Stages</h2>
      <ol>
        <li><strong>Stage 1: SIGNAL IN THE STATIC</strong><br>Use OSINT to locate Do Good Industries HQ via Instagram clues.</li>
        <li><strong>Stage 2: ENTRY PROTOCOL</strong><br>Clone badges and bypass smart locks to breach the facility.</li>
        <li><strong>Stage 3: SHADOWDANCE</strong><br>Evade cameras, drones, and Sentinels using stealth logic.</li>
        <li><strong>Stage 4: THE ROOM WITH NO NAME</strong><br>Decrypt and solve puzzles to retrieve the kill switch.</li>
        <li><strong>Stage 5: CASCADE FAILURE</strong><br>Attempt the shutdown — and watch it fail. The AI is ready.</li>
      </ol>
      <p><a href="stage1.html" class="start-button">▶ START HERE</a></p>
    </div>

    <div class="section">
      <p><strong>This is just the beginning...</strong><br>
      Part II: <em>THE SHATTERED SIGNAL</em> is coming soon.</p>
    </div>
  </main>

  <footer>
    &copy; 2025 GHOSTSTRATS CTF // Designed by Notorious Squirrel
  </footer>
</body>
</html>

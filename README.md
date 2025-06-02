<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Nervous System</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

    body {
      margin: 0;
      font-family: 'Pacifico', cursive;
      background: linear-gradient(to bottom right, #1a1a1a, #2c2c2c);
      color: white;
    }

    header {
      background-color: #000000;
      padding: 20px;
      text-align: center;
    }

    .typewriter-title {
      font-size: 2.5em;
      overflow: hidden;
      white-space: nowrap;
      border-right: 3px solid yellow;
      color: yellow;
      width: fit-content;
      margin: auto;
      animation: typing 3s steps(30, end), blink 0.75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      padding-bottom: 4px;
      border-bottom: 2px solid transparent;
      font-weight: bold;
    }

    nav a:hover {
      border-color: yellow;
    }

    .content {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      padding: 40px;
      gap: 30px;
    }

    .text {
      flex: 1;
    }

    .text h2 {
      color: #ffd700;
      font-size: 28px;
    }

    .text p {
      font-size: 18px;
      line-height: 1.6;
    }

    .images {
      flex: 1;
      display: flex;
      flex-direction: column;
      gap: 20px;
      align-items: center;
    }

    .images img {
      max-width: 100%;
      border: 3px solid yellow;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }

    .images img:hover {
      transform: scale(0.95);
    }

    @media (max-width: 768px) {
      .content {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="typewriter-title">Nervous System</div>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="nervous.html">Nervous System</a>
    <a href="glandular.html">Glandular System</a>
    <a href="reproductive.html">Reproductive System</a>
    <a href="funfacts.html">Fun Facts</a>
  </nav>

  <div class="content">
    <div class="text">
      <h2>Central Nervous System (CNS)</h2>
      <p>The CNS consists of the brain and spinal cord. It acts as the control center, processing information and directing actions throughout the body.</p>

      <h2>Parts of the Brain</h2>
      <p><strong>Cerebrum:</strong> The largest part, responsible for thinking, emotions, memory, and voluntary movement.</p>
      <p><strong>Cerebellum:</strong> Controls balance, posture, and coordination.</p>
      <p><strong>Midbrain:</strong> Connects the forebrain with the hindbrain and helps with vision and hearing reflexes.</p>
      <p><strong>Pons Varolii:</strong> A bridge between different parts of the nervous system, helps with breathing control.</p>
      <p><strong>Medulla Oblongata:</strong> Controls vital functions like heartbeat and respiration.</p>

      <h2>Peripheral Nervous System (PNS)</h2>
      <p>The PNS includes all nerves outside the CNS. It connects the brain and spinal cord to limbs and organs.</p>

      <h2>Autonomic Nervous System (ANS)</h2>
      <p>It is a part of the PNS that controls involuntary actions like heartbeat and digestion.</p>
      <p><strong>Sympathetic:</strong> Prepares the body for 'fight or flight' during stress.</p>
      <p><strong>Parasympathetic:</strong> Helps in 'rest and digest' actions, calming the body down.</p>
    </div>

    <div class="images">
      <img src="https://thumbs.dreamstime.com/z/human-brain-anatomy-sections-vector-illustration-44353466.jpg?w=360" alt="Brain Diagram" />
      <img src="https://spinalcordclinic.com/wp-content/uploads/2019/07/spine.jpg" alt="Spinal Cord" />
    </div>
  </div>
</body>
</html>

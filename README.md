<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NETROT | Cyber Playground</title>
  <style>
    body {
      margin: 0;
      font-family: monospace;
      background-color: #0d0d0d;
      color: #00ff99;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.2em;
    }

    p {
      font-size: 1.2em;
      color: #ccc;
    }

    .terminal {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px #00ff99;
      width: 90%;
      max-width: 600px;
    }

    .cursor {
      display: inline-block;
      width: 10px;
      height: 20px;
      background-color: #00ff99;
      animation: blink 1s step-start infinite;
      vertical-align: bottom;
    }

    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>
</head>
<body>
  <div class="terminal">
    <h1>NETROT</h1>
    <p>> initializing<span class="cursor"></span></p>
  </div>
</body>
</html>

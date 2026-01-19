<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Chargement…</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: #0f1115;
      font-family: Arial, Helvetica, sans-serif;
      color: #ffffff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .container {
      width: 100%;
      max-width: 900px;
      padding: 20px;
      text-align: center;
    }

    h1 {
      font-size: 22px;
      font-weight: 500;
      margin-bottom: 20px;
      opacity: 0.9;
    }

    video {
      width: 100%;
      max-height: 70vh;
      border-radius: 14px;
      background: #000;
      box-shadow: 0 0 40px rgba(0, 0, 0, 0.8);
    }

    .hint {
      margin-top: 15px;
      font-size: 13px;
      color: #9da3ae;
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>Chargement du contenu…</h1>

    <video autoplay muted controls playsinline>
      <source src="https://TON_LIEN_VIDEO_MP4" type="video/mp4">
      Ton navigateur ne supporte pas la lecture vidéo.
    </video>

    <div class="hint">
      Si la vidéo ne démarre pas automatiquement, clique sur lecture.
    </div>
  </div>

</body>
</html>



<html>
<head>
  <title>Herbalife Independent Distributor Tutorial Video</title>
  <style>
    body {
      background-image: url("https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg?cs=srgb&dl=pexels-johannes-plenio-1103970.jpg&fm=jpg");
      background-size: cover;
      font-family: Arial, sans-serif;
    }
    .container {
      width: 70%;
      margin: 0 auto;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.75);
      transition: transform 0.3s ease-in-out;
    }
    .container:hover {
      transform: scale(1.05);
    }
    .video-container {
      text-align: center;
      margin-top: 20px;
    }
    iframe {
      width: 100%;
      height: 500px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 20px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 16px;
      margin: 4px 2px;
      cursor: pointer;
    }
    
    /* Audio player */
    .audio-container {
      margin-top: 20px;
      width: 70%;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    
    audio {
      width: 100%;
      margin: 10px 0;
    }
    
    .audio-controls {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 10px;
    }
    
    .audio-controls button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 20px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 16px;
      margin: 4px 2px;
      cursor: pointer;
    }
    
    .audio-controls input[type=range] {
      margin: 0 10px;
    }
  </style>
  <script>
    // Set up the audio player
    const audio = document.getElementById('audio1');
    const playButton = document.getElementById('play-button');
    const pauseButton = document.getElementById('pause-button');
    const volumeSlider = document.getElementById('volume-slider');
    
    // Start playing the audio file automatically
    audio.autoplay = true;
    
    // Pause and play the audio file
    playButton.addEventListener('click', () => {
      audio.play();
    });
    
    pauseButton.addEventListener('click', () => {
      audio.pause();
    });
    
    // Adjust the volume
    volumeSlider.addEventListener('input', () => {
      audio.volume = volumeSlider.value / 100;
    });
  </script>
</head>
<body>
<p>&copy;2023, Nalini Sree | All rights reserved.</p>
  <div class="container">
    <h1 style="text-align:center">Herbalife Independent Distributor Tutorial Video</h1>
    <p style="text-align:center">As a Herbalife independent distributor, I have created a tutorial video to assist our valued customers in creating a custom ID, which can be accessed via the unlisted YouTube link provided below <a href="https://shorturl.at/djsFY">HOME PAGE</a></p>
    <div class="video-container">
      <iframe id="video1" src="https://www.youtube.com/embed/iJsfp0IybBw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <audio controls style="width:100%;max-width:400px;margin:20px auto;display:block;">
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
</body>
</html>

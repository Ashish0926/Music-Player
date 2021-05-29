<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Music Player</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Music Player</h1>

    <div class="music-container">
        <div class="music-info">
            <h4 id="title">FADED</h4>
            <div class="progress-container">
                <div class="progress"></div>
            </div>
        </div>
        <audio src="music/faded.mp3" id="audio"></audio>

        <div class="img-container">
            <img src="images/faded.jpg" alt="music-cover" id="cover">
        </div>

        <div class="navigation">
            <button id="prev" class="action-btn">
                <em class="fas fa-backward"></em>
            </button>
            <button id="play" class="action-btn action-btn-big">
                <em class="fas fa-play"></em>
            </button>
            <button id="next" class="action-btn">
                <em class="fas fa-forward"></em>
            </button>
        </div>
    </div>
</body>

<script src="script.js"></script>
</html>

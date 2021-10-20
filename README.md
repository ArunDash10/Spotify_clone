# Spotify_clone
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <title>Spotiy -Best Ever musics</title>
    

    
</head>

<body>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>

    <nav class="navbar navbar-expand-lg navbar-light bg-secondary" style="position: sticky;">
        <div class="brand">
            <a class="navbar-brand">
                <img src="Spotify_Logo_RGB_White.png" alt="1width="80" height="34"
                    class="d-inline-block align-text-top">
            </a>
        </div>

        <div class="nav-bar" id="navbar">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
            </ul>

        </div>

    </nav>
    <script src="https://kit.fontawesome.com/bfa187c49a.js" crossorigin="anonymous"></script>
    <div class="home">
        <div class="songlist">
            <h1>Songs</h1>
            <div class="songIteamCont">
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="0"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="2"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="3"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="4"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="5"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="6"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="7"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="8"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="9"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
                <div class="songitem">
                    <img alt="1">
                    <span class="songName">Havana</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i id="10"
                                class="far songItemPlay fa-play-circle"></i> </span></span>
                </div>
              
               


            </div>
        </div>
        <div class="songbanner"></div>
    </div>

    <div class="butoom">
        <input type="range" id="progressBar" min="0" value="0" max="100">
        <div class="icon">
            <i class="fas fa-2x fa-step-backward" style="padding-left:25px;" id="previous"></i>
            <i class="fas fa-2x fa-play" style="padding-left:25px;" id="masterPlay"></i>
            <i class="fas fa-2x fa-step-forward" style="padding-left:25px;" id="next"></i>
        </div>
        <div class="songinfo">
            <img src="playing.gif" alt="1" width="90px" id="gif">Havana..


        </div>
    </div>
    <script src="index.js"></script>
</body>

</html>

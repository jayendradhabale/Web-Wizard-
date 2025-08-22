<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Voice Clone Musics</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.0/css/all.min.css" integrity="sha512-DxV+EoADOkOygM4IR9yXP8Sb2qwgidEmeqAEmDKIOfPRQZOWbXCzLC6vjbZyy0vPisbH2SyW27+ddLVCN+OMzQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="logo.png">
    <link rel="stylesheet" href="spotifyclone.css">
</head>
<body>
    
    <div class="main">
        <div class="sidebar">
            <div class="nav">
                <div class="nav-option"  style="opacity: 1;">
                    <i class="fa-solid fa-house"></i>
                    <a href="#">Home</a>
                </div>
                <div class="nav-option">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <a href="#">Search</a>
                </div>
            </div>
            <div class="library ">
                <div class="options">
                    <div class="lib-options nav-option" >
                    <img src="library_icon.png" alt="library icon">
                    <a href="#">Your Library</a>
                </div>
                <div class="icons">
                    <i class="fa-solid fa-plus"></i>
                    <i class="fa-solid fa-arrow-right"></i>
                </div>
            </div>
            <div class="lib-box">
                <div class="box">
                    <p class="box-p1">Create your first playlist</p>
                    <p class="box-p2">It's easy,we'll help you</p>
                    <button class="badge">Create playlist</button>
                </div>
                <div class="box">
                    <p class="box-p1">Let's find some podcast to follow</p>
                    <p class="box-p2">We'll keep you updated on new episodes</p>
                    <button class="badge">Browse podcast</button>
                </div>
            </div>
            </div>
        </div>
      <div class="main_content">
              <div class="sticky-nav">
                <div class="sticky-nav-icons">
                    <img src="backward_icon.png" alt="backward_icon">
                    <img src="forward_icon.png" alt="forward_icon" class="hide">
                </div>
                <div class="sticky-nav-options">
                    <button class="badge nav-items hide">Explore Premium</button>
                    <button class="badge nav-items dark-badge"><i class="fa-regular fa-circle-down" style="margin-left: 5px;"></i>Install App</button>
                    <i class="fa-regular fa-user nav-items dark-badge"></i>
                </div>
            </div>
            <h2>Recently Played</h2>
                <div class="cards-container">
                    <div class="card">
                        <img src="card1img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                </div>
            <h2>Trending now near you</h2>
                <div class="cards-container">
                    <div class="card">
                        <img src="card2img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                    <div class="card">
                        <img src="card3img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                    <div class="card">
                        <img src="card4img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                    <div class="card">
                        <img src="card3img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                    <div class="card">
                        <img src="card4img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                </div>  
                <h2>Featured Charts</h2>
                <div class="cards-container">
                    <div class="card">
                        <img src="card5img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                    <div class="card">
                        <img src="card6img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top Songs - India</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>
                    <div class="card">
                        <img src="card1img.jpeg" alt="cardimg" class="card-img">
                        <p class="card-title">Top 50 - Global</p>
                        <p class="card-info">Your daily updates of the most played...</p>
                    </div>  
                </div>  
                <div class="footer">
                    <div class="line"></div>
                </div> 
        </div>
        <div class="music_player">
            <div class="album">
                <div class="album-pic">
                    <img src="album_picture.jpeg" alt="img" class="album-pic" >
                </div>
                <div class="album-text">
                    <h4 class="album-heading">Daylight</h4>
                    <p class="album-text-p">David Kushnar</p>
                </div>
                <div class="album-icons">
                    <img src="album_icon1.png" alt="heart" class="album-icons-heart">
                    <img src="album_icon2.png" alt="bar" class="album-icons-bar">
                </div>
            </div>
            <div class="player">
                <div class="player-controls">
                    <img src="player_icon1.png" alt="icon" class="player-control-icon">
                    <img src="player_icon2.png" alt="icon" class="player-control-icon">
                    <img src="player_icon3.png" alt="icon" class="player-control-icon" style="opacity: 1; height: 2rem;">
                    <img src="player_icon4.png" alt="icon" class="player-control-icon">
                    <img src="player_icon5.png" alt="icon" class="player-control-icon">
                </div>
                <div class="playback-bar">
                    <span class="curr-time">00:00</span>
                    <input type="range"min="0" max="100" class="progress-bar" step="1">
                    <span class="total-time">3:33</span>
                </div>
            </div>
            <div class="controls">
                <div class="controls-icons">
                    <img src="controls_icon1.png" alt="#" class="controls-icons-big">
                    <img src="controld_icon2.png" alt="#" class="controls-icons-big">
                    <img src="controls_icon3.png" alt="#" class="controls-icons-in">
                    <img src="controls_icon4.png" alt="#" class="controls-icons-in">
                    <img src="controls_icon5.png" alt="#" class="controls-icons-big">
                </div>
                <div class="controls_progress-bar">
                    <input type="range" step="1" max="15">
                </div>
            </div>
        </div>
    </div>
</body>
</html>

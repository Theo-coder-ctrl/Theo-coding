
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- metadata -->
    <title>Theoblox - Play Free Online Games!</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, user-scalable=no, maximum-scale=1.0" />
    <meta
      name="description"
      content="Play free online games such as BedWars, Skywars, and more! Build with an unlimited selection of blocks. No login required!" />
    <meta name="theme-color" content="#FF0000" />
    <meta name="keywords" content="Blocks, Voxel, Building, Parkour, PVP, Videogame, BlockCraft, Theoblox" />
    <meta name="author" content="Victor Wei, qhyun" />

    <meta name="theme-color" content="#FF0000" />
    <meta name="mobile-web-app-capable" content="yes" />
    <meta name="apple-mobile-web-app-capable" content="yes" />

    <!-- open graph metadata -->
    <meta property="og:title" content="Theoblox" />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://Theoblox.io" />
    <meta property="og:image" content="/images/titlescreen/default.png" />
    <meta
      property="og:description"
      content="Play free online games such as Bedwars, Skywars, and more! Build with an unlimited selection of blocks. No login required!" />

    <!-- progressive web app manifest-->
    <link rel="manifest" href="manifest.json" />

    <!-- prevent caching of index.html -->
    <meta http-equiv="Cache-control" content="no-cache, no-store, must-revalidate" />
    <meta http-equiv="expires" content="0" />
    <meta http-equiv="Pragma" content="no-cache" />

    <!-- favicon -->
    <link rel="icon" type="image/png" href="/favicon.png" />

    <link rel="preconnect" href="https://www.google.com" />
    <link rel="preconnect" href="https://www.gstatic.com" crossorigin />

    <!-- recaptcha -->
    <script src="https://www.google.com/recaptcha/api.js?render=6Ld0f2UqAAAAAF5kaPg3hGzwAwdJ7y6DbxAlD2t6"></script>

    <!-- font -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet" crossorigin="anonymous" />
      //CMP tool settings
      aiptag.cmp = {
        show: false,
        position: "centered", //centered or bottom
        button: true,
        buttonText: "Privacy settings",
        buttonPosition: "bottom-left", //bottom-left, bottom-right, top-left, top-right
      };

      // disable adinplay console banner by temporarily unbinding console.log
      window.tempConsoleLog = window.console.log;
      window.console.log = function () {};
    </script>
    <script src="//api.adinplay.com/libs/aiptag/pub/BLC/blockcraft.online/tag.min.js"></script>
    <script>
      window.console.log = window.tempConsoleLog;
    </script>

    <!-- Global site tag (gtag.js) - Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-HJ760XE436"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag() {
        dataLayer.push(arguments);
      }
      gtag("js", new Date());

      gtag("config", "G-HJ760XE436");
    </script>

    <script src="https://sdk.crazygames.com/crazygames-sdk-v3.js"></script>
    <script src="https://challenges.cloudflare.com/turnstile/v0/api.js?render=explicit"></script>
    <script type="module" crossorigin src="/assets/index-C0r91HPd.js"></script>
    <link rel="stylesheet" crossorigin href="/assets/index--4F_0oIe.css">
  </head>

  <body>
    <div style="position: absolute; right: 0" id="preroll"></div>
  
          AIP_COMPLETE: function (evt) {
            /*******************
           ***** WARNING *****
           *******************
           Please do not remove the PREROLL_ELEM
           from the page, it will be hidden automaticly.
           If you do want to remove it use the AIP_REMOVE callback.
          */
            console.error("Preroll Ad Completed: " + evt);
          },
          AIP_REMOVE: function () {},
        });
      });
    </script>
    <!-- Loading Screen -->
    <div id="loading-screen">
      <div class="background-image" style="image-rendering: pixelated"></div>

      <div id="loading-screen-container">
        <div id="loading-screen-text">Theoblox</div>
        <div id="progress-bar">
          <div id="progress-bar-inner"></div>
        </div>
        <div id="progress-text">Initializing game...</div>
      </div>
    </div>

    <!-- Game -->
    <div id="react" style="position: absolute; width: 100%; height: 100%; z-index: 4"></div>
    <canvas id="canvas-hud"></canvas>
    <div id="canvas-holder"></div>
  </body>
</html>

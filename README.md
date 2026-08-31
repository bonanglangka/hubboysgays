
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Play Video</title>

<style>
body{
    background:#111;
    color:#fff;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    flex-direction:column;
    font-family:Arial,sans-serif;
}

button{
    padding:15px 30px;
    font-size:20px;
    background:#ff0000;
    color:#fff;
    border:none;
    border-radius:50px;
    cursor:pointer;
}
</style>
</head>
<body>

<!-- Script iklan -->
<div id="ads">
    <script data-cfasync="false" async type="text/javascript" src="//eq.hoggiesatieno.com/tjYtgNBL7HjxozlE8/137861"></script>
</div>

<br>

<button onclick="playVideo()">▶ Play Video</button>

<video id="video" width="720" controls style="display:none;margin-top:20px;">
    <source src="video.mp4" type="video/mp4">
    Browser Anda tidak mendukung video.
</video>

<script>
function playVideo() {
    const video = document.getElementById("video");
    video.style.display = "block";
    video.play();
}
</script>
   <!-- Histats.com  START  (aync)-->
<script type="text/javascript">var _Hasync= _Hasync|| [];
_Hasync.push(['Histats.start', '1,4626895,4,0,0,0,00010000']);
_Hasync.push(['Histats.fasi', '1']);
_Hasync.push(['Histats.track_hits', '']);
(function() {
var hs = document.createElement('script'); hs.type = 'text/javascript'; hs.async = true;
hs.src = ('//s10.histats.com/js15_as.js');
(document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(hs);
})();</script>
<noscript><a href="/" target="_blank"><img  src="//sstatic1.histats.com/0.gif?4626895&101" alt="" border="0"></a></noscript>
<!-- Histats.com  END  -->
</body>
</html>

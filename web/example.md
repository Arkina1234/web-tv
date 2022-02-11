<html>
<div id="myElement"></div>

<script>
var playerInstance = jwplayer("myElement");
    playerInstance.setup({
      file: "/uploads/myVideo.mp4",
      width: 640,
      height: 270,
      autostart: true,
      mute: true //optional, but recommended
    });
</script>
<html>

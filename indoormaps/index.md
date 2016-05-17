---
layout: page
title: Indoor Maps
---

***

* [Prof. K. Gopinath's Office]({{site.url}}/indoormaps/gopi_office/)
* [Computer Architecture and System Labs]({{site.url}}/indoormaps/labs/)

***

<style type="text/css">
 img:hover {
  cursor:pointer;
 }
</style>

<img onclick="aud_play_pause();" id="portalradio" src="{{site.url}}/images/indoormaps/easteregg1.png"/>


<audio id="sstv_audio">
<source src="{{site.url}}/images/indoormaps/sstv_cake.mp3" type='audio/mp3'>
</audio>

<script>

function changeImage(playing)
{
	if(playing) {
		var img = document.getElementById("portalradio");
		img.src="{{site.url}}/images/indoormaps/easteregg1_on.png";
		return false;
	} else {
		var img = document.getElementById("portalradio");
		img.src="{{site.url}}/images/indoormaps/easteregg1.png";
		return false;
	}
}

function aud_play_pause() {
  var sstv_audio = document.getElementById("sstv_audio");
  if (sstv_audio.paused) {
  	sstv_audio.currentTime = 0;
    sstv_audio.play();
    changeImage(true);
  } else {
    sstv_audio.pause();
    changeImage(false);
  }
}
</script>

<a href="javascript:history.back()">Go Back</a>
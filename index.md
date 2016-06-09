---
layout: page
title: Welcome to CASL
---
<p class="message">
	Welcome to Computer Architecture and Systems Lab in the Department of Computer Science and Automation, Indian Institute of Science, Bangalore
</p>

<!-- Slideshow 2 -->
<div class="rslides_container">
	<ul class="rslides" id="slider2">
		<li><img src="images/home/1.jpg" alt="" height="400px"></li>
		<li><img src="images/home/2.jpg" alt=""></li>
		<li><img src="images/home/3.jpg" alt=""></li>
	</ul>
</div>

## Areas of Research
The following are some of the areas in which we work on:

* Operating systems
* Filesystems
* Storage Systems
* Clustered and Distributed Storage
* Cloud Storage
* Solid-State Storage
* Mobile Computing
* Storage Caching
* Protocols and Verification

***

## Latest Publications
* [Prudent Memory Reclamation in Procrastination based Synchronization]()
<b>Aravinda Prasad, K Gopinath</b> ASPLOS 2016
* [More &#8608;](publications)

***

## Facilities

* 40 Node Cluster each with 3 TB HDD, 8-core & 8 GB RAM
* CASL Wi-Fi
* [More &#8608;](facilities)

***

Have questions or suggestions? Feel free to [contact us](contact).

Thanks for stopping by!
<style>
	.rslides {
		position: relative;
		list-style: none;
		overflow: hidden;
		width: 100%;
		padding: 0;
		margin: 0;
	}

	.rslides_container {
		margin-bottom: 50px;
		position: relative;
		float: left;
		width: 100%;
	}

	.rslides li {
		-webkit-backface-visibility: hidden;
		position: absolute;
		display: none;
		width: 100%;
		left: 0;
		top: 0;
	}

	.rslides li:first-child {
		position: relative;
		display: block;
		float: left;
	}

	.rslides img {
		display: block;
		height: auto;
		float: left;
		width: 100%;
		border: 0;
	}

	.transparent-btns_nav {
		z-index: 3;
		position: absolute;
		-webkit-tap-highlight-color: rgba(0,0,0,0);
		top: 0;
		left: 0;
		display: block;
		background: #fff; /* Fix for IE6-9 */
		opacity: 0;
		filter: alpha(opacity=1);
		width: 48%;
		text-indent: -9999px;
		overflow: hidden;
		height: 91%;
	}

	.transparent-btns_nav.next {
		left: auto;
		right: 0;
	}

	.transparent-btns_nav:focus,
	.large-btns_nav:focus {
		outline: none;
	}

	.transparent-btns_tabs,
	.large-btns_tabs {
		margin-top: 10px;
		text-align: center;
	}

	.transparent-btns_tabs li,
	.large-btns_tabs li {
		display: inline;
		float: none;
		_float: left;
		*float: left;
		margin-right: 5px;
	}

	.transparent-btns_tabs a,
	.large-btns_tabs a {
		text-indent: -9999px;
		overflow: hidden;
		-webkit-border-radius: 15px;
		-moz-border-radius: 15px;
		border-radius: 15px;
		background: #ccc;
		background: rgba(0,0,0, .2);
		display: inline-block;
		_display: block;
		*display: block;
		-webkit-box-shadow: inset 0 0 2px 0 rgba(0,0,0,.3);
		-moz-box-shadow: inset 0 0 2px 0 rgba(0,0,0,.3);
		box-shadow: inset 0 0 2px 0 rgba(0,0,0,.3);
		width: 9px;
		height: 9px;
	}

	.transparent-btns_here a,
	.large-btns_here a {
		background: #222;
		background: rgba(0,0,0, .8);
	}
</style>

<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
<script src="public/js/responsiveslides.js"></script>
<script>
	$(function() {
		$(".rslides").responsiveSlides({
			auto: true,
  			speed: 500,
  			timeout: 3000,
			pager: true,
			nav: true,
			speed: 500,
			maxwidth: 800,
			namespace: "transparent-btns"
		});
	});
</script>
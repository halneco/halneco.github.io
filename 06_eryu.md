---
layout: page
title: ERYU
nav-menu: true
show_tile: false
image: character_thumbs/06_eryu.png
character-2Dimage: assets/images/eryu_main2.png
character-3Dimage: assets/images/eryu_main.png
character-name: エリュー = セントペルム
serifu: 「アスティーといつまでも<br>　　　いっしょにいられますように。」
prof1: Eryu=Sentperm age:14 female
prof2: 絶滅したとされる竜人族の女の子。<br>さらわれそうになっていたところをアスティーヴに助けられ、<br>それから旅を共にする。アスティーヴのことが大好き。<br>感情が昂ると竜化し、暴走してしまうことがある。
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<div class="flexcontainer ">

			<div>
				<header class="major">
					<h2>{{ page.character-name }}</h2>
					<p>{{ page.prof1 }}</p>
				</header>
				<p>{{ page.prof2 }}</p>
			</div>

			<div class="character">

				<img class="title-off" src="{{ page.character-2Dimage }} " />
				<img class="title-on" src="{{ page.character-3Dimage }} " />

				<h3 class="serifu fade-in-bottom">{{ page.serifu }}</h3>

				<button type="button" class="image-change-botton toggle button">2D⇔3D</button>

			</div>

		</div>


	</div>
</section>

<!-- Two -->
<section id="two">
	<div class="inner">
		<p>Designed by my Friend, 天野きみ. Thanks!</p>
		<div class="flexcontainer">
			<img src="assets/images/eryu_siryo1.JPG" style="margin:5px"/>
			<img src="assets/images/eryu_siryo2.jpg" style="margin:5px"/>
		</div>
	</div>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>CHARACTER</h2>
		</header>

		{% include select-character.html %}

	</div>
</section>
</div>
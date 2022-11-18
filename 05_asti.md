---
layout: page
title: ASTI
nav-menu: true
show_tile: false
image: character_thumbs/05_asti.PNG
character-image: assets/images/asti_main.PNG
character-name: アスティーヴ = クラウザー
serifu: 「俺にはエリューを守る義務がある。<br>　　　ただ…それだけだ。」
prof1: Astiv=Krauser age:21 male
prof2: 竜人族を人為的に生成する実験の実験体。<br>物心ついた時から研究所で実験体として扱われていた。<br>研究所で起こったある事件の混乱に乗じて逃げ出し、放浪の旅をしている。<br>自分が受けてきた実験が竜人族の絶滅に関与していることから、竜人族に対して負い目を感じている。<br>旅の途中で出会った竜人族のエリューを、何があっても守り通すと決意する。
mini-front: assets/images/asti_mini_front.jpg
mini-back: assets/images/asti_mini_back.jpg
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
				<img src="{{ page.character-image }} " width="300" height="540"/>
				<h3 class="serifu fade-in-bottom">{{ page.serifu }}</h3>
			</div>

		</div>


	</div>
</section>

<!-- Two -->
<section id="two">
	<div class="inner">
		<div class="flexcontainer">
			<img class="miniflexitem" src="{{ page.mini-front }} " style="margin:5px;"/>
			<img class="miniflexitem" src="{{ page.mini-back }} " style="margin:5px;"/>
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
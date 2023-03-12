---
layout: page
title: ROOT
nav-menu: true
show_tile: false
image: character_thumbs/04_root.png
character-2Dimage: assets/images/root_main.png
character-3Dimage: assets/images/root_main2.png
character-name: ルートヴィヒ = ツヴェルガー
serifu: 「俺は一人で大丈夫だ。<br>　　　兄さんがいなくてもうまくやるさ。」
prof1: Ludwig=Zwerger age:17 male
prof2: アルフの弟。冷静沈着な性格。<br>魔女である母の血を濃く引継ぎ、魔法を扱うのが得意。<br>生まれつき呪いにかかっており、永久に死ぬことができない。<br>アルフと呪いを解く方法を探す旅をしている。
mini-front: assets/images/root_mini_front.JPG
mini-back: assets/images/root_mini_back.JPG
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
				<img class="title-off" src="{{ page.character-2Dimage }}" width="300" height="540" />
				<img class="title-on" src="{{ page.character-3Dimage }} " width="300" height="540"/>

				<h3 class="serifu fade-in-bottom">{{ page.serifu }}</h3>

				<button type="button" class="image-change-botton toggle button">2D⇔3D</button>
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
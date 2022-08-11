---
layout: page
title: SHIRO
nav-menu: true
show_tile: false
image: character_thumbs/01_shiro.PNG
character-image: assets/images/shiro_main.PNG
character-name: シロ
serifu: 「クロ…ぼくはきみと生きたい。<br>　　　そしてきみを闇から救いたい。」
prof1: Shiro age:17 male
prof2: 記憶がない不思議な少年。<br>幼少期に精神だけの存在であるクロと出会い、クロを自分の身体に招き入れた。<br>独り言を言ったり、ぼーっとしていることが多い。<br>シロに救われた人は言う、「すべてが許された気がした。彼は"神"の代理人か」…と。<br>クロのことを家族のように大切に思っている。
mini-front: assets/images/shiro_mini_front.jpg
mini-back: assets/images/shiro_mini_back.jpg
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
		<img src="assets/images/shiro_siryo.PNG" style="margin:5px"/>
	</div>
</section>

<!-- Four -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>CHARACTER</h2>
		</header>

		{% include select-character.html %}

	</div>
</section>
</div>
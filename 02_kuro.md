---
layout: page
title: KURO
nav-menu: true
show_tile: false
image: character_thumbs/02_kuro.PNG
character-image: assets/images/kuro_main.PNG
character-name: クロ
serifu: 「俺の国が…家族が…<br>　　どうして滅ばなければならなかったのか。<br>　　　　　　俺はそれを知りたい。」
prof1: Kuro age:17 male
prof2: 亡国の王子。影を使って攻撃する闇魔法が得意。<br>幼少期、国から逃れる際の争いの中で身体をなくし、<br>闇の中を彷徨う精神だけの存在となった。<br>逃げた先で出会ったシロの身体に居候しており、<br>クロが表に出てくると髪や服の色が変わる。<br>シロのことを家族のように大切に思っている。
mini-front: assets/images/kuro_mini_front.jpg
mini-back: assets/images/kuro_mini_back.jpg
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
				<img src="{{ page.character-image }} " width="600" height="1080" />
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
---
layout: page
title: ALF
nav-menu: true
show_tile: false
image: character_thumbs/03_alf.png
character-image: assets/images/alf_main.png
character-name: アルフレート = ツヴェルガー
serifu: 「ルート、俺はお前を見捨てない。<br>　　　　　何があっても、絶対に…だ！」
prof1: Alfred=Zwerger age:17 male
prof2: ルートの双子の兄。明るくポジティブ。<br>獣人族である父の血を濃く引継ぎ、接近戦が得意。<br>ルートの呪いを解く方法を探すという建前で旅をしているが、<br>実は呪いを解く方法はないことを知っている。
mini-front: assets/images/alf_mini_front.JPG
mini-back: assets/images/alf_mini_back.JPG
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
				<img src="{{ page.character-image }}" class="imgtest"/>
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
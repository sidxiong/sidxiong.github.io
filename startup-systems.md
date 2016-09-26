---
layout: layout
title: Startup Systems Homework - Personal Page
---

<section class="content">

<div>
  <a href="/images/deepio1.png">
    <img src="/images/deepio1.png" class="rounded-img" alt="Me"/>
  </a>
</div>

# Homework - Personal Page

I am currently a Master student in Computer Science at Cornell University and Cornell Tech.

My NetID is **sx225**.

This page is used for homework of Startup Systems Design and Engineering.

# Homework - JS onclick
<div class='js-play'>
<button id='show-pic' style="color:black" onclick="showPic(this)"><span>Click me!</span></button>
<div id='pic2' style="display: none">
  <a href="/images/deepio2.png">
    <img src="/images/deepio2.png" class="rounded-img" alt="Me2"/>
  </a>
</div>
<script type="text/javascript">
	function showPic(elem) {
		if (elem.style.color == 'black') {
			elem.style.color = 'red';
		} else {
			elem.style.color = 'black';
		}
		var pic2 = document.getElementById('pic2');
		if (pic2.style.display == 'block') {
			pic2.style.display = 'none';
		} else {
			pic2.style.display = 'block';
		}
	}
</script>
</div>
</section>
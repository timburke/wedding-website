---
title: Photo Gallery
layout: gallery
---

<div class="galleria">

</div>

<script type="text/javascript">
	Galleria.ready(function(options) {
		this.push({image: 'img/gallery/converted/couple_1.jpg'});
	});
	
	var data = [
	    {
	        image: 'img/gallery/converted/camping_1.jpg',
	        title: "Saumya's Head",
	        description: "This is a description of Saumya's head",
	    },

	    {
	        image: 'img/gallery/converted/camping_2.jpg',
	        title: "Tim's Head",
	        description: "This is a description of Tim's head",
	    },
	];

	Galleria.loadTheme('js/themes/classic/galleria.classic.js');
	Galleria.configure({_toggleInfo: false});

    Galleria.run('.galleria', {dataSource: data});
</script>
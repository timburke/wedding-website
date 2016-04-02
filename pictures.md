---
title: Photo Gallery
layout: gallery
---

<div class="galleria">

</div>

<script type="text/javascript">
	var data = [
	    {
	        image: 'img/saumya_headshot.jpg',
	        title: "Saumya's Head",
	        description: "This is a description of Saumya's head",
	    },

	    {
	        image: 'img/tim_headshot.jpg',
	        title: "Tim's Head",
	        description: "This is a description of Tim's head",
	    },
	];

	Galleria.loadTheme('js/themes/classic/galleria.classic.min.js');
    Galleria.run('.galleria', {dataSource: data});
</script>
---
type: landing
directory: architecture
title: Architecture 
page_title: Architecture 
description: Architecture Overview
keywords: Architecture Overview
published: true
allowSearch: true
---
<div id="preview"></div>
<div id="preview1"></div>
<script>

		$(document).ready(function(){
			var animData = {
				wrapper: document.getElementById('preview'),
				animType: 'svg',
				loop: true,
				prerender: true,
				autoplay: true,
				path: "data.json"
			};
			var anim = bodymovin.loadAnimation(animData);
			var animData1 = {
				wrapper: document.getElementById('preview1'),
				animType: 'svg',
				loop: true,
				prerender: true,
				autoplay: true,
				path: "data1.json"
			};
			var anim = bodymovin.loadAnimation(animData1);
		});
	
</script>

Sunbird is a next-generation, societal learning platform built for cloud/mobile native environments and meant to address teaching and learning use cases.It is architected to enhance on scalibility and extensibility.Multiple organizations can exist independently as tenants on the platform and users of these organizations can access the platform via mobile devices, tablets, laptops and desktops.

{% image src='img/architecture/image/arch_overview.png' full center alt='Sunbird Architecture' %}

The platform is developed based on specific architectural design principles that ensures openness, interoperability and plug and play options. In addition, the architecture allows for contributions and shared access to common components such as frameworks, models and content.

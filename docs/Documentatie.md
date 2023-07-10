---
layout: page-with-side-nav
title: Documenten StUF-BG
folder_files:
  - title: Bg0204_20120701_patch13.zip
    path: documenten/Bg0204_20120701_patch13.zip
    group: 204
  - title: Bg0310_20211208_patch32.zip
    path: documenten/Bg0310_20211208_patch32.zip
    group: 310
  - title: Extra-elementen_voor_bg0204.zip
    path: documenten/Extra-elementen_voor_bg0204.zip
    group: 204
  - title: Extra-elementen_voor_bg0310.zip
    path: documenten/Extra-elementen_voor_bg0310.zip
    group: 310
  - title: GFO_Basisgegevens.pdf
    path: documenten/GFO_Basisgegevens.pdf
    group: 204
  - title: KeuzenVerStUFfing_RSGB.pdf
    path: documenten/KeuzenVerStUFfing_RSGB.pdf
    group: 310
---

# Documentatie

## StUF-BG 3.10

<ul>
	{% for i in page.folder_files %}
		{% if i.group == 310 %} 
			<li>
			  <a href="{{ i.path | base_url }}">
				{{ i.title }}
			  </a>
			</li>
		{% endif %} 
	{% endfor %}
</ul>

## StUF-BG 2.04

<ul>
	{% for i in page.folder_files %}
		{% if i.group == 204 %} 
			<li>
			  <a href="{{ i.path | base_url }}">
				{{ i.title }}
			  </a>
			</li>
		{% endif %} 
	{% endfor %}
</ul>

---
layout: page-with-side-nav
title: Documenten StUF-BG
folder_files:
  - title: Bg0204_20120701_patch13.zip
    path: documenten/Bg0204_20120701_patch13.zip
    group: 204
    versie: 13
    status: Definitief
    omschrijving: 
  - title: Bg0310_20211208_patch32.zip
    path: documenten/Bg0310_20211208_patch32.zip
    group: 310
    versie: 32
    status: Definitief
    omschrijving: Bevat alle documentatie, schema's en WSDL's behorende bij patch 32 van StUF-BG 3.10 inclusief alle bij de StUF 3.01 onderlaag horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-BG 3.10 horende extraElementen.
  - title: Extra-elementen_voor_bg0204.zip
    path: documenten/Extra-elementen_voor_bg0204.zip
    group: 204
    versie: 3-12-2021
    status: Definitief
    omschrijving: 
  - title: Extra-elementen_voor_bg0310.zip
    path: documenten/Extra-elementen_voor_bg0310.zip
    group: 310
    versie: 3-12-2021
    status: Definitief
    omschrijving: 
  - title: GFO_Basisgegevens.pdf
    path: documenten/GFO_Basisgegevens.pdf
    group: 204
    versie: 
    status: 
    omschrijving: 
  - title: KeuzenVerStUFfing_RSGB.pdf
    path: documenten/KeuzenVerStUFfing_RSGB.pdf
    group: 310
    versie: 1.14
    status: Definitief
    omschrijving: 
---

# Documentatie

## StUF-BG 3.10

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 310 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
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

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 204 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
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

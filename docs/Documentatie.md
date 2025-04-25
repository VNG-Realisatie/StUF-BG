---
layout: page-with-side-nav
title: Documentatie StUF-BG
folder_files:
  - title: Bg0310 20250321 patch33 (zip)
    path: documenten/bg0310_20250321_patch33.zip
    group: 310
    versie: 33
    status: Definitief
    omschrijving: Patch i.v.m. de wens Tijdelijke verblijfsadressen van niet ingezetene te kunnen uitwisselen. Bevat alle documentatie, schema's en WSDL's behorende bij patch 33 van StUF-BG 3.10 inclusief alle bij de StUF 3.01 onderlaag horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-BG 3.10 horende extraElementen.
    datum: 20250321
  - title: Extra-elementen voor bg0310 (zip)
    path: documenten/Extra-elementen_voor_bg0310.zip
    group: 310
    versie: 21-3-2025
    status: Definitief
    omschrijving: Bevat alle extraElementen t/m patch 33.
    datum: 20250321
  - title:  KeuzenVerStUFfing RSGB (pdf)
    path: documenten/KeuzenVerStUFfing_RSGB.pdf
    group: 310
    versie: 1.14
    status: Definitief
    omschrijving: 
    datum: 20211203
  - title: Bg0204 20250321 patch14 (zip)
    path: documenten/bg0204_20250321_patch14.zip
    group: 204
    versie: 14
    status: Definitief
    omschrijving: Patch i.v.m. de wens Tijdelijke verblijfsadressen van niet ingezetene te kunnen uitwisselen. Bevat alle documentatie, schema's en WSDL behorende bij patch 14 van StUF-BG 2.04 inclusief alle bij de StUF 2.04 onderlaag horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-BG 2.04 horende extraElementen.
    datum: 20250321
  - title: Extra-elementen voor bg0204 (zip)
    path: documenten/Extra-elementen_voor_bg0204.zip
    group: 204
    versie: 21-3-2025
    status: Definitief
    omschrijving: PBevat alle extraElementen t/m patch 14.
    datum: 20250321
  - title: GFO Basisgegevens (pdf)
    path: documenten/GFO_Basisgegevens.pdf
    group: 204
    versie: 
    status: 
    omschrijving: 
    datum: 
---

# Documentatie

## StUF-BG 3.10

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
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
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## StUF-BG 2.04

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
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
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

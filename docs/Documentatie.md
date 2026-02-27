---
layout: page-with-side-nav
title: Documentatie StUF-BG
folder_files:
  - title: Bg0310 20260227 patch34 (zip)
    path: documenten/bg0310_20260227_patch34.zip
    group: 310
    versie: 34
    status: Definitief
    omschrijving: Patch naar aanleiding van de wijziging van de maximale lengte van de landnaam van 40 posities naar 80 posities in de LO-BRP.<br/>Daarnaast zijn ook enkele verbeteringen in de documentatie aangebracht. Bevat alle documentatie, schema's en WSDL's behorende bij patch 34 van StUF-BG 3.10, StUF-ZKN 3.10 en StUF-ZTC 3.10 inclusief alle bij de StUF 3.01 onderlaag horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-BG 3.10, StUF-ZKN 3.10 en StUF-ZTC 3.10 horende extraElementen.
    datum: 20260227
  - title: Extra-elementen voor bg0310 (zip)
    path: documenten/Extra-elementen_voor_bg0310.zip
    group: 310
    versie: 15-1-2026
    status: Definitief
    omschrijving: Bevat alle extraElementen t/m patch 34.
    datum: 20260115
  - title:  KeuzenVerStUFfing RSGB (pdf)
    path: documenten/keuzenVerStUFfing_RSGB.pdf
    group: 310
    versie: 1.16
    status: Definitief
    omschrijving: Er is een opmerking opgenomen m.b.t. de betekenis van de kardinaliteit in semantische modellen en de gevolgen van het verplicht stellen van attributen in een database.
    datum: 20260113
  - title: Bg0204 20260227 patch15 (zip)
    path: documenten/bg0204_20260227_patch15.zip
    group: 204
    versie: 15
    status: Definitief
    omschrijving: Patch naar aanleiding van de wijziging van de maximale lengte van de landnaam van 40 posities naar 80 posities in de LO-BRP.<br/>Daarnaast zijn ook enkele verbeteringen in de documentatie aangebracht. Bevat alle documentatie, schema's en WSDL's behorende bij patch 34 van StUF-BG 3.10, StUF-ZKN 3.10 en StUF-ZTC 3.10 inclusief alle bij de StUF 3.01 onderlaag horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-BG 3.10, StUF-ZKN 3.10 en StUF-ZTC 3.10 horende extraElementen.
    datum: 20260227
  - title: Extra-elementen voor bg0204 (zip)
    path: documenten/Extra-elementen_voor_bg0204.zip
    group: 204
    versie: 15-1-2026
    status: Definitief
    omschrijving: Bevat alle extraElementen t/m patch 15.
    datum: 20260115
  - title: Sectormodel StUF-BG 2.04 Berichtdefinities (pdf)
    path: documenten/bg0204.pdf
    group: 204
    versie: 21-03-2025
    status: Definitief
    omschrijving: Bevat aanpassingen i.v.m. de wens Tijdelijke verblijfsadressen van niet ingezetene te kunnen uitwisselen.
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

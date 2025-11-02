---
# try also 'default' to start simple
theme: ../Prf-Slidev-Theme
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
#background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Was darf Tabakwerbung?
info: Präsentation zu verbotener und erlaubter Tabakwerbung in Deutschland
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min

colorSchema: light
hideInToc: true
layout: cover
---

# Was darf Satire? Ziemlich viel.

## Was darf Tabakwerbung? Nicht viel.

Eine Übersicht des Vereins Pro Rauchfrei e.V.

<div class="mute">
Inhalt: Barbara Soukup-Sterl, Dipl.-Jur. Stephan Weinberger, Produktion: Rene Schmidt
</div>

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Zum Starten drücken Sie die Leertaste <carbon:arrow-right />
</div>


<ProRauchfreiLogo/>
<SlideRefs/>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
hideInToc: true
---

# Was macht Pro Rauchfrei e.V.?

…ist Deutschlands größte Nichtraucherlobby, die sich für das Grundrecht auf rauchfreie Luft einsetzt, um Nichtraucher und aufhörwillige Raucher in Restaurants, Wohnräumen und Kinder zu schützen.

- <span v-click>🚀 **Mission**: Für eine rauchfreie Gesellschaft kämpfen und alle verfügbaren Mittel einsetzen.</span>
- <span v-click>⚖️ **Recht** auf saubere Luft: Als Grundrecht des Grundgesetzes geschützt und lebensnotwendig für alle.</span>  
- <span v-click>📜 **Prinzip**: Uneingeschränktes Recht aller Bürger auf rauchfreie Atemluft.</span>
- <span v-click>🗽 **Unabhängigkeit**: Keine Finanzierung durch Tabak- oder Pharmaindustrie; ablehnend jeglicher Zuwendungen.</span>
- <span v-click>🤝 **Hilfe**: Bietet umfassende Beratung & Unterstützung für Nichtraucherschutz und Rauchaufhörschritte.</span>

<br>

<span v-click>🌐 Weitere Informationen auf [pro-rauchfrei.de](https://www.pro-rauchfrei.de)</span>

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: two-cols
layoutClass: gap-20
hideInToc: true
---

# Zweck dieser Präsentation

 …ist zu klären, welche Werbeformen verboten sind, welche rechtlichen Grauzonen existieren und was es bei Sponsoring zu beachten gilt.

Gezeigt werden auch konkrete Beispiele verbotener Werbung für Tabak- und Nikotinprodukte.

::right::

<Toc text-sm minDepth="1" maxDepth="2" />

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: image-right
image: img/german_law_by_mistral_ai.jpg
---

# Rechtliche Grundlagen

Gesetze und Richtlinien

- <span v-click>**Tabakerzeugnisgesetz (TabakerzG)**: Paragraphen 19–21</span>
- <span v-click>**EU-Tabak-Richtlinie (RL 2014/40/EU)**: Erwägungsgrund 43 (elektronische Zigaretten)</span>
- <span v-click>**Bundesrecht und EU-Richtlinien**: Kombination aus nationalen und EU-Vorschriften</span>

<ProRauchfreiLogo/>
<SlideRefs/>

<!-- 
Wo ist das Tabakwerbeverbot geregelt, welche Produkte werden erfasst und welche Werbeformen sind untersagt? Ist Sponsoring auch gesetzlich reguliert?

Angaben zum Verbot der Tabakwerbung finden sich in den Paragrafen 19-21 des Tabakerzeugnisgesetzes (TabakerzG). Nach dem Erwägungsgrund 43 der EU-Tabak-Richtlinie (RL 2014/40/EU) ist insbesondere für elektronische Zigaretten und Nachfüllbehälter ein restriktiver Ansatz in Bezug auf die Werbung zu verfolgen.

Die Werbeverbote gelten für Tabakerzeugnisse, E-Zigaretten und Nachfüllbehälter 
-->

---
layout: image-left
image: img/tobacco_ads_by_mistral_ai.jpg
---

# Verbotene Werbeformen  

Welche Werbeformen sind untersagt?

- <span v-click>**Hörfunk**</span>
- <span v-click>**Presse/gedruckte Erzeugnisse** (außer bestimmte Ausnahmen)</span>
- <span v-click>**Internet**</span>
- <span v-click>**Audiovisuelle Kommunikation** (Fernsehwerbung, Sponsoring, Produktplatzierung)</span>
- <span v-click>**Außenwerbung** (Plakate, Bildschirme)</span>
- <span v-click>**Werbung zugunsten von Unternehmen** (Hersteller/Verkäufer)</span>

<ProRauchfreiLogo/>
<SlideRefs/>

<!--
Verboten ist die Werbung

- im Hörfunk
- in der Presse oder in anderen gedruckten Erzeugnissen (außer die Veröffentlichungen richten sich ausschließlich an Mitarbeiter des Tabak- oder E-Zigarettenhandels oder sie wurden in einem Nicht-EU-Staat gedruckt und sind nicht hauptsächlich für den Markt in der EU bestimmt)
- in Diensten der Informationsgesellschaft (Internet)
- mit audiovisueller Kommunikation (d.h. durch Bilder mit oder ohne Ton; Beispiele: Fernsehwerbung, Sponsoring, Teleshopping und Produktplatzierung). Das Verbot gilt auch für Werbung zugunsten von Unternehmen, deren Haupttätigkeit die Herstellung oder der Verkauf dieser Erzeugnisse ist.
- in Form von Außenwerbung (Plakate, Aufsteller, Monitore), außer an den Außenflächen inklusive dazugehöriger Fensterflächen von Geschäftsräumen des Fachhandels. 

Verboten sind darüber hinaus werbliche Informationen für Tabakerzeugnisse, die

- den Eindruck erwecken, dass der Konsum der oben genannten Erzeugnisse gesundheitlich unbedenklich oder dazu geeignet ist, die Funktion des Körpers, die Leistungsfähigkeit oder das Wohlbefinden günstig zu beeinflussen
- Jugendliche oder Heranwachsende zum Konsum veranlassen oder sie darin bestärken
- das Inhalieren von Tabakrauch als nachahmenswert erscheinen lassen
- den Eindruck erwecken, die Inhaltsstoffe wären natürlich oder naturrein
-->
---
layout: image-right
image: img/money_by_craiyon_ai.webp
---

# Sponsoring-Regelungen  

Wann ist Sponsoring verboten?

- <span v-click>**Grenzüberschreitende Aktivitäten**:</span>
  - <span v-click>Mehrere EU-Mitgliedstaaten beteiligt</span>
  - <span v-click>Aktivitäten in mehreren EU-Ländern</span>
  - <span v-click>Andere grenzüberschreitende Wirkung</span>
- <span v-click>**Ausnahme**: Veranstaltungen in Deutschland allein</span>

<ProRauchfreiLogo/>
<SlideRefs/>

<!-- 

Verbot des Sponsorings von Veranstaltungen oder Aktivitäten, die zum Ziel haben, den Verkauf von Tabakerzeugnissen, E-Zigaretten oder Nachfüllbehältern direkt oder indirekt zu fördern; jedoch nur, wenn

- an der Aktivität oder Veranstaltung mehrere EU-Mitgliedstaaten beteiligt sind
- die Veranstaltung oder Aktivität in mehreren EU-Mitgliedstaaten stattfindet
- die Veranstaltung oder Aktivität eine sonstige grenzüberschreitende Wirkung hat.

Damit sind Veranstaltungen oder Aktivitäten, die sich auf Deutschland beschränken, von diesem Verbot ausgenommen. 

-->
---
layout: image-right
image: img/A_solitary_man_stands_in_the_center_of_a_vast__sunlit_open_field__surr_S524643_St20_G7.5_beschnitten.webp
---

# Ausnahmen und Graubereiche  

Was ist nicht verboten oder unklar?

- <span v-click>**Innenraumwerbung**: Nicht verboten, außer bei speziellen Fällen</span> 
- <span v-click>**Tabakerhitzer**: Füllungen sind verboten, Geräte selbst nicht</span>
- <span v-click>**Unklare Fälle**:</span>
  - <span v-click>Werbung an Schaufenstern in Einkaufszentren</span>
  - <span v-click>Werbung auf Abfallbehältern, Wurfzetteln, Fahrzeugen</span>
  - <span v-click>Produkttests in sozialen Medien</span>

<ProRauchfreiLogo/>
<SlideRefs/>

<!--
Werbung für Tabakerzeugnisse, E-Zigaretten oder Nachfüllbehälter in Innenräumen, soweit sie nicht den oben aufgezählten Verboten unterliegen, ist gesetzlich nicht geregelt und daher nicht verboten.
Probleme und nicht rechtlich geklärte Bereiche

- Tabakautomaten mit Werbeaufklebern oder -displays in Außenbereichen: Werbung an der Verkaufsstelle oder Außenwerbung? Nach der freiwilligen Selbstverpflichtung des BDTA von 1997 gegenüber dem Bundesgesundheitsministerium dürfen Tabakautomaten keine Werbung zeigen (gilt nicht für E-Zigaretten-Automaten)
- Was ist unter „Fachhandel“ zu verstehen? Obwohl Pro Rauchfrei 2020 eine Definition anmahnte; folgte der Gesetzgeber dem nicht. Laut den wissenschaftlichen Diensten des Bundestags ist „Fachhandel“ sehr eng zu verstehen als reiner Handel für Tabakerzeugnisse oder E-Zigaretten. Ein Graubereich sind die kleinen Presse-Lotto-Tabak-Läden vor, bei denen offensichtlich Tabakprodukte den größten Teil des Sortiments ausmachen. 
Bei Kiosks mit einem breiteren Warenangebot von Tabak, Zeitschriften, Getränken, Süßigkeiten, Eis und Snacks, bei Tankstellen, Lebensmittelläden oder anderen Läden mit breiterem Sortiment ist Außenwerbung für Tabakerzeugnisse, E-Zigaretten oder Nachfüllbehälter eindeutig gesetzwidrig. 
- Wie sind Tabakerhitzer einzustufen? Sie sind nicht explizit vom Werbeverbot erfasst, jedoch ihre Füllungen schon, nämlich unter dem nachträglich eingefügten Begriff „erhitzte Tabakerzeugnisse“. Tabakerhitzer sind ohne ihre Füllungen funktionslos und sind daher zumindest als indirekte Werbung für Tabakerzeugnisse anzusehen. 
- Noch ungeklärt: Ist Werbung an Schaufenstern von Nicht-Fachgeschäften innerhalb eines Einkaufszentrums Innen- oder Außenwerbung?
- Noch ungeklärt: Werbung in Form von massenweise verteilten Wurfzetteln, Werbung auf Fahrzeugen, Sonnenschirmen, Abfallbehältern, Stühlen, Aschenbechern, Gläsern: Alle diese Werbeformen werden reichlich genutzt.
- Sind „Produkttests“ oder Ankündigungen neuer Produkte in Zeitschriften online oder offline, in Influencer-Videos oder in den sozialen Medien: neutrale Kundeninformation oder Werbung?

Bei allen diesen Fragen ist anzumerken, dass Gerichte bisher das Tabakwerbeverbot immer sehr weitgehend ausgelegt haben, gemäß der Formulierung in § 2 Nr. 5 des Tabakerzeugnisgesetzes, das Werbung definiert als: „jede Art kommerzieller Kommunikation mit dem Ziel oder mit der direkten oder indirekten Wirkung, den Verkauf eines Erzeugnisses zu fördern“

ABER: Sei es verbotene Außenwerbung oder nicht eindeutig geklärter Graubereich: Die Tabak- und E-Zigarettenbranche verstößt täglich massenhaft gegen bestehende gesetzliche Regelungen, dehnt Ausnahmen von Werbeverboten bis über ihre Grenzen hinaus aus und interpretiert nicht explizit formulierte Werbeformen als erlaubt. 

Aufgrund mangelnder Umsetzung greifen die Tabakwerbeverbote daher kaum: Statt mit Großplakaten an Straßen, Haltestellen und Gebäudewänden haben wir es heute mit Kundenstoppern, Schaufensterplakaten, digitalen Displays und Monitoren in Tausenden von Verkaufsstellen zu tun. Diese Werbeformen sind häufig so angebracht, dass sie durch die Schaufenster und Türen nach außen wirken und sind daher als Außenwerbung einzustufen. Pro Rauchfrei hat bereits Supermärkte, Tankstellen, Kiosks und weitere Verkaufsstellen wegen Tabakaußenwerbung abgemahnt und wird das weiterhin tun.  

-->
---
layout: center
hideInToc: true
---

# Beispiele für nicht verbotene Werbung  

Nicht alle Werbeformen für Tabak- und Nikotinprodukte sind verboten.

<ProRauchfreiLogo/>
<SlideRefs/>

---
src: ./pages/beispiele/tabakwerbung/03_nicht_verboten/01_innenraeume.md
layout: image-left
image: img/beispiele/tabakwerbung/03_nicht_verboten/01_Tabakpräsentation-und-werbung-in-Edeka-Ebersberg_bearbeitet.webp
level: 2
hideInToc: true
---

---
layout: center
---

# Beispiele für rechtlich unklare Formen  

Graubereiche bei der Werbung für Tabak- und Nikotonprodukte bleiben zunächst offen.

<ProRauchfreiLogo/>
<SlideRefs/>

---
src: ./pages/beispiele/tabakwerbung/02_ungeklärt/01_sonnenschirme.md
layout: image-left
image: img/beispiele/tabakwerbung/02_ungeklärt/01_Köln-Sonnenschirm-Gauloises_klein.jpg
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/02_ungeklärt/02_abfallbehälter.md
layout: image-right
image: img/beispiele/tabakwerbung/02_ungeklärt/02_2024-20-07_Werbung-auf-Abfallbehälter-Stuttgart_klein.jpg
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/02_ungeklärt/03_branding.md
layout: image-left
image: img/beispiele/tabakwerbung/02_ungeklärt/03_Vuse5.jpg
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/02_ungeklärt/04_wurfzettel.md
layout: image-right
image: img/beispiele/tabakwerbung/02_ungeklärt/04_wurfzette_beschnittenl.png
level: 2
hideInToc: true
---


---
layout: center
---

# Beispiele für verbotene Außenwerbung  

Es folgen konkrete Beispiele für verbotene Tabak- und Nikotin-**Außenwerbung**.

<ProRauchfreiLogo/>
<SlideRefs/>

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/01_digitaldisplay.md
hide: false
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/01_Veni1_beschnitten.webp
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/02_schaufensterplakat.md
layout: image-right
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/02_LycaMobil_Elbar-Plakat_beschnitten.webp
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/03_tankstelle.md
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/03_Werbeplakat-E-Zigarette-Ingolstadt_beschnitten.jpg
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/04_tuerdisplay_krailing.md
layout: image-right
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/04_Türwerbung-Tankstelle-Krailling_beschnitten.webp
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/05_tankstelle_erfurt.md
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/05_2024-08-31_Tankstelle-Erfurt_Türdisplay4_beschnitten.webp
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/06_digitale_city_lights.md
layout: image-right
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/06_Tabak-Ploom-Düsseldorf_bearbeitet.webp
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/07_digitaldisplay_tankstellenshop.md
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/07_Mühldorf_VuseGo_bearbeitet.webp
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/08_saltswitch.md
layout: image-right
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/08_saltswitch_bearbeitet.png
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/09_outlet.md
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/09_popup_outlet_hervorgehoben.jpg
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/10_werbeschilder_bahnhofsgebaeude.md
layout: image-right
image: img/beispiele/tabakwerbung/01_verboten/01_aussenwerbung/10_Werbeschilder-Aulendorf_beschnitten.jpg
level: 2
hideInToc: true
---


---
layout: center
---

# Beispiele für verbotene Onlinewerbung  

Im Folgenden werden konkrete Beispiele für verbotene Tabak- und Nikotin-**Onlinewerbung** gezeigt.

<ProRauchfreiLogo/>
<SlideRefs/>

---
src: ./pages/beispiele/tabakwerbung/01_verboten/02_online/01_werbebanner.md
hide: false
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/02_online/01_2025-06-17_Werbebanner-Onlineshop_beschnitten.png
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/02_online/02_popup.md
hide: false
layout: image-right
image: img/beispiele/tabakwerbung/01_verboten/02_online/02_popup_beschnitten.png
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/02_online/03_facebook.md
hide: false
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/02_online/03_Werbereel-Facebook.png
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/02_online/04_tiktok.md
hide: false
layout: image-right
image: img/beispiele/tabakwerbung/01_verboten/02_online/04_tiktok-beste-vape2.jpg
level: 2
hideInToc: true
---

---
src: ./pages/beispiele/tabakwerbung/01_verboten/02_online/05_vergleichsseiten.md
hide: false
layout: image-left
image: img/beispiele/tabakwerbung/01_verboten/02_online/05_Werbung-Vergleichsseite-mit-Links.png
level: 2
hideInToc: true
---

---
layout: image-right
image: img/A_fantasy_army_charging_a_dragon_that_is_smoking_a_big_cigar_with_reli_S122138858_St40_G7.5_beschnitten.webp
---

# Herausforderungen und Nicht-Einhaltung  

Probleme bei der Umsetzung

- Massenhafte Verstöße der Branche  
- Ausdehnung von Ausnahmen (z. B. Innenraumwerbung)  
- Unklare Formen (z. B. Branding, Wurfzettel)  

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: center
class: text-center
---

# Zusammenfassung  

Kernpunkte

- Klare rechtliche Grundlagen (TabakerzG, EU-Richtlinien)  
- Umfassende Verbotsliste (Hörfunk, Internet, Sponsoring)  
- Ausnahmen und Graubereiche (Innenraum, Tabakerhitzer)  
- Aktuelle Probleme: Nicht-Einhaltung, unklare Formen  

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: center
class: text-center
---

# Vielen Dank für die Aufmerksamkeit!

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />

<ProRauchfreiLogo/>
<SlideRefs/>

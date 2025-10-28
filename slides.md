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
---

# Was darf Tabakwerbung?

Eine Übersicht des Vereins Pro Rauchfrei e.V.

<div class="mute">
Inhalt: Dipl.-Jur. Stephan Weinberger, Zusammenstellung: Barbara Soukup-Sterl, Produktion: Rene Schmidt
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

<!--
Here is another comment.
-->
<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: two-cols
layoutClass: gap-36
hideInToc: true
---

# Übersicht über die Präsentation

In dieser Präsentation stelle ich vor, welche Tabakwerbung erlaubt ist und welche nicht.

::right::

<Toc text-sm minDepth="1" maxDepth="2" />

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: image-right
image: https://cover.sli.dev
---

# Fragestellungen

Wo ist das Tabakwerbeverbot geregelt, welche Produkte werden erfasst und welche Werbeformen sind untersagt? Ist Sponsoring auch gesetzlich reguliert?

- Rechtliche Grundlagen  
- Gegenstand des Verbots  
- Verbotene Werbeformen  
- Sponsoring-Regelungen  
- Ausnahmen und Graubereiche  

Die Präsentation soll diese Fragen beantworten.

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: image-right
image: https://cover.sli.dev
---

# Rechtliche Grundlagen

Gesetze und Richtlinien

- **Tabakerzeugnisgesetz (TabakerzG)**: Paragraphen 19–21  
- **EU-Tabak-Richtlinie (RL 2014/40/EU)**: Erwägungsgrund 43 (elektronische Zigaretten)  
- **Bundesrecht und EU-Richtlinien**: Kombination aus nationalen und EU-Vorschriften  

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: image-right
image: https://cover.sli.dev
---

# Verbotene Werbeformen  

Welche Werbeformen sind untersagt?

- **Hörfunk**  
- **Presse/gedruckte Erzeugnisse** (außer bestimmte Ausnahmen)  
- **Internet**  
- **Audiovisuelle Kommunikation** (Fernsehwerbung, Sponsoring, Produktplatzierung)  
- **Außenwerbung** (Plakate, Monitore)  
- **Werbung zugunsten von Unternehmen** (Hersteller/Verkäufer)  

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: image-right
image: https://cover.sli.dev
---

# Sponsoring-Regelungen  

Wann ist Sponsoring verboten?

- **Grenzüberschreitende Aktivitäten**:  
  - Mehrere EU-Mitgliedstaaten beteiligt  
  - Aktivitäten in mehreren EU-Ländern  
  - Andere grenzüberschreitende Wirkung  
- **Ausnahme**: Veranstaltungen in Deutschland allein  

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: image-right
image: https://cover.sli.dev
---

# Ausnahmen und Graubereiche  

Was ist erlaubt oder unklar?

- **Innenraumwerbung**: Nicht verboten, außer bei speziellen Fällen  
- **Tabakerhitzer**: Füllungen sind verboten, Geräte selbst nicht  
- **Unklare Fälle**:  
  - Werbung an Schaufenstern in Einkaufszentren  
  - Werbung auf Abfallbehältern, Wurfzetteln, Fahrzeugen  
  - Produkttests in sozialen Medien  

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: center
---

# Beispiele für verbotene Außenwerbung  

Es folgen konkrete Beispiele für verbotene Tabak- und Nikotin-**Außenwerbung**.

<ProRauchfreiLogo/>
<SlideRefs/>

---
src: ./pages/beispiele/tabakwerbung/verboten/aussenwerbung/01_digitaldisplay.md
hide: false
layout: image-left
image: public/img/beispiele/tabakwerbung/verboten/aussenwerbung/Veni1.JPG
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/aussenwerbung/02_schaufensterplakat.md
layout: image-right
image: public/img/beispiele/tabakwerbung/verboten/aussenwerbung/LycaMobil_Elbar-Plakat.jpg
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/aussenwerbung/03_tankstelle.md
layout: image-left
image: public/img/beispiele/tabakwerbung/verboten/aussenwerbung/Werbeplakat-E-Zigarette-Ingolstadt_beschnitten.jpg
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/aussenwerbung/04_tuerdisplay_krailing.md
layout: image-right
image: public/img/beispiele/tabakwerbung/verboten/aussenwerbung/Türwerbung-Tankstelle-Krailling_beschnitten.jpg
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/aussenwerbung/05_digitale_city_lights.md
layout: image-left
image: public/img/beispiele/tabakwerbung/verboten/aussenwerbung/2024-08-31_Tankstelle-Erfurt_Türdisplay4_beschnitten.jpg
level: 2
hideInToc: false
---

---
layout: center
---

# Beispiele für verbotene Onlinewerbung  

Im Folgenden werden konkrete Beispiele für verbotene Tabak- und Nikotin-**Onlinewerbung** gezeigt.

<ProRauchfreiLogo/>
<SlideRefs/>

---
src: ./pages/beispiele/tabakwerbung/verboten/online/01_werbebanner.md
hide: false
layout: image-left
image: public/img/beispiele/tabakwerbung/verboten/online/2025-06-17_Werbebanner-Onlineshop_beschnitten.png
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/online/02_popup.md
hide: false
layout: image-right
image: public/img/beispiele/tabakwerbung/verboten/online/popup_beschnitten.png
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/online/03_facebook.md
hide: false
layout: image-left
image: public/img/beispiele/tabakwerbung/verboten/online/Werbereel-Facebook.png
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/online/04_tiktok.md
hide: false
layout: image-right
image: public/img/beispiele/tabakwerbung/verboten/online/tiktok-beste-vape2.jpg
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/verboten/online/05_vergleichsseiten.md
hide: false
layout: image-left
image: public/img/beispiele/tabakwerbung/verboten/online/Werbung-Vergleichsseite-mit-Links.png
level: 2
hideInToc: false
---

---
layout: center
---

# Rechtlich ungeklärte Formen  

Graubereiche bei der Werbung für Tabak- und Nikotonprodukte bleiben zunächst offen.

<ProRauchfreiLogo/>
<SlideRefs/>

---
src: ./pages/beispiele/tabakwerbung/ungeklärt/01_sonnenschirme.md
layout: image-left
image: public/img/beispiele/tabakwerbung/ungeklärt/Köln-Sonnenschirm-Gauloises.jpg
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/ungeklärt/02_abfallbehälter.md
layout: image-right
image: public/img/beispiele/tabakwerbung/ungeklärt/2024-20-07_Werbung-auf-Abfallbehälter-Stuttgart.jpg
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/ungeklärt/03_branding.md
layout: image-left
image: public/img/beispiele/tabakwerbung/ungeklärt/Vuse5.jpg
level: 2
hideInToc: false
---

---
src: ./pages/beispiele/tabakwerbung/ungeklärt/04_wurfzettel.md
layout: image-right
image: public/img/beispiele/tabakwerbung/ungeklärt/wurfzette_beschnittenl.png
level: 2
hideInToc: false
---


---
layout: image-right
image: https://cover.sli.dev
---

# Nicht verbotene Werbung  

Erlaubte Werbeformen

- Werbung in Innenräumen (z. B. Supermärkte)  
- **Beispiel**: Tabakpräsentation in Edeka (Ebersberg)  

<ProRauchfreiLogo/>
<SlideRefs/>

---
layout: image-right
image: https://cover.sli.dev
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

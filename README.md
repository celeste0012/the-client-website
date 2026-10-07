# The Client - Website

Ontwerp en maak een website voor een opdrachtgever waarbij de iconen makkelijk bereikbaar en te downloaden/kopiëren zijn.
De website moet ook responsive en toegankelijk zijn.

Hier is de website: https://celeste0012.github.io/the-client-website/


## Inhoudsopgave Readme

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Voor iedereen die rechtenvrije iconen wil is deze website gemaakt, met iconen en illustraties die rechtenvrij zijn.
De pagina is responsive en is Mobile first ontworpen en gemaakt. 

### Hier is de pagina op pc:
<img width="1847" height="915" alt="afbeelding" src="https://github.com/user-attachments/assets/99f6c4cc-f56c-4020-816c-ef32765f8ca3" />
<img width="1857" height="921" alt="afbeelding" src="https://github.com/user-attachments/assets/bf99a3b5-4c19-4dee-a03c-98d79a48ad61" />
<img width="1837" height="236" alt="afbeelding" src="https://github.com/user-attachments/assets/fa319c82-465a-4ff7-8e38-9d6b19770b47" />


### Hier is de pagina op mobiel:

<img width="312" height="845" alt="afbeelding" src="https://github.com/user-attachments/assets/68c24213-bc2b-4f84-983c-ab2614919433" />
<img width="312" height="861" alt="afbeelding" src="https://github.com/user-attachments/assets/661d59e7-7f8d-4387-8a9b-7c3769dcf5d9" />
<img width="312" height="556" alt="afbeelding" src="https://github.com/user-attachments/assets/22162eaf-5bd6-4300-a6b1-239afdd428f1" />

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framework of library gebruikt? -->
De website is gebouwd met HTML en CSS.

### HTML
In de main is een search-bar, deze heb ik zo gemaakt:
```html
            <form>
                <search>
                    <span class="search-icon material-symbols-outlined"> search</span>
                    <input class="search-input" type="search" placeholder="Zoek naar een icoon...">
                </search>
            </form>
```

Ik heb een variatie selector gemaakt met deze code:
```html
            <p>
                <select name="variant">
                    <option>Regular</option>
                    <option>Line</option>
                    <option>Fill</option>
                    <option>Diapositive</option>
                </select>
            </p>
```

### CSS
De h1 heeft een media query met een clamp erin om de tekst vanaf een bepaalde grootte mee te laten bewegen en op een bepaalde grootte te stoppen met groeien.
In de grid met de iconen zijn een hoop media queries, vanaf 360px met stappen van 120px tot en met 1200px.

Er is ook een focus-within voor de search als je erop klikt.

## Bronnen
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/clamp

https://www.codecenter.nl/tryit/html/ex/form_keuzelijsten1

https://www.youtube.com/watch?v=f6ocDCkCmhM

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

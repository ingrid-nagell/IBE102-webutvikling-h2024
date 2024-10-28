# IBE102: Oblig 1, 6.okt 2024
Levert av: Ingrid Nagell

Utgangspunkt for denne oblig'en er er HTML text fundamentals (https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals), der vi skal markere oppskriften på hummus.

## Del 1: utføring
Jeg startet med å sette opp et html dokument (lagret lokalt med navn index.html) fra html template i VSCode. Denne templaten inneholder en head-seksjon og en body-seksjon.
Videre er dette prosessen jeg utførte:
* Fanetittel legges inn i: head-elementet > title-elementet: "Ingrid's recipes"
* Jeg starter med et enkelt oppsett, slik utgangspunktet er satt opp på mozilla sine sider: Oppskriftsteksten kopieres inn i body-elementet.

### Strukturering:
All teksten er på en linje i programmet, så jeg starter med å dele opp teksten i mitt program over flere linjer, slik det framstår som logisk å splitte opp. Dermed blir det enklere å legge på strukturelementer. Det er viktig å også legge på struktur iform av html-elementer, slik at når siden rendres så blir det bedre leselighet for leseren.

h1-tittel: Den første delen av teksten, "Quick hummus recipe", ser ut til å være tittelen. Jeg legger inn sidetittel, ett h1-element over teksten som forklarer leseren hva denne siden handler om. Det gir leseren et tydelig og rask forståelse for hvilken informasjon denne nettsiden innholder og forteller nettleseren hva sidetittelen er (for søkeoptimalisering feks.).

h2-titler: Denne legger jeg inn flere av. Fra teksten identifiserer jeg følgende passende undertitler:
    * "Ingredients"
    * "Instructions"
    * "Storage"

Paragrafer: Teksten som ikke passer inn i tittel-elementene legger jeg i p-elementer som følger h1/h2-elementene. Der det er naturlig deler jeg teksten i flere paragraf-elementer (og verifiserer mot fasiten).

Lister: I paragrafen som kommer etter h2-tittlene "Ingredients" så legger jeg inn en usortert liste (ul) med nestede liste-elmenter (li). Hele ul-elementet legges inne i p-elementet. Det gjøre det mulig for leseren å få rask oversikt over hva de trenger for å lage hummus. Det samme gjør jeg for instruksjonene, men her viser fasiten at det skal være en nummerert liste (ol) istedenfor. Dette antar jeg å være fordi man ønsker at leseren utfører instruksjonene i en gitt rekkefølge.

## Del 2: Drøfting
Jeg synes det er litt vanskelig å avgjøre hvorvidt man skal ha "nestede" elementer eller ikke. Jeg la initielt ul/ol listene inne i p-elementer, men i følge fasiten trengte man ikke det. Visuelt så det likt ut ut ifra det jeg kan se.

Eller synes jeg struktur-hierarkiet er greit å forstå på en grunnleggende nivå.

Jeg antar at styling med CSS ville kunne gjøre siden mer innbydende, men innholdet er jo egentlig veldig lett å se når man har strukturert det på denne måten med kun header, paragrafer og lister, og svart skrift på hvit bakgrunn, og lik font for hele siden.

Jeg kan ikke så mye om søkeoptimalisering eller universellutforming enda, men jeg regner med man kunn brukt mye tid på å optimalisere nettsiden for å optimalisere ift slike ting også.

Jeg testet tilslutt openAI/chatGPT, slik det sto i øvelsen. Jeg limte inn koden fra index.html og spurte om den med kort tekst kan komme med forbedringsforslag.

Svaret jeg fikk:
Your HTML code is quite good, but here are some suggestions for improvement:

1. **Accessibility Enhancements**:
   - Add `alt` attributes to any images (if added later) for screen readers.
   - Use more descriptive headings (like "Quick Hummus Recipe" instead of just "Instructions").

2. **Meta Tags**:
   - Include a meta description for better SEO. E.g., `<meta name="description" content="A quick and easy hummus recipe perfect for salads and snacks.">`.

3. **Semantic HTML**:
   - Consider using `<section>` tags to organize content better.
   - Use `<footer>` for any additional notes or copyright information.

4. **Lists**:
   - Consider adding a brief introduction to the ingredients and instructions sections to provide context.

5. **Styling**:
   - Ensure that your CSS file includes styles for improved typography and spacing for better readability.

6. **Code Structure**:
   - Maintain consistent indentation for better readability.

7. **Linking**:
   - If you reference other recipes or related content, consider adding hyperlinks.

Here's a revised structure with some of these suggestions:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <meta name="description" content="A quick and easy hummus recipe perfect for salads and snacks.">
    <title>My Recipes</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <h1>Quick Hummus Recipe</h1>
    <section>
        <p>This recipe makes quick, tasty hummus, with no messing. It has been adapted from a number of different recipes that I have read over the years.</p>
        <p>Hummus is a delicious thick paste used heavily in Greek and Middle Eastern dishes. It is very tasty with salad, grilled meats, and pitta breads.</p>
    </section>

    <section>
        <h2>Ingredients</h2>
        <ul>
            <li>1 can (400g) of chick peas (garbanzo beans)</li>
            <li>175g of tahini</li>
            <li>6 sundried tomatoes</li>
            <li>Half a red pepper</li>
            <li>A pinch of cayenne pepper</li>
            <li>1 clove of garlic</li>
            <li>A dash of olive oil</li>
        </ul>
    </section>

    <section>
        <h2>Instructions</h2>
        <ol>
            <li>Remove the skin from the garlic and chop coarsely.</li>
            <li>Remove all seeds and stalk from the pepper, and chop coarsely.</li>
            <li>Add all the ingredients into a food processor.</li>
            <li>Process all the ingredients into a paste.</li>
            <li>For a coarse "chunky" hummus, process it for a short time.</li>
            <li>For smooth hummus, process it longer.</li>
        </ol>
    </section>

    <section>
        <p>For a different flavor, experiment by blending in lemon, coriander, chili pepper, lime, chipotle, harissa, mint, or spinach with feta cheese.</p>
    </section>

    <section>
        <h2>Storage</h2>
        <p>Refrigerate the finished hummus in a sealed container. Use within a week; discard if fizzy.</p>
        <p>Hummus can be frozen; thaw and use within a couple of months.</p>
    </section>

</body>
</html>
```

These changes enhance accessibility, readability, and organization!

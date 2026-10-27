# Activitat backgroud i imatges
## Pràctica: Web Oficial del Club Atlètic Mont-roig

<img width="445" height="449" alt="image" src="https://github.com/user-attachments/assets/d1d724e7-16bc-4c85-8a6a-0aa812f2b132" />

### Context del Projecte
El club de futbol local **Club Atlètic Mont-roig** està renovant la seva pàgina web oficial. T'han encarregat dissenyar la secció informativa del club utilitzant **5 targetes visuals** (`div`) que mostrin diferents blocs d'informació de l'equip. 

Per mantenir la identitat de marca, **totes les targetes han de tenir exactament la mateixa mida, forma, vora (border-radius) i ombra (box-shadow)**, però cadascuna ha d'utilitzar una tècnica visual de fons diferent segons el contingut que mostra.

---

## Guia d'Estil Uniforme (Estructura Base)

Tots 5 elements `div` han de compartir una mateixa línia estètica:
* **Amplada:** Adaptada al contenidor principal (són a dins d'un altre div) (amb un màxim de 800px centrats a la pantalla).
* **Marcs i Vores:** Tots els blocs han de tenir la mateixa vora suau i les cantonades arrodonides.
* **Efecte de relleu:** Una ombra inferior idèntica a cada targeta per donar sensació de profunditat.
* **Espai interior:** Marginació suficient perquè el text no toqui les vores ni tapis els motius de fons.

---

## Les 5 Targetes del Club

Cadascuna de les 5 caixes ha d'incloure un títol `<h2>` i un paràgraf `<p>` amb la informació corresponent:

1. **Targeta 1: Fitxa del Capità (Color Corporatiu)**
   * **Contingut:** Nom i dades del capità de l'equip.
   * **Fons:** Un color blau marí sòlid definit mitjançant el seu codi hexadecimal de 6 dígits.

2. **Targeta 2: L'Estadi i la Gespa (Textura de Fons)**
   * **Contingut:** Informació sobre el camp de futbol i la capacitat de l'afició.
   * **Fons:** Una imatge amb la textura de la gespa que cobreixi completament tota la targeta sense deformar-se, adaptant-se a l'espai disponible.

3. **Targeta 3: Motiu de Patrocinadors (Sanefa Horitzontal)**
   * **Contingut:** Agraïment als patrocinadors oficials de la temporada.
   * **Fons:** Un motiu o sanefa decorativa a la part superior que es repeteixi contínuament d'esquerra a dreta en una sola línia horitzontal.

4. **Targeta 4: Palmarès i Calendari (Línia Lateral Vertical)**
   * **Contingut:** Històric de partits i títols de la temporada.
   * **Mida especial:** Aquesta targeta ha de ser bastant més alta que les altres (més del doble) per encabir tot el text.
   * **Fons:** Una sanefa decorativa al marge esquerre que es repeteixi de dalt a baix al llarg de tot el lateral de la targeta.

5. **Targeta 5: Escut Oficial (Element Centrat Superior)**
   * **Contingut:** Història del fundador i valors del club.
   * **Fons:** L'escut oficial del club situat just a la part superior central de la caixa. S'ha de mostrar una sola vegada (sense repetir-se) i el text ha de començar a escriure's a sota de l'escut.

---
## Exemple targeta 1

<img width="916" height="216" alt="image" src="https://github.com/user-attachments/assets/c674fc06-5a90-4fd1-ae8c-342116e1e0e8" />

## Formats d'Entrega

Heu de presentar la secció de la web resolta en tres fitxers diferents segons la tecnologia d'estils utilitzada (CSS Extern, Intern i Inline):

* **`pagina1.html` + `estils.css`**: Fent servir un fitxer de full d'estils extern enllaçat i classes creades per a cada targeta.
* **`pagina2.html`**: Tots els estils inclosos dins del mateix document HTML a la secció de capçalera, utilitzant classes.
* **`pagina3.html`**: Tots els estils aplicats directament a l'etiqueta de cada element (estil en línia), sense utilitzar cap classe CSS.

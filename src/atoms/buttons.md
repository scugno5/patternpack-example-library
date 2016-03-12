---
title: Buttons
---
## Buttons
Per quanto riguarda gli <b>Ancor Tags come immagini</b>, come riportato dal codice in basso ho creato un immagine da utilizzare come link. Mi rendo conto che per impostare i diversi stati ( active, hover, ecc....) dovrei creare del files js appositi. Non mi sembra una soluzione molto pratica.

Per quanto riguarda invece gli <b>Anchor Tags che usano classi con immagini e bottoni in CSS</b> posso dire che li trovo molto più pratici per eventuali animazioni ed interattività.
Ci ho speso sopra parecchio tempo per entrare in molte dinamiche, ma il risultato a mio parere garantisce più flessibilità.

Per questi ultimi mi sono anche concesso di sperimentare un semplice stato <b>:hover</b>

### Examples
<div class="library__example">
<h4>Anchor Tag come immagini</h4>
<p>Logo HiRes</p>
<a><img class="" src="../assets/images/Filled/HiRes_Black.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_Blue.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_BlueLi.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_Green.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_GreenLi.svg" width="100" height="40"></a>

<p>Logo NoGrid</p>
<a><img class="" src="../assets/images/Filled/NoGrid_Black.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_Blue.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_BlueLi.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_Green.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_GreenLi.svg" width="100" height="40"></a>

<p>Logo NoBack</p>
<a><img class="" src="../assets/images/Filled/NoBack_Black.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_Blue.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_BlueLi.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_Green.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_GreenLi.svg" width="100" height="40"></a>

<h4>Anchor Tag con classe bottone e immagine</h4>
<p>Logo HiRes</p>
<a class="btn Bla-Primo" href="#">Cliccami</a>
<a class="btn B-Primo" href="#">Cliccami</a>
<a class="btn Bl-Primo" href="#">Cliccami</a>
<a class="btn G-Primo" href="#">Cliccami</a>
<a class="btn Gl-Primo" href="#">Cliccami</a>

<p>Logo NoBack</p>
<a class="btn Bla-Secondo" href="#">Cliccami</a>
<a class="btn B-Secondo" href="#">Cliccami</a>
<a class="btn Bl-Secondo" href="#">Cliccami</a>
<a class="btn G-Secondo" href="#">Cliccami</a>
<a class="btn Gl-Secondo" href="#">Cliccami</a>

<p>Logo NoGrid</p>
<a class="btn Bla-Terzo" href="#">Cliccami</a>
<a class="btn B-Terzo" href="#">Cliccami</a>
<a class="btn Bl-Terzo" href="#">Cliccami</a>
<a class="btn G-Terzo" href="#">Cliccami</a>
<a class="btn Gl-Terzo" href="#">Cliccami</a>

</div>



### Code
```html
<h4>Anchor Tag come immagini</h4>
<p>Logo HiRes</p>
<a><img class="" src="../assets/images/Filled/HiRes_Black.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_Blue.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_BlueLi.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_Green.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/HiRes_GreenLi.svg" width="100" height="40"></a>

<p>Logo NoGrid</p>
<a><img class="" src="../assets/images/Filled/NoGrid_Black.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_Blue.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_BlueLi.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_Green.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoGrid_GreenLi.svg" width="100" height="40"></a>

<p>Logo NoBack</p>
<a><img class="" src="../assets/images/Filled/NoBack_Black.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_Blue.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_BlueLi.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_Green.svg" width="100" height="40"></a>
<a><img class="" src="../assets/images/Filled/NoBack_GreenLi.svg" width="100" height="40"></a>

<h4>Anchor Tag con classe bottone e immagine</h4>
<p>Logo HiRes</p>
<a class="btn Bla-Primo" href="#">Cliccami</a>
<a class="btn B-Primo" href="#">Cliccami</a>
<a class="btn Bl-Primo" href="#">Cliccami</a>
<a class="btn G-Primo" href="#">Cliccami</a>
<a class="btn Gl-Primo" href="#">Cliccami</a>

<p>Logo NoBack</p>
<a class="btn Bla-Secondo" href="#">Cliccami</a>
<a class="btn B-Secondo" href="#">Cliccami</a>
<a class="btn Bl-Secondo" href="#">Cliccami</a>
<a class="btn G-Secondo" href="#">Cliccami</a>
<a class="btn Gl-Secondo" href="#">Cliccami</a>

<p>Logo NoGrid</p>
<a class="btn Bla-Terzo" href="#">Cliccami</a>
<a class="btn B-Terzo" href="#">Cliccami</a>
<a class="btn Bl-Terzo" href="#">Cliccami</a>
<a class="btn G-Terzo" href="#">Cliccami</a>
<a class="btn Gl-Terzo" href="#">Cliccami</a>

```



// issikvieciam serveri
// npm init -y // package.json susigeneruoji
// npm instal -D dead-server    ---- servo instalas
*/"dev": "dead-server --host=localhost --port=5506",

touch git init
.gitignore
git add . (surenka viska talpinant i git)
git commit -m "New project astronout" (commitas ir zinute)
git push

node_modules
.vscode
.DS_store 


<!-- 
style="savybe: reiksme; kita-savybe1: reiksme1;"

Visos tekstines stiliauss savybes gali buti paveldimos (tevines - vaikines)

Matavimo vienetai:
reliatyvus: %, em, vh, vw, fr
absoliutus: px (pikselis), rem, ch

display: none;          elementas nera rodomas;
display: block;         didzioji dalis elementu; deliojimas yra vertikaliai, ir uzima kiek gali daugiau plocio
display: inline;        elgiasi kaip tekstas
display: inline-block;  elementas yra kompaktiskiausio/minimalaus plotcio, bet ne didesnis nei tevinis elementas

width: 100%;            tevinio elemento plocio atzvilgiu... bus per visa tevini elementa.
height: 50px;           aukstis dazniausiai nereguoja i % reiksmes (nereguoja i %)


padding: 10px;          atstumas tarp elemento krasto (border) ir jo turinio (teksto) visomis kriptimis
padding-top: 10px       i virsu ir visi kiti.

margin: 10px;           atstumas tarp elementu; visomis kryptimis vienodai
margin-top: 10px;       atstumas top
magin-bottom: 10px;     atstumas bot
margin-left             kaire
margin-rigth            desine

float: left;            priverstinis elemento stumimas pasirinkta kryptimi iki artimiausio kito elemento arba tevinio krasto
float: right;           priverstinis elemento stumimas pasirinkta kryptimi iki artimiausio kito elemento arba tevinio krasto

background-color: red;  backgroundo spalvos -- elemento fono spalva
color: black;           teksto spalvos

font-family: Arial;     konkretus sriftai
font-size: 20px;        teksto dydis
font-weight: bold;      paryskintos spalvos
font-style: italic;  

line-height: 1.2em;     linijos aukstis

text-transform: uppercase;
text-decoration: underline;
text-decoration: none;
text-align: center;     tekstas centruojamas

SPALVOS:
rgb(235, 236, 238)
 #ebecee -- sesioliktainis kodas 
 eb = 235, ec = 236, ee = 238
-->



<!-- a:nth-child(3), trecias parinktas
a:nth-child(2) {    antras parinktas ir tt
    background-color: red;
}  
a:nth-child(n + 2) {
    background-color: red;
} 
a:nth-child(2n) {
    background-color: red;
} 
a:nth-child(odd) {  lyginis - nelyginis (kasantra paima)
    background-color: red;
}  -->

<!-- a:nth-of-type() - ieman nuoroda ir ja keicia -->
<html>
<head>
<style> 

.dropbtn {
    margin-bottom: 1rem;
    background-color: rgba(255, 255, 255, 0.08);
    color: rgba(255, 255, 255, 0.7);
    border-color: rgba(255, 255, 255, 0.2);
    border-style: solid;
    border-width: 1px;
    border-radius: 0.3rem;
    transition: color 0.2s, background-color 0.2s, border-color 0.2s;
    cursor: pointer;
    padding: 0.75rem 1rem; 
}  

.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: rgba(105, 216, 243, 0.2);
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
    border-color: rgba(255, 255, 255, 0.2);
    border-style: solid;
    border-width: 1px;
    border-radius: 0.3rem;
    padding: 0.75rem 1,5rem;
    width: 100%
} 

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {
    background-color: rgba(105, 216, 243, 0.2);
    border-color: rgba(255, 255, 255, 0.2);
    border-style: solid;
    border-width: 1px;
    border-radius: 0.3rem;

}

.dropdown:hover .dropdown-content {
    display: block;
    padding: 0.75rem 1rem;
}

.dropdown:hover .dropbtn {
    color: rgba(255, 255, 255, 0.8);
    text-decoration: none;
    background-color: rgba(255, 255, 255, 0.2);
    border-color: rgba(255, 255, 255, 0.3);
}


.section-accueil {
	display: flex;
	flex-direction: row;
	min-height: calc(100vh-150px);
	min-width: 100vh;
}

#accueil {
       background-color: rgb(255, 124, 109);
}

#accueil p {
    color: black;
}

#introduction {
       background-color: rgb(44, 195, 161);
}

.newspaper {
    -webkit-column-count: 3; /* Chrome, Safari, Opera */
    -moz-column-count: 3; /* Firefox */
    column-count: 3;
    -webkit-column-gap: 30px; /* Chrome, Safari, Opera */
    -moz-column-gap: 30px; /* Firefox */
    column-gap: 30px;
    -webkit-column-rule-style: solid; /* Chrome, Safari, Opera */
    -moz-column-rule-style: solid; /* Firefox */
    column-rule-style: solid;
    -webkit-column-rule-width: 1px; /* Chrome, Safari, Opera */
    -moz-column-rule-width: 1px; /* Firefox */
    column-rule-width: 1px;
    -webkit-column-rule-color: lightblue; /* Chrome, Safari, Opera */
    -moz-column-rule-color: lightblue; /* Firefox */
    column-rule-color: lightblue;


#sommaire {
  background-color: white;
}


#tonextsection img {
	width: 10vmin;
	height: 10vmin;
	margin-top: 3vmin;
}

</style>
</head>
<body>

<div class="main">
<article class="article">

<div id="accueil" class="section-accueil">

<h1 style="text-align:center;" > Dans quelle mesure les perturbateurs endocriniens ont-ils remis en question la réglementation sanitaire basée sur les principes traditionnels de la science ? </h1>

<p>"La question des perturbateurs endocriniens est une question majeure de santé publique."François Veillerette, fondateur de l'association Générations Futures</p>

<a data-scroll id="tonextsection" href="https://controverses.github.io/perturbateurs-endocriniens/#introduction"><p text-align="center"><img src="arrow.png"></p></a>


</div>

<div id= "introduction" class="section-accueil" >
  <h1 style="text-align:center;">Introduction</h1><br>
  
  <div class="newspaper" align="justify">
  Les perturbateurs endocriniens sont des substances chimiques d’origine naturelle ou anthropologique (issues des activités humaines) qui viennent interférer avec le système endocrinien des animaux et des Hommes, c’est-à-dire l’ensemble des organes qui sécrètent et régulent les hormones de l’organisme. Les hormones sont des molécules destinées à  transmettre des messages chimiques à l’organisme afin d’assurer son bon fonctionnement, celles-ci sont principalement transportées par la circulation sanguine. Ainsi, les perturbateurs endocriniens en imitant, en bloquant ou en perturbant l’action des hormones naturelles peuvent avoir des effets néfastes sur l’organisme et provoquer des anomalies métaboliques ou comportementales. Les hormones sont des molécules qui agissent à très faibles doses et ainsi, les perturbateurs endocriniens aussi ce qui en font des substances d’autant plus nocives. Avec le boom de l’industrie chimique des années 50 et l’explosion de notre utilisation de produits chimiques, les perturbateurs endocriniens sont aujourd’hui présents dans tous les écosystèmes de la planète et posent des problèmes importants tant pour les espèces animales que pour les Hommes. 
  
  </div>

<a data-scroll id="tonextsection" href="https://controverses.github.io/perturbateurs-endocriniens/#sommaire"><p text-align="center"><img src="arrow.png"></p></a>

</div>

<div id= "sommaire" class="section-accueil">

<img src="Schéma-STS.jpg" alt="Schéma-STS" style="hight:calc(100vh-150px); width:auto;" usemap="#sommairemap" >

<map name="sommairemap">
  <area shape="rect" coords="485,30,890,194" alt="Perturbateurs endocriniens" href="https://controverses.github.io/perturbateurs-endocriniens/scientifiqueaupublic.md/decouvertesscientifiques.html">
</map>

 
 </div>
   
</article>
</div>
</body>
</html>

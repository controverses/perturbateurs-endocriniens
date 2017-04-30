<html>
<head>
<style> 

.article {
    text-align: left;
}

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
    z-index: 1;
}  

.dropdown {
    position: relative;
    display: inline-block;
    z-index: 1;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: rgba(105, 216, 243, 0.2);
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    border-color: rgba(255, 255, 255, 0.2);
    border-style: solid;
    border-width: 1px;
    border-radius: 0.3rem;
    padding: 0.75rem 1,5rem;
    width: 100%;
} 

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {
    background-color: rgba(105, 216, 243, 0.2;
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
	min-height: 100vh;
}

#accueil {
        background-color: pink;
}

#accueil p {
    color: black;
}

#sommaire {
  background-color: white;
}

</style>
</head>
<body>

<div class="main">
<article class="article">

<div id="accueil" class="section-accueil">

<h1> Citations</h1>

<p>"La question des perturbateurs endocriniens est une question majeure de santé publique."François Veillerette, fondateur de l'association Générations Futures</p>

<a data-scroll id='tointroduction' href="https://controverses.github.io/perturbateurs-endocriniens/#introduction"><p text-align="center" style="width:50px;height:50px;"><img src="arrow.png"></p></a>

</div>

<div id= "introduction" class="section-accueil" >

  <h1>Introduction</h1>
  <p>Nous sommes six étudiantes du double cursus Sciences et Sciences Sociales entre SciencesPo et l'université Pierre et Marie Curie.</p>
  
  <p align="justify">
Dans notre corps, certains organes comme le pancréas, le rein ou la thyroïde sécrètent des hormones, qui sont des molécules destinées à agir sur d’autres organes en étant transportées par le sang. L’ensemble de ces organes compose le système endocrinien. Il est primordial car la sécrétion d’hormones permet de réguler notre métabolisme, notre croissance et notre reproduction. Aussi, il est à la base du fonctionnement de notre corps. Par exemple, l’insuline et le glucagon, deux hormones, agissent sur la régulation de la glycémie, l’adrénaline sur la contraction musculaire, les oestrogènes sur la reproduction, … En temps normal, il s’auto-régule : le taux de sécrétion d’une hormone est déterminé par d’autres hormones agissant en amont, la plupart du temps provenant du complexe hypothalamo-hypophysaire de notre cerveau, mais également par un rétrocontrôle des hormones sur lesquelles elle influe. </p> 

<a href="https://controverses.github.io/perturbateurs-endocriniens/#sommaire">Sommaire</a>

</div>

<div id= "sommaire" class="section-accueil">

<img src="Schéma-STS.pdf" alt="Schéma-STS" usemap="#sommairemap" style="min-width:100%;hight:auto;">

<map name="sommairemap">
  <area shape="rect" coords="45,195,140,430" alt="Biberon" href="http://social-sante.gouv.fr/sante-et-environnement/risques-microbiologiques-physiques-et-chimiques/article/bisphenol-a">
</map>
 
 </div>
   
</article>
</div>
</body>
</html>

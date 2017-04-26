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

.dropdown-content a:hover {background-color: rgba(105, 216, 243, 0.2)}

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

</style>
</head>

    <body>
        <header>
            <h1>Les Perturbateurs endocriniens</h1>
            <h2>Indicateur du logement sciences-piste idéal</h2>
            <p>Découvre ton quartier idéal selon tes propres critères</p>
            <div id='domains'>
                   <section class="page-header">
      <h1 class="project-name">{{ site.title | default: site.github.repository_name }}</h1>
      <h2 class="project-tagline">{{ site.description | default: site.github.project_tagline }}</h2>
      {% if site.github.is_project_page %}
       <div class="btn">
        <a href="https://controverses.github.io/perturbateurs-endocriniens/">Accueil</a>
       </div>
      
      <div class="dropdown">
          <button class="dropbtn">De l'espace scientifique au domaine public</button>
          <div class="dropdown-content">
            <a href="https://controverses.github.io/perturbateurs-endocriniens/scientifiqueaupublic.md/decouvertesscientifiques.html" >Découvertes scientifiques</a>
            <a href="https://controverses.github.io/perturbateurs-endocriniens/scientifiqueaupublic.md/santepublique.html" >Un problème de santé publique</a>
            <a href="https://controverses.github.io/perturbateurs-endocriniens/scientifiqueaupublic.md/debatpublic.html" >Émergence dans le débat public</a>
         </div>
    </div>
          
      <div class="dropdown">
         <button class="dropbtn">Les actions du gouvernement français</button>
         <div class="dropdown-content">
            <a href="https://controverses.github.io/perturbateurs-endocriniens/gouvernementfrancais.md/reglementation.html" >Réglementation</a>
            <a href="https://controverses.github.io/perturbateurs-endocriniens/gouvernementfrancais.md/recherches.html" >Programme de recherches</a>
            <a href="https://controverses.github.io/perturbateurs-endocriniens/gouvernementfrancais.md/unioneuropeenne.html" >Influence sur l'UE</a>
         </div>
      </div>
      
       <div class="dropdown">
         <button class="dropbtn">Une législation difficile</button>
         <div class="dropdown-content">
           <a href="https://controverses.github.io/perturbateurs-endocriniens/legislationdifficile.md/lobbies.html">Les lobbies</a>
           <a href="https://controverses.github.io/perturbateurs-endocriniens/legislationdifficile.md/gouvernementfrancais.html">Gouvernement Français</a>
           <a href="https://controverses.github.io/perturbateurs-endocriniens/legislationdifficile.md/definition.html">Définition</a>
           <a href="https://controverses.github.io/perturbateurs-endocriniens/legislationdifficile.md/solutions.html">Solution</a>
          </div>
       </div>
      
        <div class="dropdown">
         <button class="dropbtn">Tous concernés ?</button>
         <div class="dropdown-content">
           <a href="https://controverses.github.io/perturbateurs-endocriniens/legislationdifficile.md/lobbies.html">Comment s'en protéger ?</a>
           <a href="https://controverses.github.io/perturbateurs-endocriniens/legislationdifficile.md/gouvernementfrancais.html">Substitus ou suppression </a>
           <a href="https://controverses.github.io/perturbateurs-endocriniens/legislationdifficile.md/definition.html">Peut-on s'en passer ? </a>
          </div>
       </div>
   
      {% endif %}
      {% if site.show_downloads %}
        <a href="{{ site.github.zip_url }}" class="btn">Download .zip</a>
        <a href="{{ site.github.tar_url }}" class="btn">Download .tar.gz</a>
      {% endif %}
    </section>

            </div>
            <a data-scroll id='toIntroduction' href="#introduction"><p align="center"><img src="arrow.png"></p></a>
        </header>
        <div id='Introduction'>
            <article class="article">

  <h1>Introduction</h1>
  <p>Nous sommes six étudiantes du double cursus Sciences et Sciences Sociales entre SciencesPo et l'université Pierre et Marie Curie.</p>
  <p><strong>Venez découvrir la controverse!</strong></p>
  
  <p align="justify">
Dans notre corps, certains organes comme le pancréas, le rein ou la thyroïde sécrètent des hormones, qui sont des molécules destinées à agir sur d’autres organes en étant transportées par le sang. L’ensemble de ces organes compose le système endocrinien. Il est primordial car la sécrétion d’hormones permet de réguler notre métabolisme, notre croissance et notre reproduction. Aussi, il est à la base du fonctionnement de notre corps. Par exemple, l’insuline et le glucagon, deux hormones, agissent sur la régulation de la glycémie, l’adrénaline sur la contraction musculaire, les oestrogènes sur la reproduction, … En temps normal, il s’auto-régule : le taux de sécrétion d’une hormone est déterminé par d’autres hormones agissant en amont, la plupart du temps provenant du complexe hypothalamo-hypophysaire de notre cerveau, mais également par un rétrocontrôle des hormones sur lesquelles elle influe. </p> 

  <p align="justify">
Pourtant, il existe des molécules peuvent perturber ce fonctionnement en remplaçant une hormone et en imitant ou bloquant son effet. Ces entités chimiques sont appelées perturbateurs endocriniens. </p> 

 <p align="justify">
Les perturbateurs provoquent différents problèmes de santé chez les personnes concernées ainsi que des dérèglements environnementaux importants. Or, ils prennent une place de plus en plus importante dans notre quotidien, à tel point qu’ils sont semblent aujourd’hui être omniprésents : on en retrouve dans les cosmétiques, les pesticides, mais aussi l’alimentation et les plastiques.
Cependant, la véritable prise de conscience de l’enjeu de santé publique qu’ils constituent reste assez récent par rapport aux découvertes scientifiques plus anciennes. Les perturbateurs endocriniens sont aujourd’hui au coeur de l’actualité car ils soulèvent des débats aux niveaux politiques européen et français sur leur réglementation. Au delà des politiques, de nombreux acteurs ont été saisis ou se sont saisi eux mêmes de la question, menant à de nombreux réseaux d’acteurs qui s’influencent ou se combattent les uns les autres. En effet, les enjeux de la question sont nombreux : santé publique, développement industriel, protection de l’environnement… Ceci explique les difficultés que rencontrent nos dirigeant à légiférer sur le sujet tout en conciliant les intérêts des différents acteurs (industriels, populations, scientifiques, associations) ainsi que la faisabilité de la suppression de ces produits au sein de notre industrie postmoderne. </p>


 <p align="justify">
Face à ce fourmillement dans le débat d’idée autour de multiples acteurs, il nous est apparu nécessaire de faire un état des lieux et une analyse de la controverse autour de l’enjeu de la régulation des perturbateurs endocriniens au niveaux français et européen. Sans prendre aucun parti, nous établirons les actions et les positions de chacun, avant de proposer une réflexion sur la possibilité de se passer des perturbateurs endocriniens au jour d’aujourd’hui. </p> 
            </article>
            
        <div id='Sommaire'>
            <p>Cliquer sur les produits pour les voir de plus près:</p>
                <img src="perturbateurs endocriniens.jpg" alt="Perturbateurs endocriniens" usemap="#pertumap" style="width:600px;height:600px;">
                <map name="pertumap"> <area shape="rect" coords="45,195,140,430" alt="Biberon" href="http://social-sante.gouv.fr/sante-et-environnement/risques-microbiologiques-physiques-et-chimiques/article/bisphenol-a">
</map>
            </div>
        </div>


</body>
</html>

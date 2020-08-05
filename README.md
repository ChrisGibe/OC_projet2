# OC_projet2 [Chalets et caviar](https://www.chaletsetcaviar75.fr/)
# Intégrez un thème Wordpress pour un client

Bravo ! Vous venez de vous lancer en tant que développeur freelance et vous avez décroché votre premier contrat.

Votre client ? L’agence immobilière “Chalets et caviar” de Courchevel. 

![Chalets et caviar](https://user.oc-static.com/upload/2019/07/16/15632617541681_image1.png)

Le logo de l'entreprise Chalets et caviar
Chalets et caviar
Cette agence possède une quinzaine de chalets de luxe à la vente et une vingtaine en location.

Cependant, elle ne possède pas encore de site web pour promouvoir la vente et la location de ses chalets. C’est pour cette raison qu’elle fait appel à vous.

Lors d’une première réunion, vous rencontrez Marie, la directrice de l’agence.  Voici l’échange de mails que vous recevez suite à cette réunion.

 

**De : Marie D.**

**À : Moi**

--------------------------------------------------------------------------------------------------------

Bonjour,

Je suis ravie de savoir que le projet te plaise. Comme nous en avons discuté, je souhaite créer un site web pour notre agence “Chalets et caviar”. J’aimerais que mon équipe et moi puissions mettre à jour le site régulièrement, sans passer par un prestataire.

As-tu une recommandation à me faire pour que les mises à jour soient le plus simple possible ?

Cordialement, 

Marie Dubois

Directrice de l’agence Chalets et caviar

--------------------------------------------------------------------------------------------------------

**De : moi**

**À : Marie**

------------------------------------------------------------------------------------------------------

Bonjour Marie,

Pour que vous puissiez mettre à jour votre site facilement, sans passer par un prestataire externe, je vous recommande un site Wordpress.

Peux-tu me donner plus de détails sur le design du site que tu recherches ? Cela me permettra de te proposer le thème Wordpress le plus adapté à tes besoins.

Merci.

-------------------------------------------------------------------------------------------------------

**De : Marie**

**À : Moi**

-------------------------------------------------------------------------------------------------------

Bonjour,

Je souhaite un design clair et épuré, qui montre la ligne luxe de l’agence. J’aimerais que tu me présentes la première version en ligne du site avec les éléments suivants : 

une section avec 5 chalets à louer ;
une section avec 5 chalets à vendre ;
une page de contact avec les coordonnées de l’agence et un formulaire de contact fonctionnel.
 

Pour que ce soit plus facile pour nous de collaborer sur les différentes offres, pourras-tu t’assurer de bien utiliser des catégories séparées pour que chacun retrouve ses petits ?

Tu trouveras en pièce jointe un dossier contenant les visuels de nos chalets ainsi qu’un document avec leurs caractéristiques.

 

Merci, 

Marie Dubois

Directrice de l’agence Chalets et caviar

--------------------------------------------------------------------------------------------------------

**De : Moi**

**À : Marie Dubois**

--------------------------------------------------------------------------------------------------------

Bonjour Marie,

Merci, j’ai bien pris en note toutes les informations. Je te préparerai un document présentant le thème wordpress et montrant que cela correspond bien à tes attentes en termes de design.

Y a-t-il d’autres éléments que je dois prendre en compte pour la création du site ?

--------------------------------------------------------------------------------------------------------

**De : Marie**

**À : Moi**

--------------------------------------------------------------------------------------------------------

Oui, pour faciliter la mise à jour du site par l’équipe (ajout, suppression et modification de chalets), pourrais-tu ajouter des droits d’administrateur selon les règles suivantes : 

un compte administrateur pour la directrice de l'agence ;
un compte administrateur pour le développeur (toi) s'il n'existe pas déjà ;
des comptes éditeurs pour les 2 autres collaborateurs de l'agence ?
Pourrais-tu également me fournir un document contenant les instructions de mise à jour ? 3 à 5 pages devraient suffire. N’oublie pas qu’on ne connaît rien au développement, donc je veux bien toutes les étapes détaillées, si possible avec des captures d’écran !


Merci,

Marie Dubois

Directrice de l’agence Chalets et caviar

Vous avez tous les éléments pour vous lancer dans cette mission… C’est parti !

# Gatsby v2 WordPress Starter

This starter is forked from the
[gatsby-starter-netlify-cms](https://github.com/netlify-templates/gatsby-starter-netlify-cms)
and modified to use WordPress instead of netlify-cms, using the [gatsby-source-wordpress](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-source-wordpress) plugin as the data connector.

Demo: https://gatsby-starter-wordpress.netlify.com/

## Use It Now

    gatsby new NAME https://github.com/GatsbyCentral/gatsby-starter-wordpress

* Edit `gatsby-config.js`, change `baseUrl`
  - Make sure you have at least 1 post and 1 page on your WordPress site
  - Make sure at least 1 post has at least 1 tag
* Ensure the permalink structure in your WordPress installation is set to `Post Name` instead of the deafult `Plain`, or else the `gatsby-source-wordpress` plugin won't be able to communicate with WordPress
* Rejoice
  - For more information on the source plugin, check out the [gatsby-source-wordpress](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-source-wordpress) repository page
  - File any [issues here](https://github.com/GatsbyCentral/gatsby-starter-wordpress/issues)

### Known Limitations

* This is based on the [netlify starter](https://github.com/netlify-templates/gatsby-starter-netlify-cms) which uses [bulma](https://bulma.io). This adds 150KB to every built page.
* Your WordPress site must have at least 1 post with 1 tag, or the starter will crash
* Nested pages / categories will not render with nested pages
  - A WordPress page like `/about/team/` will render on Gatsby as `/team/`
  - Likewise for categories
  - Discussion here https://github.com/GatsbyCentral/gatsby-starter-wordpress/issues/24

## CSS Processing

This plugin uses [gatsby-plugin-purgecss](https://www.gatsbyjs.org/packages/gatsby-plugin-purgecss/) and [bulma](https://bulma.io/). The bulma build would otherwise be ~170K which adds 170K to each of your built HTML pages. However, with purgecss this is reduced 90%.

## WordPress Setup

Check the [gatsby-source-wordpress](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-source-wordpress) plugin for more information. If you want to copy the demo content, you can grab the [WordPress XML export here](https://wpdemo.gatsbycentral.com/gatsbystarterwordpress.WordPress.2019-09-12.xml) and import it into your WordPress site as a starting point.

## Support

Please post support questions on StackOverflow or other similar sites. Please only post issues here if you have a bug to report with a reproduction. Unfortunately we're not able to provide support here.

## Contributors

This starter was forked from the netlify starter by the
[GatsbyCentral](https://www.gatsbycentral.com/) crew. Additional contributions
were gratefully received from the following folks:

* https://github.com/tomByrer
* https://github.com/dajocarter


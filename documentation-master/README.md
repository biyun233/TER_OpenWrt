# Nouvelle Interface Web de OpenWrt
## Membre du groupe

    Biyun WANG
    Zhao  ZHANG

## Résumé du projet
Français:

OpenWrt dispose déjà d’une interface web de configuration, LuCI, mais celle-ci est difficile à 
utiliser, peu intuitive, et destinée à des utilisateurs avancés. Un projet récent nommé « OUI » 
propose une interface alternative qui améliore l’utilisabilité, mais qui conserve certains travers de 
LuCI. Un autre projet similaire, JUCI, a été développé il y a quelques années mais n’est plus 
maintenu. 

Le but du projet est de concevoir et réaliser une interface web intuitive pour configurer un 
routeur personnel de type « Box Internet Wifi » et voir l'activité de ce routeur, qui se concentre 
sur les utilisateurs non experts du routeur. Cette nouvelle interface s’intégrerait dans 
OpenWrt, un projet Open Source utilisé sur des millions de routeurs dans le monde.

Cette interface ne couvrira pas toutes les fonctionnalités de LuCI, mais quelques fonctionnalités de base qui
répondre aux besoins habituels des utilisateurs débutants. En revanche, cette interface s'ajoutera à l'habituelle
interface Web de LuCI en tant que nouvelle partie, dans ce cas, les besoins avancés des utilisateurs seront satisfaits.

Nous avons envoyé un questionnaire à un échantillon représentatif du public cible et organisé 
trois entretiens pour analyser les besoins des utilisateurs. De cette façon, nous avons conçu 
une interface Web et identifié les fonctionnalités de l'interface Web.

Cette interface web doit être codée avec les techniques HTML5/CSS3、Javascipt Luci-js et basé 
sur le thème Luci.

Après un mois de phase de codage, nous avons envoyé une demande de fusion de notre code au groupe 
de développeurs LuCI.Nous attendons leur réponse jusqu'à présent.

English:

OpenWrt already has a web configuration interface, LuCI, but this is intended for advanced users. 
For beginning users, LuCI is difficult to use, and not very intuitive. A recent project called "OUI" 
offers an alternative interface that improves usability, but which retains certain shortcomings of LuCI. 
Another similar project, JUCI, was developed a few years ago but is no longer maintained.

The goal of the project is to design and create an intuitive web interface to configure a personal 
router type "Wifi Internet Box" and see the activity of this router, which focuses on non-expert users 
of the router. This new interface would integrate into OpenWrt, an Open Source project used on millions 
of routers worldwide.

This interface won't cover all the functionalities that LuCI has, but a few basic functionalities that 
meet the usual needs of beginning users. On the other hand, this interface will be added to the usual 
web interface of LuCI as a new part, in this case, users’ advanced needs will be satisfied.

We surveyed the home router interface online and organized three interviews to analyze the needs of users.
In this way, we designed a web interface and identified the web interface functionalities.

The web interface was coded with HTML5 / CSS3, Javascipt Luci-js and theme Luci.

After one month's coding phase, we have sent a merge request of our code to LuCI's developer group. 
We are waiting for their response until now.

### Documentation interne
Comme nous n'avons pas crée des nouvelles fonctions, je vous donne le lien vers le document interne du LuCI.

[Documentation interne](https://openwrt.github.io/luci/jsapi/)


### Code source
|Date|Modules|
|---|---|
|18/06/2020|[Dashboard](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/luci/-/tree/dashboard/modules/luci-mod-dashboard)
|18/06/2020|[Quick Setup](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/luci/-/tree/quick-setup-v1/modules/luci-mod-quick_setup)
|18/06/2020|[Simple Configuration](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/luci/-/tree/simple_configuration/modules/luci-mod-simple_configuration)

### Les documentations

|Date|Fiche|
|---|---|
|15/01/2020|[cahier des charges](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/blob/master/cahier_des_charges.pdf)|
|15/01/2020|[cahier de recettes](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/blob/master/cahier_de_recettes.pdf)|
|15/01/2020|[plan du developpement](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/blob/master/plan_du_developpement.pdf)|
|10/05/2020|[résultat d'entretien](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/blob/master/resultat_entretien.pdf)
|18/06/2020|[Rapport](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/blob/master/Report.pdf)
|18/06/2020|[plan de test](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/blob/master/test_plan.pdf)
|18/06/2020|[manuel d'utilisation](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/blob/master/user_manual.pdf)
|18/06/2020|[manuel d'installation](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/blob/master/manuel_installation.pdf)

### Compte-rendus des réunions

|Date|Fiche|
|---|---|
|06/11/2019|[compte-rendu n°1](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/Compte-rendu-de-r%C3%A9union-1)
|12/11/2019|[compte-rendu n°2](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/Compte-rendu-de-r%C3%A9union-2)
|15/11/2019|[compte-rendu n°3](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/compte-rendue-de-réunion-3)
|22/11/2019|[compte-rendu n°4](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/Compte-rendue-de-réunion-4)
|26/11/2019|[compte-rendu n°5](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/Compte-rendue-de-réunion-5)
|06/12/2019|[compte-rendu n°6](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/Compte-rendue-de-réunion-6)
|17/12/2019|[compte-rendu n°7](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/Compte-rendue-de-réunion-7)
|20/12/2019|[compte-rendu n°8](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/wikis/Compte-rendue-de-r%C3%A9union-8)
|08/01/2020|[compte-rendu n°9](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-9)
|17/01/2020|[compte-rendu n°10](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-r%C3%A9union-10)
|23/01/2020|[compte-rendu n°11](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-r%C3%A9union-11)
|10/02/2020|[compte-rendu n°12](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-12)
|13/04/2020|[compte-rendu n°13](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-13)
|05/05/2020|[compte-rendu n°14](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-14)
|08/05/2020|[compte-rendu n°15](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-15)
|13/05/2020|[compte-rendu n°16](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-16)
|20/05/2020|[compte-rendu n°17](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-17)
|28/05/2020|[compte-rendu n°18](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-18)
|04/06/2020|[compte-rendu n°19](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-19)
|08/06/2020|[compte-rendu n°20](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-20)
|15/06/2020|[compte-rendu n°21](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-21)
|18/06/2020|[compte-rendu n°22](https://gricad-gitlab.univ-grenoble-alpes.fr/projet-ter-m1-wic-openwrt/documentation/-/wikis/Compte-rendue-de-réunion-22)
# TER_OpenWrt

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

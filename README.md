# ServeurProxy
Présentation du serveur proxy web

<b>Définition</b>

Pour commencer, il est important de préciser que le terme « proxy » peut être traduit par mandataire, procuration, intermédiaire

Donc, un serveur proxy est un serveur qui servirait d’intermédiaire ou un serveur que l’on mandaterait pour faire quelque chose.

Essayons d’imaginer le rôle d’un serveur proxy en dehors de l’informatique. On pourrait expliquer cela comme ça :

<ul>
Vous devez récupérer un colis ou faire vos courses, mais vous ne pouvez ou ne voulez pas y aller (par faute de temps, parce que c’est loin, ou pour toute autre raison …)  : Vous envoyez quelqu’un le faire à votre place. Cette personne (ce mandataire) ira chercher le colis ou faire vos courses pour vous et vous ramènera ce qu’il a récupéré.
</br></br>
Voilà, le principe du serveur proxy (mandataire).
</br></br>
Mais attention, s’il faut que le mandataire paye pour vous, il faudra que vous lui donniez des informations personnelles telles le code de votre carte bleue, et c’est là qu’on voit qu’il faut avoir toute confiance dans ce mandataire (ou alors ne lui confier que des tâches qui ne nécessitent pas d’informations confidentielles : c’est à dire récupérer un colis qui n’a pas besoin de paiement).
</ul>

<b>Principe de fonctionnement</b>

Les serveurs proxy permettent de sécuriser et d'améliorer l'accès à certaines pages Web en les stockant en cache (ou copie). Ainsi, lorsqu’un navigateur envoie une requête sur la demande d'une page Web qui a été précédemment stockée, la réponse et le temps d'affichage en sont améliorés. L'utilisateur accède plus rapidement au site et ne sature pas le proxy pour sortir. Les serveurs proxy renforcent également la sécurité en filtrant certains contenus Web et les logiciels malveillants.

<i>Filtrage</i>

Le filtrage est appliqué en fonction de la politique de sécurité en place sur le réseau. Ceci permet de bloquer selon une liste noire, les sites considérés comme malveillants et/ou inutiles au contexte de travail de l'entreprise (pornographie ... etc)

<i>Authentification</i>

Afin de limiter l'accès au réseau extérieur, et de renforcer ainsi la sécurité du réseau local, il peut être nécessaire de mettre en place un système d'authentification pour accéder aux ressources extérieures. Ceci est assez dissuasif pour les utilisateurs souhaitant visiter des sites contraires à la charte de leur système d'information. Ils se sentent suivis et restent "sages" dans leurs recherches. 

<i>Stockage des Logs</i>

Le stockage, des logs des sites visités et des pages vues, permet à l'administrateur du réseau de redéfinir la politique de sécurité du réseau et/ou d'intervenir auprès d'un utilisateur qui visite fréquemment des sites malveillants ou sans rapport avec l'activité de l'entreprise.

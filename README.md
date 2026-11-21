# WarLike Telecom
Application utilisateur de téléphonie Internet, distincte de WarLike Networks (registre et routage) et WarLike Chat (collaboration).
T01 : interface responsive, clavier, contacts locaux, validation explicite des destinations internes et publiques. Aucun appel ou SMS transmis. Aucune donnée de contact envoyée au réseau. Effacer les données locales permet de supprimer les contacts de ce navigateur.
T02 : session WarLike Keys/Server et récupération sécurisée de sa ligne Networks.
T03 : appels internes WebRTC + signalisation ; T04 messagerie interne ; T05 opérateur SIP/PSTN et SMS publics ; T06 historique et notifications.
Pas de faux appels, de faux numéros publics ou de faux accusés de réception. Hébergement cible Cloudflare Pages, à configurer.

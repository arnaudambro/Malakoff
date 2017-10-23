  <!-- Conseils de développement
-> La limite entre Desktop et Mobile, c'est 480 pixels.
-> MJML c'est mobile first.
-> Lorsqu'on précise la width d'un mj-column, il ne s'applique qu'en version Desktop. En version mobile, c'est 100%.
-> Lorsqu'on indique pas de width pour l'image, une fois compilé en HTML l'image est inclue dans un <td> qui prend une width particulière, un peu inattendue et qui dérange la taille de l'image en version mobile. Lorsqu'on précise width="0", cela donne la width au futur <td> et l'image prend 100% de la largeur en version mobile.
-> Outlook insert un page-break après 1800 pixels de longueur
-> border-color: black!important; => NON
-> border-color: black !important; => OUI
-> Pour les liens sur Gmail, le seul truc qui marche c'est le rajout de la classe nolink
-> Outlook et Gmail lisent très mal la banner -> on la met en picture directos popoulos
-->


# Malakoff

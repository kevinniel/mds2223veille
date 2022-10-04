# JWT (JSON Web Token)
<p align="center">
    <img alt="JWT" src="http://jwt.io/img/logo-asset.svg">
</p>

## Description
JSON Web Token (JWT) est un standard ouvert défini dans la RFC 7519. Il permet l'échange sécurisé de jetons (tokens) entre plusieurs parties. Cette sécurité de l’échange se traduit par la vérification de l'intégrité et de l'authenticité des données. Elle s’effectue par l'algorithme HMAC ou RSA.

### Structure
Un jeton se compose de trois parties :

- Un en-tête (header), utilisé pour décrire le jeton. Il s'agit d'un objet JSON.
- Une charge utile (payload) qui représente les informations embarquées dans le jeton. Il s'agit également d'un objet JSON.
- Une signature numérique.

Il existe des outils en ligne permettant de les déchiffrer.

## Sources
Nom | Type | Langue | Lien | Description | Tags | Note
--- | --- | --- | --- | --- | --- | --- 
![dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)|Site web|Anglais|https://dev.to/shubhamyadav/jwt-json-web-token-1j19|Présentation succincte de JWT|Découverte|4/5|
![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)|Site web|Anglais|https://systemweakness.com/hacking-jwt-3324cba98210|Différentes attaques pouvant être éffectuées sur la librairie|Sécurité|4/5|
![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)|Site web|Anglais|https://blog.bitsrc.io/best-practices-for-using-jwt-df3788433fd3|Bonnes pratiques|Sécurité, Guide|4/5|
Algolia|Site web|Anglais|https://www.algolia.com/blog/engineering/api-keys-vs-json-web-tokens/|API Keys VS JWT Auth|Comparatif|4/5|
![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)|Site web|Anglais|https://infosecwriteups.com/attacks-on-json-web-token-jwt-278a49a1ad2e|Attaques sur JWT|Sécurité|4/5|
![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)|Site web|Anglais|https://javascript.plainenglish.io/where-to-store-the-json-web-token-jwt-4f76abcd4577|Ou stocker ton token ?|Comparatif, Sécurité, Stockage|4/5|
![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)|Site web|Anglais|https://codeburst.io/localstorage-vs-cookies-all-you-need-to-know-about-storing-jwt-tokens-securely-in-the-front-end-70dc0a9b3ad3|Risques liés au lieu du stockage du token|Comparatif, Sécurité, Stockage|4/5|
![dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)|Site web|Anglais|https://dev.to/koladev/authentication-and-authorization-with-jwts-in-node-expressjs-5a9a|Mise en application de la librairie avec le framework Express JS|Tuto, Express JS|4/5|
![redis](https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white)|Site web|Anglais|https://redis.com/blog/json-web-tokens-jwt-are-dangerous-for-user-sessions/|JWT est dangereux|Sécurité|3/5|
![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)|Site web|Anglais|https://github.com/dwyl/learn-json-web-tokens/blob/master/README.md|Mise en application|Guide|4/5|
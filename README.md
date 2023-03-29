# Card_Extraction_Data

## Classification de documents (carte d'identité, permis de conduire et CPF)

### Contexte : 
De nombreuses zones différentes des organisations (généralement dans le cadre d'un processus de back-office) reçoivent des documents de leurs clients pour former des kits de documentation. Ces kits sont partagés avec d'autres parties prenantes des entreprises, par exemple. Comme on peut l'imaginer, un défi dans ce scénario est le fait que le client peut envoyer des documents sans nécessairement indiquer de quel type de document il s'agit (carte d'identité, permis de conduire ou CPF, par exemple). Par conséquent, au lieu de nécessiter un travail manuel pour lire et classifier les documents, nous pouvons construire un modèle d'apprentissage capable de lire un ensemble de documents (en .jpg, par exemple) et de les classer ultérieurement en trois types distincts : carte d'identité, permis de conduire et CPF.
Ensemble de données : Pour ce défi, nous utiliserons un ensemble de données public de cartes d'identité, de permis de conduire et de CPF (y compris des images). Ce référentiel présente l'ensemble de données appelé Brazilian Identity Document Dataset (BID Dataset), le premier ensemble de données public de documents d'identification brésiliens.

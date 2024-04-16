Le projet consiste a développer un outil d'exploitation de vidéo de présentation des résultats financiers annuels des organismes d'assurance. 
Le résultat est préformaté afin qu'il puisse directement etre utilisé par les controleurs dans la fiche de synthèse.
La solution est structurée en 3 phases : 
1) Transformation de la vidéo (Input data) en audio puis en texte grace a Azure Whisper.
2) Traduction du texte en francais grace a Azure OPENAI.
3) Résumer le texte avec LangChain et Azure OPENAI sous le format fiche de synthèse.

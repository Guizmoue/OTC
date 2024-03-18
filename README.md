# OTC

## Informations Générales

- **_Tasks :_** Text Classification - Sub-tasks : fact-checking
- **_Corpus :_** datacommons_factcheck (https://huggingface.co/datasets/datacommons_factcheck?row=25)
- **_Goal :_** Ce corpus peut-être utile pour réaliser un detecteur automatique de "fake news".
- **_Models :_** Bien que ce corpus date de 2020, aucun modèle à ce jours n'a exploité ce corpus. Ensemble de données fourni à des fins de recherche uniquement.
- **_Features :_** C'est un corpus monolingue en langue anglaise, il contient 5764 lignes. Chaque ligne nous renseigne sur l'organisme qui a fact-checker la déclaration, le titre de la déclaration, la date d'examen de cette déclaration, l'adresse URL de la déclaration, la note de l'article en fonction de sa véracité, la provenance de la déclaration et enfin sa date de publication. Les quatre organismes qui se sont occupés de l'annotation sont FactCheck.org, PolitiFact, The Washington Post et The Weekly Standard avec la participation de Yacine Jernite qui gère une équipe de Machine Learning chez Hugging Face.
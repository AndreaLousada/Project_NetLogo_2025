# Project_NetLogo_2025
 
Modèle de simulation multi-agent conçu pour étudier la dynamique des réseaux sociaux. Le modèle se concentre sur la manière dont les agents, qui représentent des individus ou des entités, interagissent et influencent les comportements au sein d'une société simulée. Les agents peuvent observer l'état des autres, ce qui peut affecter leurs propres états, et ces interactions sont régies par des règles spécifiques qui simulent des phénomènes sociaux tels que la contagion des opinions ou la diffusion de l'information. La structure du réseau social qui émerge de ces interactions est étudiée pour comprendre les dynamiques sous-jacentes, telles que la centralité, la densité, et le regroupement des agents, ce qui permet d'analyser l'efficacité de stratégies de sensibilisation ou d'autres interventions sociales.
Ce modèle permet de simuler divers scénarios et de prévoir les impacts de certaines actions sur le réseau social global, offrant ainsi des insights précieux pour la prise de décision dans des contextes tels que la gestion de ressources ou les campagnes de sensibilisation.

Description Détail par Détail du Modèle
1.	Agents et États Internes :
o	Détail : Les agents dans ce modèle possèdent des états internes qui peuvent être observés par d'autres agents. Ces états représentent des attributs comme des opinions, des croyances ou des niveaux de sensibilisation, et peuvent changer en fonction des interactions avec d'autres agents.
2.	Observation et Influence :
o	Détail : Un agent peut observer l'état d'un autre agent, et cette observation peut influencer son propre état. Cela simule des phénomènes sociaux tels que la contagion des opinions ou le conformisme.
3.	Réseau Social :
o	Détail : Le modèle génère un réseau social basé sur les interactions entre agents. Les métriques de réseau telles que la centralité, la densité et le regroupement sont calculées pour analyser la structure et la dynamique du réseau.
4.	Scénarios de Simulation :
o	Détail : Le modèle permet d'explorer différents scénarios, comme l'impact de campagnes de sensibilisation sur la consommation d'eau ou la diffusion de l'information dans un réseau social.
5.	Diffusion d'Information :
o	Détail : Les agents diffusent des messages ou des états, et cela affecte les comportements au sein du réseau. Par exemple, la sensibilisation à une campagne peut se propager dans le réseau, influençant les décisions de consommation d'eau.

Introduction au Modèle :
•   Description générale du modèle : objectif du modèle et contexte dans lequel il est utilisé.	
•  Aperçu des caractéristiques principales et des fonctionnalités

Installation :
•	Comment configurer l'environnement de simulation.

Description des Agents et de l'Environnement :
•	Détails sur les types d'agents utilisés dans le modèle et leurs caractéristiques.
•	Explication de l'environnement où les agents interagissent, y compris la topologie du réseau, les règles d'interaction, etc.

Configuration du Modèle :
•	Instructions pour configurer les paramètres du modèle avant l'exécution, comme le nombre d'agents, les paramètres d'interaction, les conditions initiales, etc.
•	Description des différentes configurations possibles et de leurs impacts sur la simulation.

Exécution du Modèle :
•	Comment démarrer la simulation.
•	Description des étapes de simulation et ce à quoi s'attendre à chaque étape.
•	Commandes ou interfaces utilisateur pour contrôler et surveiller la simulation.

Analyse des Résultats :
•	Comment interpréter les résultats générés par le modèle.
•	Outils pour visualiser les résultats, tels que graphiques, réseaux sociaux générés, statistiques.
•	Exportation et manipulation des données générées.

Cas d'Utilisation :
•	Exemples pratiques de simulations réalisées avec le modèle.
•	Résultats attendus et analyse de différents scénarios.

Références et Ressources Supplémentaires :
•	Documentation supplémentaire, articles pertinents, tutoriels et autres ressources pouvant aider l'utilisateur à mieux comprendre et utiliser le modèle.


## Estrutura
- `src/`: Contém o código do modelo principal.
- `data/`: Arquivos de dados de entrada e saída.
- `results/`: Resultados das simulações.

## Como Executar
1. Abra `main.nlogo` no NetLogo.
2. Clique em "Setup" e "Go".

## Licença
Este projeto é licenciado sob a [MIT License](LICENSE).
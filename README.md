# Text Generation using RNN
# Génération de Texte par RNN

This project explores text generation using Recurrent Neural Networks (RNNs), focusing on GRU, minGRU, and LRU architectures. The goal is to evaluate the application of a multiplicative method to improve long-term dependency modeling in textual sequences.

Ce projet explore la génération de texte à l'aide de réseaux de neurones récurrents (RNN), en se concentrant sur les architectures GRU, minGRU et LRU. L'objectif est d'évaluer l'application d'une méthode multiplicative pour améliorer la modélisation des dépendances à long terme dans les séquences textuelles.

## Table of Contents
## Table des Matières

- [Introduction](#introduction)
- [Architectures Explored](#architectures-explored)
- [Results](#results)
- [Discussion](#discussion)
- [Contribution](#contribution)
- [License](#license)
- [Contact](#contact)

## Introduction
## Introduction

Since the Dartmouth conference, efforts to endow machines with linguistic skills have led to the development of architectures based on deep learning. This project focuses on using RNNs for text generation, exploring architectures such as GRU, minGRU, and LRU, and applying a multiplicative method to enhance performance.

Depuis la conférence de Dartmouth, les efforts pour doter les machines de compétences linguistiques ont conduit au développement d'architectures basées sur l'apprentissage profond. Ce projet se concentre sur l'utilisation des RNN pour la génération de texte, en explorant des architectures comme les GRU, minGRU et LRU, et en appliquant une méthode multiplicative pour améliorer les performances.

## Architectures Explored
## Architectures Explorées

- **GRU**: Gated Recurrent Unit, a simplified variant of LSTM.
- **minGRU**: Simplified version of GRU for better parallelization.
- **LRU**: Linear Recurrent Unit, using linear recurrences for increased efficiency.

- **GRU** : Gated Recurrent Unit, une variante simplifiée des LSTM.
- **minGRU** : Version simplifiée du GRU pour une meilleure parallélisation.
- **LRU** : Linear Recurrent Unit, utilisant des récurrences linéaires pour une efficacité accrue.

## Results
## Résultats

The results show that the GRU model offers the best performance in terms of accuracy, although the simplified architectures and the multiplicative approach do not significantly outperform classical RNNs. Visualizations and analyses of the results are available in the `results` folder.

Les résultats montrent que le modèle GRU offre les meilleures performances en termes de précision, bien que les architectures simplifiées et l'approche multiplicative ne surpassent pas significativement les RNN classiques. Les visualisations et analyses des résultats sont disponibles dans le dossier `results`.

## Discussion
## Discussion

The study highlights the challenges related to parameter reduction and model optimization for complex text generation tasks. Improvement paths include integrating attention mechanisms and advanced regularization techniques.

L'étude met en lumière les défis liés à la réduction des paramètres et à l'optimisation des modèles pour des tâches de génération de texte complexes. Des pistes d'amélioration incluent l'intégration de mécanismes d'attention et des techniques de régularisation avancées.

## Contribution
## Contribution

Contributions are welcome! To contribute, please follow these steps:

1. Fork the repository.
2. Create a branch for your feature (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a Pull Request.

Les contributions sont les bienvenues ! Pour contribuer, veuillez suivre ces étapes :

1. Forkez le dépôt.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`).
3. Committez vos modifications (`git commit -am 'Ajout d'une nouvelle fonctionnalité'`).
4. Poussez vers la branche (`git push origin feature/nouvelle-fonctionnalite`).
5. Créez une Pull Request.



## Contact
## Contact

For any questions or suggestions, please contact [your-email@example.com](mailto:elimane.seidou.com).

Pour toute question ou suggestion, veuillez contacter [votre-email@example.com](mailto:elimane.seidou.com).

---

N'hésitez pas à personnaliser ce modèle en fonction des spécificités de votre projet et des informations que vous souhaitez inclure.

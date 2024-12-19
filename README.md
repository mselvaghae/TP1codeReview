# AwesomePasswordChecker

**AwesomePasswordChecker** is a Java library designed to analyze and evaluate passwords. It includes features for password masking, distance calculation between passwords and predefined clusters, and custom MD5 hash computation. This tool helps assess password complexity and uniqueness in a secure and structured manner.

---

## Features

- **Password Masking**: Converts passwords into numerical masks based on predefined character categories.
- **Distance Calculation**: Measures the similarity between a password and predefined cluster centers using the Euclidean distance.
- **MD5 Hashing**: Provides a custom implementation for computing the MD5 hash of a password.
- **Singleton Pattern**: Ensures a single instance of the password checker is used across the application.

---

## Requirements

- **Java Version**: Java Development Kit (JDK) 8 or higher.
- **Cluster File**: A CSV file containing cluster center data (e.g., `cluster_centers_HAC_aff.csv`).

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mselvaghae/codeReview.git
---

## Documentation
- La documentation complète du projet, y compris les détails sur l'API et les exemples d'utilisation, est disponible ici :
[👉 Javadoc](https://mselvaghae.github.io/TP1codeReview/javadoc/3.4.1)

---

## Contribuer
- Forkez le dépôt.
- Créez une branche pour votre fonctionnalité :
   ```bash
   git checkout -b feature/nouvelle-fonctionnalite
   
- Faites vos modifications, ajoutez vos commits et poussez la branche :
   ```bash
   git add .
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   git push origin feature/nouvelle-fonctionnalite
- Ouvrez une Pull Request.
---
## Licence
- Ce projet est sous licence MIT [LICENCE](https://github.com/mselvaghae/TP1codeReview/blob/main/LICENSE)
pour plus d'informations.
---
## Contact
- Pour toute question ou suggestion, veuillez ouvrir une issue dans le dépôt GitHub :
[👉 TP1codeReview Issues](https://github.com/mselvaghae/TP1codeReview/issues/new/choose)

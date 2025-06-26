# ENSAE-Digital-Vote
Ce projet est une application web destinée à organiser et gérer les élections des représentants de l’ENSAE. Elle permet aux étudiants de voter en ligne, aux administrateurs de gérer les élections et d’accéder aux résultats en temps réel.
## 👨‍💻 Connexion administrateur
Email : admin@ensae.fr
Mot de passe : admin123
## 📥 Importation des électeurs
Les colonnes doivent être du format: email | password | prenom | nom | classe. ⚠️ Le format du fichier doit être .xlsx ou .xls.
## 🔄 Persistance des données
Les données (élections, électeurs, votes) sont enregistrées dans le navigateur (via localStorage) sous la clé sharedElectionsData, ce qui permet aux administrateurs de voir la même base s’ils utilisent le même navigateur.
## ✅ Fonctionnalités principales
Authentification des électeurs,
vote sécurisé (1 vote par élection),
résultats en temps réel,
tableau de bord administrateur,
import/export des données,
interface responsive (smartphone + ordinateur)

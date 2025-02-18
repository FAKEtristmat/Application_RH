# 📋 Application RH

Bienvenue dans le projet de l'application RH ! Cette application est conçue pour gérer les demandes de congé des employés, permettant aux employés de demander des congés et aux managers d'approuver ou de refuser ces demandes.

## 🌟 Fonctionnalités

- **Demande de Congé** : Les employés peuvent demander des congés en spécifiant une date de début et une date de fin.
- **Approbation des Congés** : Les managers peuvent approuver ou refuser les demandes de congé.
- **Interface Utilisateur** : Interfaces distinctes pour les employés et les managers.
- **Gestion des Données** : Les données sont stockées dans des fichiers CSV pour une gestion simple et efficace.

## 🖥️ Interfaces

### Interface Employé
- **Demande de Congé** : Permet aux employés de spécifier les dates de début et de fin de leur congé.
- **Statut des Demandes** : Affiche le statut des demandes de congé (approuvé, refusé, en attente).

### Interface Manager
- **Approbation des Congés** : Permet aux managers de voir et d'approuver ou de refuser les demandes de congé.
- **Gestion des Employés** : Interface pour gérer les informations des employés.

## 📦 Bibliothèques à Installer

Pour exécuter ce projet, vous aurez besoin des bibliothèques suivantes :

- **JFreeChart** : Pour les graphiques.
- **JCalendar** : Pour les sélecteurs de date.
- **Apache PDFBox** : Pour générer des PDF.

Vous pouvez ajouter ces dépendances à votre projet Maven ou Gradle.

### Maven
```xml
<dependencies>
    <dependency>
        <groupId>org.jfree</groupId>
        <artifactId>jfreechart</artifactId>
        <version>1.5.3</version>
    </dependency>
    <dependency>
        <groupId>com.toedter</groupId>
        <artifactId>jcalendar</artifactId>
        <version>1.4</version>
    </dependency>
    <dependency>
        <groupId>org.apache.pdfbox</groupId>
        <artifactId>pdfbox</artifactId>
        <version>2.0.24</version>
    </dependency>
</dependencies>

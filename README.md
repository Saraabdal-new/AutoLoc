# AutoLoc — Plateforme de gestion de location de véhicules multi-agences

## Description

AutoLoc est une application de gestion d'une plateforme de location de véhicules multi-agences.

Le projet est réalisé dans le cadre du module **Architecture des Systèmes d'Information (ASI)** à ESPRIT.

Cette première version permet de mettre en place le modèle de domaine avec les principales entités JPA de l'application.

## Technologies utilisées

- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- MySQL
- Lombok
- IntelliJ IDEA

## Structure du projet

```text
src/
└── main/
    └── java/
        └── tn/
            └── esprit/
                └── autoloc/
                    ├── domain/
                    │   ├── Agence.java
                    │   ├── Client.java
                    │   ├── Contrat.java
                    │   ├── Employe.java
                    │   ├── Equipement.java
                    │   ├── Maintenance.java
                    │   ├── Paiement.java
                    │   ├── Reservation.java
                    │   ├── Vehicule.java
                    │   ├── CategorieVehicule.java
                    │   ├── ModePaiement.java
                    │   ├── RoleEmploye.java
                    │   └── StatutReservation.java
                    │
                    ├── repository/
                    ├── service/
                    └── web/
                        ├── controller/
                        └── dto/

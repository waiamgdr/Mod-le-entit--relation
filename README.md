## Explications

* L'entité Gymnase représente un établissement physique de la salle de sport. Elle est caractérisée par son nom, son adresse et son numéro de téléphone.
* L'entité Membre représente une personne inscrite à la salle de sport. Elle est caractérisée par son identifiant unique, son nom, son prénom, son adresse, sa date de naissance et son sexe.

* L'entité Séance représente une activité proposée par la salle de sport. Elle est caractérisée par son type de sport, son horaire et le nombre de places disponibles.

* L'entité Coach représente une personne qui anime une séance. Elle est caractérisée par son nom, son prénom, son âge et sa spécialité.

* La relation Inscrit relie un membre à un gymnase. Elle représente le fait qu'un membre est inscrit dans un gymnase. La cardinalité de cette relation est 1 membre vers N gymnases, car un membre peut être inscrit dans plusieurs gymnases.

* La relation Participe relie un membre à une séance. Elle représente le fait qu'un membre participe à une séance. La cardinalité de cette relation est 1 membre vers N séances, car un membre peut participer à plusieurs séances.

* La relation Animée par relie une séance à un coach. Elle représente le fait qu'une séance est animée par un coach. La cardinalité de cette relation est 1 séance vers 0..2 coachs, car une séance peut être animée par un coach ou par deux coachs.

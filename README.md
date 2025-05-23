# Model_Concurrency

## Installation

```
Installer UPPAAL
```

## Tests & Vérifications

Dans la section vérificateur de UPPAAL, j'ai créé 4 propriétés pour tester l'algorithme :

| Propriété | Description |
|-----------|-------------|
| `E<> Client1.GotTicket` | Vérifie si le client peut atteindre l'état GotTicket |
| `E<> Client1.GotServiceTicket` | Vérifie si le client peut atteindre l'état GotServiceTicket |
| `E<> Client1.Granted` | Vérifie si le client peut accéder au service final |
| `A[] Client1.Granted imply HasServiceTicket` | Vérifie que le client ne peut jamais accéder au service sans ticket |

## Explication

Ce modèle simule le protocole kerberos

## Commentaire

Commentaire par rapport au projet, la prise en main, et la compréhension du protocole était assez simple, le plus dur était de se familiarisé avec le logiciel uppaal c'est pour cela qu'a la fin de notre projet respectif mon camarade de Master Francois Flandin et moi avons crée un tutoriel pour la prise en main de ce dernier.

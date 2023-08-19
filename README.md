# software-design-principles
Zoom sur les principes de conception en développement logiciel

Les principes de conception en développement logiciel sont des lignes directrices et des règles générales qui aident les développeurs à créer des systèmes informatiques efficaces, durables et maintenables. Ils sont essentiels pour produire un code de haute qualité, facile à comprendre, à maintenir et à faire évoluer.

Ce dépôt Github:
* explique ces principes de conception
* les vulgarise
* les illustre par le biais de schémas
* démontre leur utilité au travers d'examples d'implémentation


### Principe de Responsabilité Unique (Single Responsibility Principle - SRP)
Ce principe stipule qu'une classe ou un module ne devrait avoir qu'une seule raison de changer. En d'autres termes, une classe ne devrait avoir qu'une seule responsabilité ou fonction.

🚧

### Principe Ouvert/Fermé (Open/Closed Principle - OCP)
Ce principe suggère que les entités logicielles (classes, modules, fonctions, etc.) devraient être ouvertes à l'extension mais fermées à la modification. Cela signifie que vous devriez pouvoir ajouter de nouvelles fonctionnalités sans modifier le code existant

🚧

### Principe de Substitution de Liskov (Liskov Substitution Principle - LSP)
Ce principe énonce que les objets d'une classe dérivée devraient pouvoir être substitués à des objets de la classe de base sans affecter la cohérence du programme. En d'autres termes, les sous-classes devraient être utilisables de manière transparente comme les classes parentes.

🚧

### Principe d'Interface de Ségrégation (Interface Segregation Principle - ISP)
Ce principe préconise que les interfaces clients ne devraient pas être forcées d'implémenter des méthodes dont elles n'ont pas besoin. En d'autres termes, des interfaces spécifiques devraient être créées pour des cas d'utilisation spécifiques, plutôt qu'une seule interface monolithique.

🚧

### Principe d'Inversion de Dépendance (Dependency Inversion Principle - DIP)
Ce principe suggère que les modules de haut niveau ne devraient pas dépendre directement des modules de bas niveau, mais plutôt des abstractions. Cela favorise la réutilisation du code et rend le système plus flexible.

🚧

### Principe de Remplacement de Composition (Composition Over Inheritance)
Ce principe favorise la composition (l'assemblage d'objets plus petits pour créer des fonctionnalités plus grandes) plutôt que l'héritage pour réutiliser le code et éviter les problèmes associés à l'héritage multiple.

🚧

### Principe de Séparation des Préoccupations (Separation of Concerns - SoC)
Ce principe implique de diviser un programme en différentes parties, appelées préoccupations, où chaque partie traite d'un aspect particulier du logiciel. Cela facilite la gestion, la maintenance et l'évolutivité du système.

🚧

### Principe du Code DRY (Don't Repeat Yourself)
Ce principe préconise d'éviter la duplication de code en factorisant les fonctionnalités communes dans des emplacements réutilisables. Cela améliore la maintenabilité et réduit les erreurs.

🚧

### Principe de la Simplicité (KISS - Keep It Simple, Stupid)
Ce principe suggère que la simplicité doit être privilégiée dans la conception et l'implémentation. Évitez les solutions complexes lorsque des solutions simples suffisent.

🚧

### Principe de la Clarté (YAGNI - You Ain't Gonna Need It)
Ce principe conseille de ne pas ajouter de fonctionnalités ou de complexité inutiles avant qu'elles ne soient nécessaires. Cela évite le surdéveloppement et le code inutile.

🚧
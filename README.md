# mini_jeu_POO


Architechture du projet : 

mini_jeu_POO
├── lib
│   ├── player.rb
│   └── game.rb
├── app.rb
├── README.md
├── Gemfile
├── Gemfile.lock
└── .env
└── .gitignore



Version 1.0 : combat entre 2 joueurs

utilisation des fichiers ruby suivants :
app.rb
lib/player.rb

Création de 2 joueurs 
Chaque joueur a 10 points d'exp 

Chaque joueur attaque l'autre, chacun son tour 
Le nombre de point(s) d'attaque est défini aléatoirement entre 1 et 6 grâce à une fonction rand

Le combat se poursuit jusqu'à ce que l'un des deux soit mort 


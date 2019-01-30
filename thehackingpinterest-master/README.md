# thehackingpinterest-master

Groupe de Jonathan, Maxime et Marylis

pré-recquis:

bundle install
> pour avoir les gems:
gem 'table_print'
gem 'faker'


Consignes:

The Hacking Pinterest
Tu veux faire de la concurrence à Pinterest, donc tu voudrais créer un site où les utilisateurs peuvent créer des "pins". Chaque pin contient l'URL d'une image sur le net. Les utilisateurs peuvent commenter les pins, mais ne peuvent pas commenter les commentaires.


Présentation du projet:

3 tabs : users, pins et comments

modèle user
modèle pin : 1 foreign key(id_user)
modèle commentaire: 2 foreign key (id_user & id_pin)

seed.rb utilisé pour générer des entrées


Pour voir la base:
1)télécharger le zip
2)dézipper
3)chemin du dossier dans le terminal
4)ouvrir rails console
5) 'tp user.all' / ) 'tp pin.all' / ) 'tp comment.all' 

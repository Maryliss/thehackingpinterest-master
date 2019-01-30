# thehackingpinterest-master

Groupe de Jonathan, Maxime et Marylis

# Pré-recquis:

1) $ télécharger le zip 
> obvious 
2) $ dézipper 
>  :p 
3) $ chemin du dossier dans le terminal 
> (sans dec?)
4) $ bundle install
> pour avoir les gems: gem 'table_print' et gem 'faker'
5) $ rails db:migrate 
> pour mettre les migrations up.
6) $ rails c
> pour lancer la console de rails
7) 'tp user.all' / ) 'tp pin.all' / ) 'tp comment.all' 
> pour voir les différents tabs

# Consignes:

The Hacking Pinterest
Tu veux faire de la concurrence à Pinterest, donc tu voudrais créer un site où les utilisateurs peuvent créer des "pins". Chaque pin contient l'URL d'une image sur le net. Les utilisateurs peuvent commenter les pins, mais ne peuvent pas commenter les commentaires.


# Présentation du projet:

3 tabs : users, pins et comments

modèle user
modèle pin : 1 foreign key(id_user)
modèle commentaire: 2 foreign key (id_user & id_pin)

seed.rb utilisé pour générer des entrées

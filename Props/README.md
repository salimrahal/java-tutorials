# Utilisation de "Properties" 

##Propriété système

Initialisé lors de la commande java

java -Dcle=valeur ....

----

##Ou fichier de propriétés

Ensemble de lignes cle=valeur



salim@salim-desktop:~/Development/java-tutorials/Props$ java -Dconfig.file=myprop.env  -jar props/dist/props.jar HOME
config.file=myprop.env
HOME=/home/salim
aprop="a propertie a"


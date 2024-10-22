Pour le contrôle des moteurs, il est possible d'utiliser la bibliothèque *controller* rédigé par les professeurs.

## Problèmes avec *controller*

Cette bibliothèque n'est pas du même type de que *NumPy* ou *Matplotlib* dans le sens ou elle n'est pas installé directement dans l'environnement python. 
En effet, elle est liée au fichier *"controller.py"*, les programmes l'utilisant doivent donc être exécutés dans **le même dossier** que ce fichier. 

```
> [!ATTENTION]
> Il ne faut pas essayer d'installer controller via pip. 
```
([il s'agit d'une autre bibliothèque n'ayant rien à voir](https://pypi.org/project/controller/))

## Comment installer *controller* sur votre environnement entier ?


J'ai transformé le fichier *controller.py* en paquet pouvant être installé via *pip* dans tout votre environnement, pour cela, il suffit d'exécuter la commande :
```pip install git+https://github.com/4Pi-R2/controller.git#egg=controller```

Ainsi, vous pourrez utiliser *controller* peu importe le dossier dans lequel vous êtes en l'important normalement.

*De l’équipe 3 du groupe 1.*

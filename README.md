RDF pour PAIR
===

[![Join the chat at https://gitter.im/assemblee-virtuelle/pair](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/assemblee-virtuelle/pair?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Contient des ontologies,
des exemples de données,
des spécifications de formulaires,
pour la modélisation PAIR ( Projet- Acteur - Idée - Resource ) .


# Outils recommandés pour vérifier la syntaxe Turtle:

NE PAS COMMITER SANS VERIFIER LA SYNTAXE !!!!!!!!!

Utilitaire rapper:
    sudo apt-get install raptor2-utils
    for f in *.ttl ; do echo ====== $f ; rapper -i turtle $f ; read PAUSE ; done

- *validation Web: http://ttl.summerofcode.be/*
- [EulerGUI](http://svn.code.sf.net/p/eulergui/code/trunk/eulergui/html/documentation.html#L931)
- [Protégé](http://protege.stanford.edu/)
- Outil en ligne de commande: [CWM](http://www.w3.org/2000/10/swap/doc/CwmInstall)
- Outil en ligne de commande: [rapper](http://librdf.org/raptor/rapper.html)
- Raisonneurs (en ligne de commande): [Hermit](http://hermit-reasoner.com/download.html)
- [Pellet](http://clarkparsia.com/pellet/)

# Utiliser dans une application
Les spécifications de formulaires sont utilisables avec
[semantic\_forms](https://github.com/jmvanel/semantic_forms/blob/master/scala/forms_play/README.md)
,
et [WP-LDP](https://github.com/assemblee-virtuelle/wpldp/wiki/Installation).


# cycle de la vie du logiciel #
## Description ##
## Implémentation ##

-Codage

-Test

-Intégration

-Analyse

-Conception

 ```mermaid
 flowchart LR

 A(analyse)
 C(coception)
 D(codage )
 T(test)
 I(integration)
A-->C
C-->D
D-->T
T-->I
 ```
 ## source control ##
 la gestion du code source 
 on utilise git, mais il y a d'autres systemes(subversion,mercurial)
 ```mermaid
 flowchart LR
 C(code)
 R(loacal repository)
 G(github)
 C--commit-->R
 R--push-->G
 ```
 Mais il faut 
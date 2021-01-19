![Angular Logo](https://github.com/vercel/vercel/blob/master/packages/frameworks/logos/angular.svg)

# Angular Example

This directory is a brief example of an [Angular](https://angular.io/) app that can be deployed with Vercel and zero configuration.

## Deploy Your Own

Deploy your own Angular project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/vercel/tree/master/examples/angular)

_Live Example: https://angular.now-examples.now.sh_

### How We Created This Example

To get started with Angular, you can use the [Angular CLI](https://cli.angular.io/) to initialize the project:

```shell
$ ng new
```

_____________TD d�ployer une application sans code____________

4. 'vercel -v'

5. 'vercel init angular'

6. 'cd angular && vercel'

7. 'vercel ls td-vercel-augjosse'

8. 'vercel logs td-vercel-augjosse-aqbt72d7c.vercel.app'

9. 'vercel inspect td-vercel-augjosse.vercel.app'
Gr�ce � cette commande on peut voir les infos concernant le projet et son d�ploiement.
On peut visualiser : l'id, le nom, l'etat, l'url, la structure des fichiers, les routes, ...

10. Les variables d'environnement sont utilis�es pour ajouter des param�tres de configuration aux outils d�ploy�s avec Vercel en fonction de l'environnement.
Cela permet d'injecter des valeurs que l'on ne souhaite pas placer directement dans le code source.

11. 'vercel env add plain variable production'

12. 'vercel env ls'

13. Les variables d'environnement peuvent �tre cr�er en secret. Elles sont alors chiffr�es. 
Elles s�curisent le stockage et le partage des informations sensibles.

15. 'vercel secret add secret_2 ceciestunsecret'
'vercel env add secret secret_2 production' avec value : secret_2

16. Les 3 environnements que met automatiquement Vercel � notre disposition : PRODUCTION, PREVIEW, DEVELOPMENT
Cela permet de ne pas boulverser l'architecture de l'application lors des tests. 
Autrement dit, on developpe avec l'environnement DEVELOPMENT.
On fait les tests avec l'environnement PREVIEW.
Puis on push les modifs sur l'environnement PRODUCTION.

18. https://td-vercel-aj.vercel.app/

19. Une pull-request est une proposition de modification du projet. 
Les membres du groupe travaillant sur le m�me projet r�cup�re ce dernier.
Ils modifient le projet sur la nouvelle branche et envoient des pull-request pour envoyer ces modifications aux autres membres du projet.

Vercel deploie la pull-request dans un environnement PREVIEW.

20. Vercel deploie la pull-request dans un environnement PRODUCTION.

21. L'environnement de PRODUCTION correspond � la branche main.

Les pull-request permettent de pouvoir travailler � plusieurs sur un m�me projet. 
Ils permettent � un d�veloppeur de pr�venir les membres de son �quipe qu'il a termin� une fonctionnalit�.
On peut des versions temporaires du projet. Ils permettent de tester le bon fonctionnement du projet avant le deploiement.
On p�ut r�aliser des tests avant de merge.

Workflow d'une feature : 
- modification sur la branche de d�veloppement dans le working tree 
- commit et push des modifs sur la branche de d�veloppement de Git 
- pull-request et merge de la branche de developpement vers la branche de production 
- pull de la branche de production du depot vers la branche de production du working tree

22. Un serverless : quand un fournisseur de cloud fournit des ressources aux application � la demande. 
Il utilise des serveurs qui ne sont pas g�r� par le devellopeur, ce qui leur facilite la t�che.
Cela facilite le passage d'une application en production.


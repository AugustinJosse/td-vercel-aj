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

_____________TD déployer une application sans code____________

4. 'vercel -v'

5. 'vercel init angular'

6. 'cd angular && vercel'

7. 'vercel ls td-vercel-augjosse'

8. 'vercel logs td-vercel-augjosse-aqbt72d7c.vercel.app'

9. 'vercel inspect td-vercel-augjosse.vercel.app'
Grâce à cette commande on peut voir les infos concernant le projet et son déploiement.
On peut visualiser : l'id, le nom, l'etat, l'url, la structure des fichiers, les routes, ...

10. Les variables d'environnement sont utilisées pour ajouter des paramètres de configuration aux outils déployés avec Vercel en fonction de l'environnement.
Cela permet d'injecter des valeurs que l'on ne souhaite pas placer directement dans le code source.

11. 'vercel env add plain variable production'

12. 'vercel env ls'

13. Les variables d'environnement peuvent être créer en secret. Elles sont alors chiffrées. 
Elles sécurisent le stockage et le partage des informations sensibles.

15. 'vercel secret add secret_2 ceciestunsecret'
'vercel env add secret secret_2 production' avec value : secret_2

16. Les 3 environnements que met automatiquement Vercel à notre disposition : PRODUCTION, PREVIEW, DEVELOPMENT
Cela permet de ne pas boulverser l'architecture de l'application lors des tests. 
Autrement dit, on developpe avec l'environnement DEVELOPMENT.
On fait les tests avec l'environnement PREVIEW.
Puis on push les modifs sur l'environnement PRODUCTION.

17.


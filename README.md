Déployer une application

4. vercel -v    ->    Vercel CLI 21.1.0

5. vercel init

6. vercel deploy

7. vercel ls

8. vercel logs <url>  (https://vercelproject-8k4t4jixa.vercel.app)

9. vercel inspect <url> -> récupère des informations sur un ou des déploiements spécifiques

10. variable d'environnement -> permet d'injecter des valeurs que l'on ne souhaite pas mettre directement dans le code source. on peut les adapter facilement en fonction de l'environnement

11. vercel env add plain <var> production


12. vercel env ls

13. variables chiffrées cachées -> pour transmettre des données confidentielles

14.

15. vercel secret add secret_2 efcezfezc45
    vercel env add secret SECRET_2 production

16. development, preview, production
on a plusieurs environnement -> on développe sur development, teste sur preview et push sur production

18. tdgestionvoisin-6kw6u9uyr.vercel.app

19. on développe deux branches, on effectue des modification d'un côté ou de l'autre

git branch newbranch
git checkout newbranch

environnement development trigger

20. on merge les deux branches
environnement production trigger

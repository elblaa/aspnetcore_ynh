Le dossier d'installationd de l'application est  `__INSTALL_DIR__`

Pour installer votre propre application .net :
1. Publiez votre application dotnet `dotnet publish --configuration Release`
2. Remplacez le contenu de `__INSTALL_DIR__` par le contenu du dossier publish que vous avez généré précédemment
3. Renommez votre dll en `Elbla.Sample.AspNetCore.Ynh` ou éditez le nom de la dll dans le service systemd.

Référence utilisé pour le déploiement d'une application .net : [Documentation Microsoft](https://learn.microsoft.com/fr-fr/aspnet/core/host-and-deploy/linux-nginx?view=aspnetcore-9.0)

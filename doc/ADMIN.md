The app install dir is `__INSTALL_DIR__`

To install you own .net web app:
1. Publish your dotnet application `dotnet publish --configuration Release`
2. Replace the content of `__INSTALL_DIR__` with the content of the publish folder you previously generated
3. Rename your dll you generated to `Elbla.Sample.AspNetCore.Ynh` or edit the dll name in systemd service.

Reference used to deploy your .net app : [Microsoft documentation](https://learn.microsoft.com/en-us/aspnet/core/host-and-deploy/linux-nginx?view=aspnetcore-9.0)

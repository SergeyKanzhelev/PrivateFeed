#Private NuGet server

This is an implementation of private NuGet server that you can deploy and start using in seconds.

##Using

1. Deploy to Azure [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)
2. Open KuDu console at http://<sitename>.scm.azurewebsites.net
3. Go to *Debug Console* > *CMD*
4. Use command ```cd site\wwwroot\app_data``` to open App_Data folder
5. Drag and drop your ```*nupkg``` files to the folder
6. Use http://<sitename>.azurewebsites.net/nuget as a nuget feed

##Informaiton

Read more about deploying to azure button at [azure blog](http://azure.microsoft.com/en-us/blog/deploy-to-azure-button-for-azure-websites-2/).

Read about hosting your own nuget feeds using ```NuGet.Server``` package at [docs.nuget.org](https://docs.nuget.org/create/hosting-your-own-nuget-feeds).
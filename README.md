# .NET 6 ASP.NET MVC Application for [Tanzu Application Platform](https://tanzu.vmware.com/application-platform)

Deploy by running:

`tanzu apps workload create dotnet-mvc --git-repo https://github.com/fjb4/dotnet-mvc --git-branch master --type web`

or

`tanzu apps workload create dotnet-mvc -f ./config/workload.yaml`
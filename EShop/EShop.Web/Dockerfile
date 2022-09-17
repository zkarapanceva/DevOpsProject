FROM mcr.microsoft.com/dotnet/sdk:6.0
WORKDIR /App
COPY bin/Release/net6.0/publish/ App/ 
EXPOSE 5000
ENTRYPOINT ["dotnet", "App/EShop.Web.dll"]


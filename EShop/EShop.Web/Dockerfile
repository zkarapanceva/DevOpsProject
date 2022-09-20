FROM mcr.microsoft.com/dotnet/sdk:6.0
WORKDIR /App
COPY bin/Release/net6.0/publish/ .
EXPOSE 5000
ENTRYPOINT ["dotnet", "EShop.Web.dll"]
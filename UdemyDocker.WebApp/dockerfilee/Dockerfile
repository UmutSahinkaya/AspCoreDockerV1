# Katmanlı mimari
# FROM mcr.microsoft.com/dotnet/core/sdk:3.1 as build
# WORKDIR /app
# COPY ./UdemyNLayerProject.Core/*.csproj ./UdemyNLayerProject.Core/
# COPY ./UdemyNLayerProject.Data/*.csproj ./UdemyNLayerProject.Data/
# COPY ./UdemyNLayerProject.Service/*.csproj ./UdemyNLayerProject.Service/
# COPY ./UdemyNLayerProject.Web/*.csproj ./UdemyNLayerProject.Web/
# COPY *.sln .
# RUN dotnet restore
# COPY . .
# RUN dotnet publish ./UdemyNLayerProject.Web/*.csproj -o /publish/
# FROM mcr.microsoft.com/dotnet/core/aspnet:3.1
# WORKDIR /app
# COPY --from=build /publish .
# ENV ASPNETCORE_URLS="http:/*:5000"
# ENTRYPOINT [ "dotnet","UdemyNLayerProject.Web.dll" ]

# Unit Test Projesi
#FROM mcr.microsoft.com/dotnet/core/sdk:3.1 as build
#WORKDIR /app
#COPY ./UdemyRealWorldUnitTest.Test/*.csproj ./UdemyRealWorldUnitTest.Test/
#COPY ./UdemyRealWorldUnitTest.Web/*.csproj ./UdemyRealWorldUnitTest.Web/
#COPY *.sln .
#RUN dotnet restore
#COPY . .
#RUN dotnet Test ./UdemyRealWorldUnitTest.Test/*.csproj
#RUN dotnet publish ./UdemyRealWorldUnitTest.Web -o /publish/
#FROM mcr.microsoft.com/dotnet/core/aspnet:3.1
#WORKDIR /app
#COPY --from=build /publish .
#ENV ASPNETCORE_URLS="http://*:5000"
#ENTRYPOINT [ "dotnet","UdemyRealWorldUnitTest.Web.dll" ]

FROM mcr.microsoft.com/dotnet/core/aspnet:2.2-stretch-slim
WORKDIR /app

# Copy the published web app
#COPY /aspnet-core-dotnet-core/ /app

# Copy published files from the pipeline
COPY ./publish .

# Expose the default port
EXPOSE 80

# Run command
ENTRYPOINT ["dotnet", "aspnet-core-dotnet-core.dll"]

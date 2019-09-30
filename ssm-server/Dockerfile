FROM microsoft/dotnet:2.2-sdk AS build
WORKDIR /app
RUN mkdir /data

ENTRYPOINT ["dotnet", "watch", "run", "--urls", "http://0.0.0.0:5000"]
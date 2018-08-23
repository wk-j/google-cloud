FROM gcr.io/google-appengine/aspnetcore
ADD ./ /app
ENV ASPNETCORE_URLS=http://*:${PORT}
WORKDIR /app
ENTRYPOINT [ "dotnet", "GoogleCloud.dll" ]
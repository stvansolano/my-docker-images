FROM mcr.microsoft.com/mssql/server:2017-latest
CMD -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=12345abC' \
   -p 1433:1433 --name sql1
EXPOSE 1433
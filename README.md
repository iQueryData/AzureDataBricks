# AzureDataBricks
Learning Notes of Azure DataBricks 

MSSQL_SA_PASSWORD="Admin"
MSSQL_PID=Developer
MSSQL_USER=Admin



docker run --cap-add SYS_PTRACE -e "ACCEPT_EULA=1" -e "MSSQL_SA_PASSWORD=Admin" -e "MSSQL_PID=Developer" -e "MSSQL_USER=Admin" -p 1433:1433 --name azuresqledge -d mcr.microsoft.com/azure-sql-edge
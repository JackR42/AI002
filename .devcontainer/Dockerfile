# .devcontainer/Dockerfile
FROM mcr.microsoft.com/mssql/server:latest

# Set environment variables for SQL Server
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=YourStrongPassword123!  # Replace with a strong password!

# Expose the SQL Server port (1433)
EXPOSE 1433

# Optional: Copy SQL scripts to initialize the database
# COPY ./scripts/ /docker-entrypoint-initdb.d/

# Optional: Add other dependencies or configurations as needed
# ...

# Parsan_Auth

This is a Simple Authentication API using IdentityServer4.

# 1 - Clone Repository 

to use this api just clone it with this command 

`git clone https://github.com/haftado3/parsan_auth.git`


# 2 - Execution 

then run the api with this command:

` dotnet run `

will be executed on `https://localhost:5055` which could be changed from `launchSettings.json`

# In Case of Certificate Error 

` dotnet dev-certs https --trust `

# Config

for authentication server all configs are in `config.cs` file (`ClientId ,ClientSecrets`)
